# 🎵 MiniSpotify

> A Spotify-inspired Android music streaming app for favorites management, built with Kotlin and Jetpack Compose.

![Kotlin](https://img.shields.io/badge/Kotlin-1.9-purple?logo=kotlin)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-MVVM-4285F4?logo=android)
![Android](https://img.shields.io/badge/Android-API_33-green?logo=android)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📌 Overview

MiniSpotify is an Android application that replicates core Spotify features including music browsing, album viewing, and favorites management. Built with modern Android development practices using Jetpack Compose and MVVM architecture.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Language | Kotlin |
| UI | Jetpack Compose, Material Design |
| Architecture | MVVM |
| Navigation | Jetpack Navigation |
| Networking | Retrofit + mock RESTful API (json-server) |
| Local Storage | Room Database |
| Media Playback | Google ExoPlayer |

---

## ✨ Features

- 🎵 **Music Feed** — Browse songs and albums with a modern, responsive UI
- ❤️ **Favorites Management** — Add and manage favorite tracks
- 💿 **Album View** — Explore albums and track listings
- 🔊 **Global Playback** — Seamless music playback across screens via Google ExoPlayer
- 💾 **Offline Caching** — Local favorites stored with Room Database
- 🔄 **Mock API Integration** — Data fetching via Retrofit against a json-server backend

---

## 📁 Project Structure

MiniSpotify/
├── app/
│   └── src/main/java/   # Kotlin source code
├── gradle/
├── build.gradle
├── settings.gradle
└── README.md

---

## 🚀 Getting Started

### Prerequisites
- Android Studio Hedgehog or later
- Android SDK API 33+
- Node.js (for running mock backend)

### ▶️ Run Mock Backend
```bash
cd spotify_backend
npm install
npm start
```

### ▶️ Run Android App
1. Open project in Android Studio
2. Connect a device or start an emulator (API 33+)
3. Click **Run**

---

## 👩‍💻 Author

**Yuelu Zhang** — MS Information Systems, Northeastern University  
[![GitHub](https://img.shields.io/badge/GitHub-YueluZhang-181717?logo=github)](https://github.com/YueluZhang)

---

## 📜 License

MIT
