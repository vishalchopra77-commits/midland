# Property tracker

Password-protected rent, bond and utility tracker.

The application is encrypted with AES-256-GCM. The browser derives a key using PBKDF2-SHA256 and decrypts locally. The password is not embedded in the repository or sent to a server.

User edits are stored in browser localStorage and do not sync between devices. Existing local-file data does not automatically transfer to this site. Locking closes the app but keeps saved records in the same browser.

Host index.html using GitHub Pages over HTTPS.
