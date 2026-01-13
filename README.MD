📱 Daily Quote App

A simple and elegant Daily Quote Android application built using Jetpack Compose, designed to demonstrate clean UI, basic persistence, authentication, and effective use of AI tools during development.

✨ Features
🔐 Authentication (Firebase)

Email & password sign up

Login and logout functionality

Session persistence (stay logged in)

Simple user profile screen showing logged-in email

💬 Quotes

Display a random daily quote on the home screen

Save quotes to favorites

View all favorite quotes in a dedicated screen

Favorites persist locally between app sessions

🔔 Daily Quote Notification

Daily quote notification scheduled using WorkManager

Notification triggers once per day automatically

🎨 UI & Design

Built fully with Jetpack Compose

Clean and minimal UI

Bottom navigation for core features

Profile access via top-right icon (standard Android UX pattern)

🧠 AI-Assisted Development Workflow

This project was built with extensive use of AI tools to improve development speed and code quality.

AI tools used:

ChatGPT – architecture planning, Compose UI guidance, debugging errors, and Gradle configuration help

How AI helped:

Breaking down features into manageable steps

Debugging build and dependency issues

Iterating quickly on UI and navigation logic

Making informed architectural decisions (e.g., choosing Firebase for Android stability)

AI was used as a development assistant, not as a replacement for understanding or decision-making.

🎨 Design Process

UI designs were generated using Stitch (Google AI design tool)

The designs were used as inspiration and then manually implemented in Jetpack Compose

Screenshots of the designs are included in the repository

📁 Designs / Screenshots:
/screenshots folder in this repository

🛠 Tech Stack

Language: Kotlin

UI: Jetpack Compose (Material 3)

Authentication: Firebase Authentication

Persistence: SharedPreferences / Local storage

Notifications: WorkManager

Architecture: Simple modular separation (UI, Auth, Data, Notifications)

🚀 Setup Instructions
Prerequisites

Android Studio (latest stable version)

Android SDK 33+

Firebase account

Steps

Clone the repository:

git clone https://github.com/<your-username>/DailyQuoteApp.git


Open the project in Android Studio

Sync Gradle dependencies

Add your google-services.json file (Firebase setup)

Run the app on an emulator or physical device

📸 Screenshots

Screenshots of the app and UI designs can be found in the screenshots/ directory.

🎥 Demo Video

A Loom video walkthrough is included in the submission, demonstrating:

App functionality

Authentication flow

Profile screen

Favorites

Design process

AI-assisted workflow

📌 Notes

Firebase was chosen over other backend options for its official Android support and SDK stability

Material 3 experimental APIs are used with proper opt-in annotations

The focus of this project is quality, clarity, and correctness, not feature overload

👤 Author

Shiva Prasad
Android Developer
GitHub: https://github.com/shivaprasad1235/DailyQuoteApp