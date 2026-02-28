# OpenCode Client

[![Platform](https://img.shields.io/badge/platform-iOS%20%7C%20Android-blue)](https://flutter.dev)
[![License](https://img.shields.io/badge/License-Proprietary-red.svg)](/LICENSE)

**OpenCode Client** is a multi-platform mobile app for communicating with the [OpenCode AI Assistant](https://opencode.ai) directly from your phone or tablet. Manage your programming projects, review AI-generated code changes, and control every action the assistant takes -- all from one app.

---

## 📩 Support & Contact

If you encounter any issues, have questions, or wish to report a bug:

- **Email:** [sp.keepee@gmail.com](mailto:sp.keepee@gmail.com)
- **GitHub Issues:** [Report an issue](https://github.com/KEEPEE/Opencode-client/issues)

---

## ✨ Features

### AI Chat Assistant
- **Multi-model support** -- switch between providers (OpenAI, Anthropic, Google, OpenRouter, and more) with a built-in provider filter
- **Real-time streaming** -- watch responses generate token-by-token with a live progress indicator
- **Reasoning view** -- inspect the AI's step-by-step thought process for complex tasks
- **Session history** -- resume any previous conversation at any time; sessions are organized by project and directory
- **Live task list** -- see the AI's current to-do list update in real time as it works

### Project & Directory Management
- **Server-side projects** -- connect to OpenCode servers running on your own infrastructure
- **Directory browser** -- navigate the remote file system, create new project directories, and select where to work
- **Subdirectory session discovery** -- select a parent directory and see sessions from all child projects at once
- **Multi-project switching** -- manage several projects simultaneously

### Security & Control
- **Permission management** -- every file edit and terminal command the AI wants to run requires your explicit approval
- **Diff view** -- review exactly what changed (additions, deletions, modified files) before committing
- **Encrypted credential storage** -- passwords are stored in the platform-native keychain/keystore (iOS Keychain, Android Keystore, libsecret on Linux, Windows Credential Manager), never in plain text
- **Agent questions** -- answer contextual questions the AI asks to better understand your requirements

### Additional Capabilities
- **SSE event stream** with auto-reconnect -- real-time notifications for permissions, questions, and task updates
- **Tool call inspector** -- see every bash command, file edit, and search the AI performs
- **Model switching mid-session** -- change the AI model at any point during a conversation without losing context
- **Pull-to-refresh** everywhere -- always see the latest state

---

## 📱 Supported Platforms

- ✅ **iOS** (iPhone & iPad)
- ✅ **Android**

---

## 🎯 How to Use

1. **Add a Server** -- tap `+`, enter your OpenCode server URL and credentials, and test the connection.
2. **Select a Project** -- pick an existing project or create a new directory.
3. **Start Chatting** -- choose an AI model (with provider filtering) and type your request.
4. **Review Changes** -- tap "View changes" to see a detailed diff of everything the AI modified.
5. **Approve or Deny** -- the AI asks for permission before executing commands or editing files. You stay in control.

---

## 🔐 Security

| Data | Storage | Encryption |
|------|---------|------------|
| Server URLs, usernames | Local app storage | No (non-sensitive) |
| Passwords | Platform secure storage | Yes (AES / Keychain / Keystore) |
| Chat history | On your OpenCode server | Controlled by you |

The app does **not** collect analytics, display ads, or share any data with third parties. All communication happens directly between your device and the OpenCode server you configure.

For full details, see our [Privacy Policy](/PRIVACY_POLICY.md).

---

## 📝 Legal

- [License](/LICENSE) (Proprietary -- Copyright 2026 Keepee)
- [Privacy Policy](/PRIVACY_POLICY.md)
- [Terms of Service](/TERMS_OF_SERVICE.md)

---

Made with care for the OpenCode community.
