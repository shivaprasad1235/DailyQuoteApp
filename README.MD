# Daily Quote App

A simple Android app that displays a random daily quote, allows users to favorite quotes, and share them.

## Features
- Random quote from public API
- Save favorite quotes
- Persistent storage using SharedPreferences
- Share quote via system share sheet
- Jetpack Compose UI

## Tech Stack
- Kotlin
- Jetpack Compose
- Retrofit
- ZenQuotes API

## AI Tools Used
- ChatGPT – used for:
    - Generating Jetpack Compose UI
    - API integration with Retrofit
    - Debugging crashes using Logcat
    - Iterating on API issues and fixes
- Stitch – used to generate initial UI design

## AI Workflow
I used AI tools to rapidly scaffold the app, generate Compose layouts, and debug issues.
When the app crashed due to missing permissions, I used Logcat output to identify the issue and fixed it.
When the initial API failed on my device, I iterated by switching to a more stable API and updated the data model accordingly.

## Setup Instructions
1. Clone the repository
2. Open in Android Studio
3. Sync Gradle
4. Run on emulator or physical device

## Design
Designs were generated using Stitch.
(Screenshots / link included)
## Screenshots

### Home Screen
![Home Screen](screenshots/home_screen.png)

### Favorites Screen
![Favorites Screen](screenshots/favorites_screen.png)
