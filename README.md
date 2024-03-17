# Backup Hub - Android Backup App

![App Screenshots](https://github.com/fahaddhabib/Backup-Restore-Hub/blob/main/assets/featured.png)

## Overview

Backup Hub is an Android application designed to facilitate easy backup and restore functionalities for various data types, including calls, calendar events, SMS messages, and contacts. The app leverages Google Drive for secure cloud storage and provides a user-friendly interface for managing backups.l

## Features

1. **Data Types Supported:**
   - Call Logs Backup and Restore
   - Calendar Events Backup and Restore
   - SMS Messages Backup and Restore
   - Contacts Backup and Restore

2. **Google Drive Integration:**
   - Utilizes Google Drive API for uploading and retrieving backup files securely.

3. **Dark Mode:**
   - Allows users to toggle between light and dark modes for a personalized experience.

4. **User Authentication:**
   - Implements Google Sign-In for user authentication and personalized services.

5. **Premium Subscription:**
   - Offers premium features for subscribed users, enhancing the backup experience.

6. **Settings:**
   - Provides configurable settings, including backup paths, language preferences, and dark mode.

7. **In-App Review:**
   - Encourages users to leave reviews by integrating an in-app review flow.

## Technologies Used

- **Programming Language:** Kotlin
- **Android Architecture:** MVVM (Model-View-ViewModel)
- **Libraries/Tools:**
  - Android Jetpack Components (ViewModel, LiveData, etc.)
  - Google Drive API
  - Firebase Analytics
  - Firebase Crashlytics
  - Material Design Components
  - Google Sign-In
  - Coroutines for asynchronous programming
  - Android DataStore for preferences
  - ReviewManager API for in-app reviews

## Instructions for Running the Project

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/fahaddhabib/backup-hub-android-backup-app.git
   cd backup-hub-android-backup-app
   ```

2. **Replace API Keys:**
   - Replace the following placeholders in the code with your own API keys or IDs:
     - `google-services.json`: Add your own Google services JSON file.
     - `<YOUR_DRIVE_CLIENT_ID>`: Replace with your Google Drive API client ID.
     - `<YOUR_FIREBASE_API_KEY>`: Replace with your Firebase API key.
     - `<YOUR_INTERSTITIAL_AD_UNIT_ID>`: Replace with your AdMob interstitial ad unit ID.
     - `<YOUR_REWARDED_AD_UNIT_ID>`: Replace with your AdMob rewarded ad unit ID.

3. **Build and Run:**
   - Build and run the project using Android Studio or Gradle.

4. **Testing:**
   - Run unit tests and UI tests using the appropriate Gradle commands.

5. **Contribute:**
   - Feel free to contribute to the project by opening issues or creating pull requests.

## Screenshots

<p float="left">
  <img src="https://github.com/fahaddhabib/Backup-Restore-Hub/blob/main/assets/ss1.png" width="200" />
  <img src="https://github.com/fahaddhabib/Backup-Restore-Hub/blob/main/assets/ss2.jpg" width="200" />
  <img src="https://github.com/fahaddhabib/Backup-Restore-Hub/blob/main/assets/ss3.jpg" width="200" />
  <img src="https://github.com/fahaddhabib/Backup-Restore-Hub/blob/main/assets/ss4.png" width="200" />
  <img src="https://github.com/fahaddhabib/Backup-Restore-Hub/blob/main/assets/ss5.png" width="200" />
  <img src="https://github.com/fahaddhabib/Backup-Restore-Hub/blob/main/assets/ss6.jpg" width="200" />
</p>

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to explore, use, and contribute to Backup Hub! If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request. Happy coding!
```
