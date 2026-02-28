# OpenCode Client

[![Platform](https://img.shields.io/badge/platform-ios%20%7C%20android%20%7C%20macos%20%7C%20windows%20%7C%20linux-blue)](https://flutter.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**OpenCode Client** is a modern, multi-platform mobile client built with Flutter, designed to interface with the **OpenCode AI Assistant**. It allows you to manage your programming projects and communicate with AI directly from your mobile device or tablet.

---

## 📩 Support & Contact

If you encounter any issues, have questions about using the app, or wish to report a bug, please use the following channels:

* **Email:** [sp.keepee@gmail.com](mailto:sp.keepee@gmail.com) (Primary support contact)
* **GitHub Issues:** [Report an issue here](https://github.com/KEEPEE/Opencode-client/issues)
* **Web:** [GitHub Repository](https://github.com/KEEPEE/Opencode-client)

---

## ✨ Key Features

### 🤖 AI Chat Assistant
* **Interactive Conversations:** Ask questions, request code explanations, or ask for new feature implementations.
* **Multi-Model Support:** Seamlessly switch between OpenAI, Anthropic, OpenRouter, and other AI models.
* **Streaming & Reasoning:** Watch responses generate in real-time and view the AI's "thought process" for complex tasks.

### 📁 Project Management
* **Git Integration:** Connect to existing repositories hosted on your OpenCode server.
* **File Explorer:** Browse directory structures and files directly within the app.
* **Multi-Project Management:** Manage and switch between several projects simultaneously.

### 🔒 Security & Control
* **Permission Management:** You approve or deny AI requests to modify files or execute terminal commands.
* **Detailed Diff View:** Review exactly what the AI changed with a clear visual diff before committing.
* **Secure Local Storage:** Credentials and server details are stored locally and securely on your device.

---

## 📱 Supported Platforms
Thanks to the Flutter framework, OpenCode Client is available for:
* ✅ **iOS** (iPhone & iPad)
* ✅ **Android**


---

## 🛠️ Installation for Developers

1.  Ensure you have the [Flutter SDK](https://docs.flutter.dev/get-started/install) installed.
2.  Clone the repository:
    ```bash
    git clone [https://github.com/KEEPEE/Opencode-client.git](https://github.com/KEEPEE/Opencode-client.git)
    ```
3.  Install dependencies:
    ```bash
    flutter pub get
    ```
4.  Run the application:
    ```bash
    flutter run
    ```

---

## 🎯 Quick Start Guide

1.  **Add a Server:** Tap `+`, enter your OpenCode server URL, and test the connection.
2.  **Select a Project:** Choose a git repository you wish to work on.
3.  **Start Chatting:** Start a new session, select your preferred AI model, and enter your prompt.
4.  **Manage Changes:** Go to "View changes" to approve or reject edits made by the assistant.

---

## 🏗️ Technical Architecture
The app follows **Clean Architecture** principles:
* `lib/api/` - HTTP client for server communication.
* `lib/models/` - Data models (Project, Session, Message).
* `lib/screens/` - UI layers built with Material Design 3.
* `lib/services/` - Local services and state management (Provider).

---

## 🤝 Contributing
Contributions are welcome! If you have ideas for improvements or found a bug:
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add AmazingFeature'`).
4. Push to the branch and open a Pull Request.

---

## 📝 License
https://github.com/KEEPEE/Opencode-client/blob/main/LICENSE

