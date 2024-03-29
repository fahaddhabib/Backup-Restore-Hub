# Backup Hub - Android Backup App

![App Screenshots](https://github.com/fahaddhabib/Backup-Restore-Hub/blob/main/assets/featured.png)

## Overview

Backup Hub is an Android application designed to facilitate easy backup and restore functionalities for various data types, including calls, calendar events, SMS messages, and contacts. The app leverages Google Drive for secure cloud storage and provides a user-friendly interface for managing backups.

[![Google Play Store](https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png)](https://play.google.com/store/search?q=backup%20hub&c=apps&hl=en&gl=US)


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

- **Programming Language:**  Kotlin
- **Android Architecture:**  MVVM (Model-View-ViewModel)
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

## Project Details

This project was developed with a focus on scalability, maintainability, and user-centric design. The architecture follows the MVVM pattern, separating concerns and facilitating testability and extensibility. By leveraging modern Android development practices and industry-standard libraries and tools, Backup Hub delivers a high-quality user experience while maintaining code quality and robustness.

## Future Enhancements

While the current version of Backup Hub offers a comprehensive set of features and functionalities, there is always room for improvement. Some potential enhancements for future iterations of the app include:
    Enhanced Backup Options:
Introduce support for backing up additional data types, such as app data and media files, to provide users with a more comprehensive backup solution.
    Improved User Feedback Mechanisms:
Implement more advanced user feedback mechanisms, such as sentiment analysis and user behavior tracking, to gather actionable insights for further     refining the app.
    Enhanced Security Features:
Explore advanced security features, such as end-to-end encryption and biometric authentication, to further enhance the security and privacy of user data.
    Cross-Platform Compatibility:
Investigate opportunities for expanding Backup Hub's compatibility to other platforms, such as iOS, to cater to a broader audience of users.

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

---
## Acknowledgments
Third-Party Libraries and Frameworks

    User Messaging Platform by Google: Used for user consent.
        License: Apache License 2.0

    Google Play Services Ads: Integrated for displaying ads in the application.
        License: Google APIs Terms of Service

    Android Lifecycle Components: Utilized for lifecycle management in Android applications.
        License: Apache License 2.0

    Billing Client Library for Android: Integrated for in-app purchases functionality.
        License: Apache License 2.0

    Work Manager by Google: Used for managing background tasks in the application.
        License: Apache License 2.0

    Firebase SDK: Integrated for analytics, crash reporting, and messaging functionalities.
        License: Apache License 2.0

    In-App Review Library: Utilized for prompting users to leave reviews within the app.
        License: Apache License 2.0

    Legacy Support Library: Used for providing backward compatibility support.
        License: Apache License 2.0

    Glide Image Loading Library: Integrated for efficient image loading and caching.
        License: BSD, part MIT and Apache 2.0

    Kotlin Coroutines: Used for asynchronous programming.
        License: Apache License 2.0

    Android DataStore: Used as a replacement for SharedPreferences.
        License: Apache License 2.0

    Material Dialogs: Utilized for implementing bottom sheets in the application.
        License: Apache License 2.0

    Google API Client for Android and Google Drive API Services: Integrated for Google Drive integration.
        License: Apache License 2.0

    Navigation Component: Utilized for navigation within the application.
        License: Apache License 2.0

Additional Resources

    JUnit and Espresso: Used for testing purposes.
        License: Eclipse Public License - v 1.0

## Note

This project is intended for portfolio purposes only and is not publicly available. If you have any inquiries or would like to discuss potential collaboration opportunities, please feel free to reach out via iamfahad1296@gmail.com. Thank you for your interest in Backup Hub!

## License

This project is licensed under the [MIT License](LICENSE).

---
