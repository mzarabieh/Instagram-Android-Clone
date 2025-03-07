# instagram-clone-app


<div>
<h4>Language options</h4>
  <a href="https://github.com/hernanhawryluk/instagram-clone-app/blob/main/README.es.md"><img alt="Cambiar idioma al español" src="https://img.shields.io/badge/idioma-español-yellow.svg"></a>
  <a href="#"><img alt="Visitor Badge" src="https://visitor-badge.laobi.icu/badge?page_id=hernanhawryluk.instagram-clone-app"></a>
</div>
<div>
  <h3>Technologies used</h3>
  <a href="#"><img alt="React Native" src="https://img.shields.io/badge/React%20Native-0.72.6-blue?logo=react"></a>
  <a href="#"><img alt="Expo" src="https://img.shields.io/badge/Expo-49.0.15-blue?logo=expo"></a>
  <a href="#"><img alt="Firebase" src="https://img.shields.io/badge/Firebase-10.5.2-blue?logo=firebase"></a>
</div>

## Description

Fully functional Instagram replica built in React Native, showcasing my skills as a mobile app developer. Explore the features and functionality of Instagram in this project.

## Features

- User authentication.
- Discover, search, and share content and users.
- Create, edit, and share posts, stories, and reels.
- Easy image uploads from your device or camera.
- Social interaction: like, comment, and follow other users.
- Personalized user profiles with information and a list of posts.
- Real-time notifications and chat to keep you connected.

## Technologies Used

- Expo.
- React Native.
- Firebase (authentication and cloud storage).

## Download the App for Android devices

- [![Download APK for Android](https://img.shields.io/badge/Google%20Drive-instagram--clone--app.apk-blue?logo=googledrive)](https://drive.google.com/file/d/15ahphglkz-yoSmbGTq201YoZ-xWay-pn/view?usp=drive_link)



## Instructions for Running on an Emulator:

### Requirements:

    - Node.js.
    -	Android Studio (for Android).
    -	Xcode (for iOS).
    -	Firebase.

### Instructions:

1. Set Up Firebase:

   - Create a project on Firebase and enable Authentication, Firestore, and Storage.
   - Apply the Firebase and Firestore rules located in the folders `/src/services/firebase.rules` y `firestore.rules`.
   - Add your Firebase credentials to the file `/src/services/firebaseConfig.js`.
   - Rename `/src/services/firebaseConfig.js` to `/src/services/firebase.js`.

2. **Download the repository**

```bash
git clone https://github.com/hernanhawryluk/instagram-clone-app
```

3. **Navigate to the project directory**

```bash
cd instagram-clone-app
```

4. **Install dependencies**

```bash
npm install
```

5. **Create a Developer Build**

- To run on the iOS emulator:

```bash
npx expo run:ios
```

- To run on the Android emulator:

```bash
npx expo run:android
```

6. **Start the application**

```bash
npm start
```

