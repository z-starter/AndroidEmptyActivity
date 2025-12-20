# AndroidEmptyActivity 🚀

A clean, modern, and minimal Android project template built with Kotlin. Kickstart your next Android application with a well-structured foundation that follows current best practices.

![Kotlin](https://img.shields.io/badge/Kotlin-100%25-7F52FF?logo=kotlin&logoColor=white)
![License](https://img.shields.io/github/license/z-starter/AndroidEmptyActivity)
![GitHub Releases](https://img.shields.io/github/v/release/z-starter/AndroidEmptyActivity?include_prereleases)
![GitHub Last Commit](https://img.shields.io/github/last-commit/z-starter/AndroidEmptyActivity)

## 📖 Overview

**AndroidEmptyActivity** is designed to eliminate the initial setup friction for new Android projects. It provides a streamlined "Empty Activity" template, pre-configured with a sensible project structure, common Gradle configurations, and essential files, allowing you to focus on writing your app's unique logic from the very first commit.

This repository serves as both a usable template and a reference for modern Android development setup.

## ✨ Features

*   **Modern Kotlin-First**: Built entirely with Kotlin, leveraging its conciseness and safety features.
*   **Clean Architecture Ready**: Organized project structure that can easily scale to fit Clean Architecture patterns.
*   **Latest Tooling**: Configured with up-to-date Gradle settings and dependencies (check `build.gradle.kts`).
*   **CI/CD Integration Ready**: Includes a `.github/workflows` directory, prepped for automated builds and tests.
*   **Minimal Dependencies**: Starts lean. Add only the libraries you need for your specific project.

## 🚀 Getting Started

### Prerequisites

*   **Android Studio** (Latest stable version is recommended)
*   **Android SDK**
*   **Java Development Kit (JDK)** 11 or higher

### Installation

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/z-starter/AndroidEmptyActivity.git
    ```
2.  **Open in Android Studio:**
    *   Launch Android Studio.
    *   Select "Open" and navigate to the cloned `AndroidEmptyActivity` directory.
3.  **Sync the Project:**
    *   Android Studio will automatically detect the Gradle files and begin syncing. Click "Sync Now" if prompted.
4.  **Run the App:**
    *   Connect an Android device or start an emulator.
    *   Click the **Run** button (green triangle) to build and launch the app.

You should now see a basic "Hello World" app running on your device.

## 📁 Project Structure

A quick overview of the key directories and files:
```
AndroidEmptyActivity/
├── .github/workflows/ # GitHub Actions CI/CD configuration files
├── app/ # Main application module
│ ├── src/main/
│ │ ├── kotlin/ # Your Kotlin source code
│ │ └── res/ # App resources (layouts, strings, drawables)
│ └── build.gradle.kts # Module-specific Gradle configuration
├── gradle/
│ └── wrapper/ # Gradle Wrapper (ensures consistent builds)
├── .gitignore # Standard Git ignore rules for Android
├── build.gradle.kts # Project-level Gradle configuration
└── settings.gradle.kts # Defifies included modules
```

## 🤝 Contributing

Contributions are welcome! If you have suggestions to improve this starter template, such as adding useful default configurations, updating dependencies, or improving documentation:

1.  Fork the Project.
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`).
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`).
4.  Push to the Branch (`git push origin feature/AmazingFeature`).
5.  Open a Pull Request.

Please ensure your code adheres to the existing style.

## 🙏 Acknowledgments

*   This template is maintained by the [z-starter](https://github.com/z-starter) organization.
*   Thanks to all contributors who help keep this project up-to-date.

---

**Happy Coding!** If you find this template useful, consider giving it a ⭐ on GitHub.

