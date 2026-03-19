<div align="center">

  # 🛡️ EmpowerMe
  **Your Safety, Our Priority**

  ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
  ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
  ![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

  *A women's personal safety companion app — stay connected, protected, and empowered.*

  [View Screenshots](#screenshots) · [Getting Started](#getting-started) · [Features](#features)

</div>

---

## 🌍 Why We Built This

Women's safety remains a critical concern in today's world. According to the National Crime Records Bureau, crimes against women in India have been consistently rising year over year. Many existing safety solutions are either too complex, require internet at all times, or are simply not built with the end user in mind.

**EmpowerMe** was built to address this gap — a simple, fast, and reliable safety app that a woman can use in seconds when she needs help the most. As engineering students at RAIT, we wanted to build something that goes beyond academics and creates a real-world impact.

---

## 📖 About

EmpowerMe is a cross-platform mobile application built with Flutter and Firebase, designed to help women stay safe in emergency situations. The app provides instant SOS alerts, live location sharing, fake call simulation, and a trusted contacts system — all wrapped in a clean, intuitive interface.

> 2nd Year Mini Project — Ramrao Adik Institute of Technology (2025)

---

## 📱 Screenshots

<p align="center">
  <img src="screenshots/splash.png" width="160"/>
  &nbsp;
  <img src="screenshots/signup.png" width="160"/>
  &nbsp;
  <img src="screenshots/home.png" width="160"/>
  &nbsp;
  <img src="screenshots/fakecall.png" width="160"/>
</p>
<p align="center">
  <img src="screenshots/add_contact.png" width="160"/>
  &nbsp;
  <img src="screenshots/forum.png" width="160"/>
  &nbsp;
  <img src="screenshots/profile.png" width="160"/>
</p>

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🔐 Authentication | Secure sign up and login via Firebase Auth |
| 🆘 SOS Alert | Instantly notify trusted contacts in an emergency |
| 📍 Live Location | Share real-time location with emergency contacts |
| 📞 Fake Call | Trigger a simulated call to escape uncomfortable situations |
| 👥 Emergency Contacts | Add and manage trusted contacts |
| 💬 Community Forum | Connect and share safety tips with other users |
| 👤 User Profile | Manage personal info, notifications and privacy settings |

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| Flutter | Cross-platform mobile & web UI |
| Dart | Programming language |
| Firebase Auth | User authentication |
| Firebase Firestore | Real-time database |
| Google Maps API | Live location sharing |

---

## 🚀 Getting Started

### Prerequisites
- Flutter SDK (3.0+)
- Dart SDK
- Android Studio / VS Code
- Firebase project setup

### Installation

1. Clone the repository
```bash
git clone https://github.com/NehaKadam26/EmpowerMe.git
cd EmpowerMe
```

2. Install dependencies
```bash
flutter pub get
```

3. Set up Firebase
   - Create a project at [firebase.google.com](https://firebase.google.com)
   - Add `google-services.json` to `android/app/`
   - Add `GoogleService-Info.plist` to `ios/Runner/`
   - Enable Email/Password authentication

4. Run the app
```bash
flutter run
```

---

## 📁 Project Structure
```
lib/
├── main.dart
├── firebase_options.dart
│
├── auth/
│   ├── loginP_page.dart
│   └── signup_page.dart
│
├── screens/
│   ├── first_page.dart
│   ├── community_forum.dart
│   ├── profile_page.dart
│   ├── edit_profile_page.dart
│   └── feature_cards.dart
│
├── safety/
│   ├── sos_alert.dart
│   ├── sos_service.dart
│   ├── fakecallsscreen.dart
│   └── getuserlocation.dart
│
├── contacts/
│   ├── addclose_people.dart
│   └── close_people_screen.dart
│
└── settings/
    ├── notifications_page.dart
    ├── privacy_security_page.dart
    ├── help_support_page.dart
    └── about_page.dart
```

---

## 👩‍💻 Team

| Name | GitHub |
|------|--------|
| Neha Kadam | [@NehaKadam26](https://github.com/NehaKadam26) |
| Ishita Sharma | — |
| Dilkush Janwa | [@dilkush-31](https://github.com/dilkush-31) |
| Hitarth Khot | [@hitarthruns](https://github.com/hitarthruns) |

---

<div align="center">
  💡 Built by students, inspired by real world problems
</div>
