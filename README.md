# 🐰 SaveTheBunny - Android 2D Game

A simple and engaging 2D Android game where you control a rabbit and dodge falling spikes. Built using native Android SDK with Java and XML layouts. The game tracks points and high scores, and features a dynamic health bar.

---

## ✅ Prerequisites

Before you build or run this project, make sure you have the following installed:

- ✅ Android Studio (Chipmunk or newer)
- ✅ Android SDK (API level 25 or higher)
- ✅ Java Development Kit (JDK 8+)
- ✅ A physical Android device (API 23+) or emulator
- ✅ Gradle (handled automatically by Android Studio)

---

## 🗂 Project Structure

```plaintext
SaveTheBunny/
├── app/
│   ├── java/com/example/savethebunny/
│   │   ├── MainActivity.java         # Entry point
│   │   ├── GameView.java             # Game engine & logic
│   │   ├── GameOver.java             # Game over screen
│   │   ├── Spike.java                # Falling spike logic
│   │   └── Explosion.java            # Optional: spike hit animation
│   ├── res/
│   │   ├── drawable/                 # Game assets: background, bunny, spike, UI icons
│   │   ├── layout/
│   │   │   ├── activity_main.xml     # Game screen layout
│   │   │   └── game_over.xml         # Game Over screen layout
│   │   └── values/                  # Strings, colors, dimensions
├── build.gradle.kts                 # Project build config
├── settings.gradle.kts              # Gradle module linking
├── gradlew / gradlew.bat            # Gradle wrapper scripts
└── .gitignore                       # Files to exclude from version control

---

## ▶️ How to Run the App
Connect your Android phone with USB debugging enabled
or start an Android emulator (API 23 or higher)

Click the Run ▶ button in Android Studio

Select your device when prompted

The app will build, install, and launch on your device


🎮 Game Functionality
You control a bunny 🐰 using touch input (drag left/right)

Spikes fall from the top of the screen

For each successful dodge, you earn +10 points

The health bar shows how many lives you have left:

💚 Green = 3 lives

💛 Yellow = 2 lives

❤️ Red = 1 life

If the bunny is hit 3 times, the game ends

You are taken to a Game Over screen which shows:

Your current score

Your highest score

You can then Restart the game or Exit

