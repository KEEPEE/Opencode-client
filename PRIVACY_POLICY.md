# Privacy Policy

**OpenCode Client**
**Effective Date: February 28, 2026**
**Last Updated: February 28, 2026**

Keepee ("we", "us", "our") operates the OpenCode Client mobile application (the "App"). This Privacy Policy describes how we collect, use, and protect your information when you use our App.

## 1. Information We Collect

### 1.1 Information You Provide
- **Server connection details**: Server URLs, usernames, and passwords that you enter to connect to your OpenCode servers.
- **Chat content**: Messages you send through the App to your OpenCode server.

### 1.2 Information We Do NOT Collect
- We do **not** collect personal identification information beyond what you provide for server authentication.
- We do **not** use analytics or tracking services.
- We do **not** collect device identifiers, location data, or browsing history.
- We do **not** display advertisements.

## 2. How Your Data Is Stored

### 2.1 Local Storage Only
All data is stored **locally on your device**:
- Server connection details (URLs, usernames) are stored in the app's local storage (SharedPreferences).
- **Passwords are encrypted** using platform-native secure storage:
  - **Android**: EncryptedSharedPreferences (AES encryption with keys in Android Keystore)
  - **iOS / macOS**: Keychain Services
  - **Linux**: libsecret (GNOME Keyring / KWallet)
  - **Windows**: Windows Credential Manager

### 2.2 No Cloud Storage
We do **not** store any of your data on our servers. The App communicates directly with the OpenCode servers that **you** configure. We have no access to these servers or the data exchanged between the App and your servers.

## 3. Data Transmission

### 3.1 Communication with Your Servers
The App communicates with OpenCode servers that you configure. This communication:
- Is initiated solely by you
- Uses HTTPS when the server supports it
- Includes authentication credentials (Basic Auth) that you provide
- Transmits chat messages, project information, and session data

### 3.2 No Third-Party Data Sharing
We do **not** share, sell, rent, or trade your data with any third parties. Your data never leaves your device except when communicating with the OpenCode servers you have configured.

## 4. Data Security

We take reasonable measures to protect your data:
- Passwords are stored using platform-native encrypted storage
- No sensitive data is transmitted to our servers
- All server communication uses the protocols configured by you

## 5. Children's Privacy

The App is not intended for use by children under the age of 13. We do not knowingly collect personal information from children under 13.

## 6. Your Rights

You have the right to:
- **Access** your data: All data is stored locally on your device and is accessible to you.
- **Delete** your data: You can delete all stored data by removing server entries from the App or by uninstalling the App.
- **Control** your data: You choose which servers to connect to and what information to provide.

## 7. Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be reflected in the "Last Updated" date above. Continued use of the App after changes constitutes acceptance of the updated policy.

## 8. Open Source Components

The App uses open-source software components licensed under their respective licenses. A list of dependencies is available in the `pubspec.yaml` file in the project repository.

## 9. Contact Us

If you have any questions about this Privacy Policy, please contact us at:

**Email**: sp.keepee@gmail.com

---

Copyright (c) 2026 Keepee. All rights reserved.
