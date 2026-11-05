
# Privacy Policy

**Last updated: November 5, 2026**

## 1. Application description

This application is a personal, single-user installation of Rclone running on Ubuntu Linux. Rclone is open-source software used to synchronize files between a local computer and the user's Google Drive account.

It is not a commercial service and is not offered to third parties.

## 2. Google user data accessed

The application uses Google OAuth 2.0 authorization with the Google Drive scope:

`https://www.googleapis.com/auth/drive`

This scope grants broad access to the user's Google Drive files. Although the authorization permits broad access, this installation is configured to synchronize only selected folders: Documents, Images and Videos, together with associated backup folders.

## 3. How Google user data is used

Google Drive data is accessed exclusively to:
- List and inspect files and folders involved in synchronization.
- Upload new or modified local files to Google Drive.
- Download new or modified Google Drive files to the local computer.
- Apply changes and deletions as part of bidirectional synchronization.
- Maintain backup copies of replaced or deleted files.

All synchronization operations are initiated by Rclone on the user's own computer.

## 4. Data storage and sharing

Files are transferred directly between the user's local computer and Google Drive through Google's APIs.

No separate application server is operated by the developer. Google Drive files are not uploaded to GitHub.

OAuth credentials and authorization tokens are stored locally in the Rclone configuration on the user's computer.

The application does not sell, rent or share Google user data with third parties.

## 5. Data retention

Synchronized files remain on the local computer and Google Drive according to the user's synchronization settings.

Backup copies are retained for approximately 30 days locally and 90 days on Google Drive, after which they are automatically deleted according to the configured cleanup procedure.

## 6. Revoking access

The user can revoke the application's access at any time through their Google Account security settings, under third-party connections.

The local OAuth credentials and tokens can also be removed by deleting the Rclone configuration from the computer.

## 7. Security

Access to Google Drive is protected by Google's OAuth 2.0 authorization mechanism.

The application does not operate a remote database or server containing Google user files or OAuth tokens.

## 8. Contact

For privacy-related questions, please use the developer contact email address listed on the application's Google OAuth consent screen.

