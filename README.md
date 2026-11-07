<h1 align="center">Derivify: The Calculus Toolkit</h1>

<p align="center">
<a href="https://github.com/codewithmahad/Derivify-Calculus-Toolkit/releases/latest"><img src="https://img.shields.io/github/v/release/codewithmahad/Derivify-Calculus-Toolkit?style=for-the-badge&label=Latest%20Release"></a><a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge"></a><a href="https://developer.android.com/jetpack/compose"><img src="https://img.shields.io/badge/Jetpack%20Compose-UI-blue?style=for-the-badge&logo=android"></a><a href="https://kotlinlang.org/"><img src="https://img.shields.io/badge/Kotlin-100%25-orange?style=for-the-badge&logo=kotlin"></a>
</p>

<p align="center">
  An Android calculus toolkit built with Kotlin, Jetpack Compose, and a custom symbolic differentiation engine.
</p>

---

I built **Derivify** for my second-semester **Multi-Variable Calculus** course at UBIT. It brings together partial derivatives, gradients, and calculus quizzes in a native Android app, with a symbolic differentiation engine written in Kotlin.

## 📱 Application Showcase


| Calculator | Navigation Menu | Quiz Selection | Quiz in Progress |
| :---: | :---: | :---: | :---: |
| <img src="screenshots/calculator.png" alt="Calculator Screen" width="200"/> | <img src="screenshots/navigation.png" alt="Navigation Drawer" width="200"/> | <img src="screenshots/quiz_difficulty.png" alt="Quiz Difficulty Screen" width="200"/> | <img src="screenshots/quiz_question.png" alt="Quiz Question Screen" width="200"/> |

## Features

The app combines calculus calculations with practice questions.

### The Calculators
The implemented calculators cover:

* **Partial Derivatives:** Solves partial derivatives for functions with multiple variables.
* **Gradients:** Finds the gradient vector `∇f` of a function.

Directional derivatives appear in the navigation, but that screen is still marked as in progress.

### The Calculus Quiz
The quiz contains calculus questions grouped into four difficulty levels.

* **Easy:** A review of foundational rules (Power Rule, Product Rule, etc.).
* **Medium:** A mix of chain rules, implicit differentiation, and inverse trig.
* **Hard:** Multi-variable topics like partial derivatives and gradients.
* **Nightmare:** Mixed partials, directional derivatives, and other advanced questions.

## 🏗️ How It's Built

The UI and calculation state are separated through ViewModels.

* **Language:** 100% **Kotlin**
* **User Interface:** **Jetpack Compose** with **Material 3** for a fully declarative, modern UI
* **Architecture:** **MVVM (Model-View-ViewModel)** for a clean separation between UI and logic
* **State Management:** Using `ViewModels` and `MutableState` for efficient UI reactivity

### Key Technical Feature: Custom Math Engine
The core of this application is a **custom-built symbolic differentiation engine**. Instead of relying on external libraries, this engine:
1.  **Parses** user-input functions into an Abstract Syntax Tree (AST).
2.  **Recursively applies** calculus rules (Power, Product, Chain Rule, etc.) to the tree.
3.  **Generates** symbolic derivative expressions for the functions supported by the engine.

### Built With
<p align="center">
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=android&logoColor=white"/>
  <img src="https://img.shields.io/badge/Material%203-673AB7?style=for-the-badge&logo=materialdesign&logoColor=white"/>
  <img src="https://img.shields.io/badge/MVVM-FF6F00?style=for-the-badge&logo=architecture&logoColor=white"/>
</p>

## 📲 Download & Installation

The latest installable `.apk` file is available on the **Releases** page.

1.  Navigate to the [**Latest Release**](https://github.com/codewithmahad/Derivify-Calculus-Toolkit/releases/latest)
2.  Under **Assets**, download the `app-release.apk` file
3.  Open it on your Android device (enable *Install from Unknown Sources* if prompted)

## 🛠️ Building from Source

To run this archived project locally:

1.  Clone the repository:
    ```bash
    git clone https://github.com/codewithmahad/Derivify-Calculus-Toolkit.git
    ```
2.  Open the repository root in Android Studio, using a version compatible with the checked-in Android Gradle Plugin.
3.  Let Gradle sync and build the project.
4.  Run on an emulator or a physical device.

## 🤝 Contributing

This repository is archived and no longer accepts issues or pull requests. You can fork it to explore the code or make your own changes.

## About Me

I’m **Mahad** (`codewithmahad`), a software engineering student at UBIT. I’ve kept this project as a record of my Android coursework.

<p align="center">
<a href="https://www.linkedin.com/in/codewithmahad"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<a href="https://github.com/codewithmahad"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

<p align="center">
  <b>Developed with ❤️ by <a href="https://www.linkedin.com/in/codewithmahad">Shaikh Mahad</a></b> <br>
  <sub>© 2025 Shaikh Mahad · MIT License.</sub>
</p>
