# 🚀 Firebase Authentication App

## 🌟 Overview
This project is a Firebase Authentication Android application that provides users with the ability to:
- ✅ Register with email and password.
- 🔑 Log in using email and password.
- 📧 Log in using Google Sign-In.
- 🔄 Reset their password via email.
- 📱 Navigate between different fragments using a bottom navigation bar.

The application is built using **Java**, **Firebase Authentication**, and follows modern Android development practices.

---

## 🎯 Features
### 1. 📝 User Registration
- Allows new users to register with their email and password.
- Sends an email verification link to the registered email address.

### 2. 🔐 Email and Password Login
- Authenticates registered users with their email and password.
- Verifies email addresses before allowing access to the app.

### 3. 🌐 Google Sign-In
- Supports logging in using a Google account.
- Integrates with Firebase Authentication for seamless Google login.

### 4. 🔓 Password Reset
- Enables users to reset their passwords by sending an email with a reset link.

### 5. 🧭 Bottom Navigation
- Provides navigation between three fragments:
  - **🏠 HomeFragment**: Displays the home screen.
  - **📜 HistoryFragment**: Shows the user's activity history.
  - **👤 ProfileFragment**: Displays user profile details.

---

## 💻 Technologies Used
- **Language**: Java
- **Firebase Services**:
  - Firebase Authentication
  - Google Sign-In Integration
- **UI/UX**: Material Design Components
- **Navigation**: BottomNavigationView with Fragment Transactions
- **View Binding**: Used for efficient and type-safe view access

---

## 📂 Folder Structure
```
├── com.example.firebase
│   ├── Login.java           # Handles user login functionality
│   ├── Register.java        # Handles user registration
│   ├── MainActivity.java    # Hosts the bottom navigation and fragments
│   ├── HomeFragment.java    # Fragment for home screen
│   ├── HistoryFragment.java # Fragment for user activity history
│   ├── ProfileFragment.java # Fragment for user profile details
└── res
    ├── layout               # Contains XML layout files
    └── values               # Contains resource files (strings, colors, themes)
```

---

## 🛠️ Setup Instructions

### Prerequisites
1. ⚙️ Android Studio installed on your machine.
2. 🔥 A Firebase project set up in the [Firebase Console](https://console.firebase.google.com/).
3. 📂 Add the `google-services.json` file from Firebase to the `app/` directory.

### Steps
1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```

2. Open the project in Android Studio.

3. Sync Gradle:
   - Open the `build.gradle` file in the `app/` directory and ensure dependencies for Firebase and Google Sign-In are included:
     ```groovy
     implementation 'com.google.firebase:firebase-auth:21.4.0'
     implementation 'com.google.android.gms:play-services-auth:20.6.0'
     ```
   - Sync Gradle to download dependencies.

4. Update Firebase Configuration:
   - Add the `default_web_client_id` in the `strings.xml` file:
     ```xml
     <string name="default_web_client_id">YOUR_WEB_CLIENT_ID</string>
     ```

5. Build and run the app on an emulator or physical device.

---

## 📸 Screenshots


---

## 📦 Release
The latest version of the app can be downloaded from [🚀 Firebase Google Authentication v1.0 Release](https://github.com/AbhishekVabilisetty/Firebase_google_authentication/releases/tag/v1.0).


