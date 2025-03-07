# Instagram Android Clone

<img alt="Instagram Logo" src="./assets/images/header-logo.png" width="60%">

<div>
<h4>Technologies Used</h4>
  <a href="#"><img alt="Java" src="https://img.shields.io/badge/Java-AndroidStudio-green?logo=java"></a>
  <a href="#"><img alt="Android Studio" src="https://img.shields.io/badge/Android%20Studio-2024.1.1-blue?logo=androidstudio"></a>
  <a href="#"><img alt="Parse" src="https://img.shields.io/badge/Parse-Backend-blue"></a>
</div>

## Description

A feature-rich Instagram clone built using **Java** and **Android Studio**, with **Parse** as the backend. This project replicates Instagram’s core functionality with seamless user experience and interactions.

---

## Features

- User authentication (login & signup)
- Photo sharing and real-time feed
- Infinite scrolling for improved user engagement
- Like, comment, and interact with posts
- Profile management and personalized user profiles
- Instagram-style UI for familiarity and ease of use

---

## Technologies Used

- **Java** for app logic and UI development
- **Android Studio** as the primary development environment
- **Parse** for user authentication, photo storage, and data management

---


## Instructions for Running on an Emulator

### Requirements
- Java Development Kit (JDK)
- Android Studio
- Parse backend set up

### Instructions

1. **Clone the Repository**
```bash
git clone https://github.com/yourusername/instagram-clone-app.git
cd instagram-clone-app
```

2. **Install Dependencies**
```bash
gradlew build
```

3. **Configure Backend (Parse)**
- Set up a **Parse Server** account.
- Add your **application ID**, **client key**, and **server URL** to the `ParseApplication` class.

4. **Run the Application**

- To run on the Android emulator:
```bash
./gradlew installDebug
```

5. **Launch the Emulator**

- Press “Run” in Android Studio or use the command:
```bash
adb shell am start -n com.yourapp/.MainActivity
```

---

## 🚀 Future Improvements
- Adding real-time chat functionality
- Implementing Stories with swipeable interactions
- Improving UI animations for a smoother experience



## 📜 License
This project is licensed under the **MIT License**.
