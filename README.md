# Zomato Clone 

[![Android](https://img.shields.io/badge/Platform-Android-brightgreen.svg)](https://www.android.com)
[![Kotlin](https://img.shields.io/badge/Language-Kotlin-purple.svg)](https://kotlinlang.org)
[![Jetpack Compose](https://img.shields.io/badge/UI-Jetpack%20Compose-blue.svg)](https://developer.android.com/jetpack/compose)

A high-fidelity mobile application clone of **Zomato**. This project demonstrates modern Android development practices, emphasizing a reactive UI and declarative design patterns using Jetpack Compose.

---

## 📱 Features

* **Dynamic Home Screen**: Categorized restaurant listings, promotional banners, and location-based recommendations.
* **Search Functionality**: Deep-search capabilities for dishes, cuisines, and local dining spots.
* **Detailed Restaurant Profiles**: View menus, ratings, reviews, and high-quality food galleries.
* **Interactive UI**: Smooth transitions and sleek animations.
* **Dark Mode Support**: Fully compatible with system-wide light and dark themes.

## 🛠️ Tech Stack

* **Language**: [Kotlin](https://kotlinlang.org/)
* **UI Framework**: [Jetpack Compose](https://developer.android.com/jetpack/compose)
* **Architecture**: MVVM (Model-View-ViewModel)
* **Image Loading**: Coil
* **Dependency Injection**: Hilt (if applicable)
* **Navigation**: Compose Navigation Component

## 📸 Screenshots

| Home Screen | Search Results | Restaurant Detail |
| :---: | :---: | :---: |
| <img src="[PASTE_LINK_HERE]" width="200"> | <img src="[PASTE_LINK_HERE]" width="200"> | <img src="[PASTE_LINK_HERE]" width="200"> |

> **Note:** To add images, upload your screenshots to the repository and replace `[PASTE_LINK_HERE]` with the file path.

---

## 🚀 Getting Started

To get a local copy up and running, follow these steps:

### Prerequisites
* Android Studio Flamingo or later.
* JDK 11 or higher.

### Installation
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/ren276/Compose-Camp-Final-App.git](https://github.com/ren276/Compose-Camp-Final-App.git)
    ```
2.  **Open the project** in Android Studio.
3.  **Sync the project** with Gradle files.
4.  **Run the app** on an Emulator or Physical Device.

## 📂 Project Structure
```text
app/src/main/java/com/example/zomatoclone/
├── ui/                 # Composable screens and components
│   ├── theme/          # Color, Type, and Shape definitions
│   ├── components/     # Reusable UI widgets
│   └── screens/        # Main feature screens (Home, Profile, etc.)
├── data/               # Models and Data Sources
├── viewmodel/          # Business logic and UI State management
└── navigation/         # NavHost and Route definitions
