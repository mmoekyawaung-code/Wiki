# 🌐 Moe Kyaw Aung — Developer Wiki

> *Senior Android Developer · Tachileik, Myanmar 🇲🇲 · Kotlin · Jetpack Compose · Firebase*

---

## 🗂️ Table of Contents

| Section | Description |
|---------|-------------|
| [About Me](#about-me) | Background, education, and focus areas |
| [Tech Stack](#tech-stack) | Languages, frameworks, and tools |
| [Projects](#projects) | Featured work and open-source contributions |
| [Android Architecture](#android-architecture) | How I structure Android apps |
| [GitHub Accounts](#github-accounts) | My multi-account GitHub presence |
| [Dev Education](#dev-education) | Myanmar developer education content |
| [Contact](#contact) | How to reach me |

---

## 👨‍💻 About Me

I am a **Senior Android Developer** with **5+ years** of professional experience building production-quality mobile applications. Based in **Tachileik, Myanmar**, I specialize in Kotlin-first Android development using modern Jetpack libraries.

Beyond Android, I work with **Three.js** for 3D web experiences and integrate AI capabilities via the **Gemini API** into tools and educational apps.

### 🎓 Education

- **B.Sc. Computer Science** — University of Computer Studies, Pathein
- **B.A. English** — Pathein Distance University

### 🌍 Language Skills

- 🇲🇲 Myanmar (Native)
- 🇬🇧 English (Proficient)

---

## ⚙️ Tech Stack

### Android Core
```
Kotlin · Jetpack Compose · Android SDK
Coroutines · Flow · StateFlow
Hilt / Dagger (DI) · Room Database
Retrofit · OkHttp · Coil
Navigation Component · WorkManager
```

### Architecture
```
MVVM (Model–View–ViewModel)
Clean Architecture (Domain / Data / Presentation)
Repository Pattern · Use Cases
```

### Backend & Cloud
```
Firebase (Firestore · Realtime DB · Auth · Storage)
Firebase Cloud Functions · FCM Push Notifications
```

### Web & AI
```
JavaScript (ES6+) · HTML5 · CSS3
Three.js · WebGL · Web Speech API
Gemini API (2.0 Flash) · Google AI Studio
React · GitHub Pages
```

### DevOps & Tools
```
Git · GitHub · GitHub Actions
Android Studio · VS Code
GitHub Pages · GitHub Wiki
```

---

## 🚀 Projects

### 📱 Android

| Project | Description | Stack |
|---------|-------------|-------|
| **Kotlin Compose Showcase** | Production MVVM + Clean Architecture demo | Kotlin, Compose, Firebase, Hilt |
| **Myanmar Dev App** | Developer tools for Burmese-language learning | Kotlin, Compose, Room |

### 🌐 Web & AI

| Project | Description | Stack |
|---------|-------------|-------|
| **3D Rubik's Cube** | Fully interactive WebGL Rubik's Cube game | Three.js, JavaScript |
| **AI Multilingual Translator** | 19-language voice + text translator | Gemini API, Web Speech API |
| **CodeVerter** | Code conversion tool via Gemini 2.0 Flash | Gemini API, Vanilla JS |
| **Life in Weeks** | Bilingual life visualization app | React, EN/MM bilingual |
| **Love Counter** | Bilingual relationship milestone tracker | React, theme switcher |
| **Myanmar Cities Directory** | Interactive Myanmar city reference app | HTML/JS |
| **Pure CSS Animation Suite** | Multi-scene CSS-only animation showcase | Pure CSS |

### 🎓 Education

| Project | Description |
|---------|-------------|
| **Myanmar Dev Learning Portal** | Bilingual portal with CSS libraries, PDF mind maps, GitHub guide |
| **100 Days of Code** | Structured coding challenge with daily logs |
| **GitHub Mobile Guide (Burmese)** | Step-by-step GitHub usage guide in Myanmar language |

---

## 🏗️ Android Architecture

I follow **Clean Architecture** with MVVM across all serious Android projects:

```
📦 app/
├── 📁 data/
│   ├── remote/         # API services, DTOs
│   ├── local/          # Room DAOs, entities
│   └── repository/     # Repository implementations
├── 📁 domain/
│   ├── model/          # Domain models
│   ├── repository/     # Repository interfaces
│   └── usecase/        # Business logic use cases
└── 📁 presentation/
    ├── ui/             # Composable screens
    ├── viewmodel/      # ViewModels (Hilt injected)
    └── state/          # UI state classes
```

**Key principles I follow:**
- Unidirectional data flow (UDF)
- Single source of truth (Repository layer)
- Reactive streams with `StateFlow` / `SharedFlow`
- Constructor injection via Hilt
- Composable functions remain stateless (hoisting state up)

---

## 🐙 GitHub Accounts

I maintain multiple GitHub accounts for different focus areas:

| Account | Focus |
|---------|-------|
| `mmoekyawaung-code` | Primary — Android & Web projects |
| `moekyawaung-tech` | Tech experiments & tools |
| `Moe-kyaw-Aung-microsoft` | Microsoft-themed dev content |
| `moekyawaung-graduate` | Academic & graduation portfolio |
| `moekyawaungmka2026-cyber` | Cybersecurity learning |
| `moekyawaungmka2034-coder` | Long-term coding challenges |

---

## 📚 Dev Education

Creating quality developer education content in Myanmar language is a core mission of mine. Resources I've built:

- 🇲🇲 **GitHub Mobile Usage Guide** — Complete guide to using GitHub on mobile in Burmese
- 📄 **PDF Mind Maps** — Visual references on Programming Basics and MVP Design Pattern
- 🌐 **Interactive Learning Portal** — Combining tutorials, CSS showcases, and GitHub guides
- 💬 **Bilingual Apps** — All personal tools are built with English/Myanmar language support

---

## 📬 Contact

| Channel | Details |
|---------|---------|
| 📧 Email | moekyawaung@engineer.com |
| 🐙 GitHub | [@mmoekyawaung-code](https://github.com/mmoekyawaung-code) |
| 📍 Location | Tachileik, Shan State, Myanmar 🇲🇲 |

---

<div align="center">

*"Code is how I speak to machines. Kotlin is my mother tongue."*

**⚡ Built with ♥ from Myanmar**

</div>
