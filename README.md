# ComicStoryApp

## Project Overview
ComicStoryApp is a comic story reading application designed to provide an immersive experience for comic lovers. The app features two primary modules: Admin and User, making it easy to manage comic stories while allowing users to enjoy reading comics effortlessly.

## Features
- **User Module**: Allows users to register, login, browse, and read comic stories.
- **Admin Module**: Enables administrators to manage comic stories, including adding, updating, or deleting stories.
- **User Profiles**: Personalized user profiles that save preferences and reading history.
- **Search Functionality**: Efficient search options to find comics by title or genre.
- **Offline Reading**: Option to download comics for offline reading access.
- **Push Notifications**: Get notified about new comics or updates.

## Tech Stack
- **Frontend**: Kotlin for Android development
- **Backend**: Firebase for database management and authentication
- **Architecture**: MVVM (Model-View-ViewModel)
- **Libraries Used**: Retrofit, Glide, Firebase UI, and others.

## Installation Guide
1. Clone the repository:
   ```bash
   git clone https://github.com/Hackershimul07Ami/ComicStoryApp.git
   ```
2. Open the project in Android Studio.
3. Sync the project with Gradle files to ensure all libraries are properly included.
4. Set up Firebase by following the official [Firebase documentation](https://firebase.google.com/docs/android/setup).
5. Connect your app to Firebase by adding the `google-services.json` file to the app-level directory.
6. Run the application on an emulator or device.

## Folder Structure
```
ComicStoryApp/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/
│   │   │   │   └── com/example/comicstoryapp/
│   │   │   ├── res/
│   │   │   │   ├── layout/
│   │   │   │   ├── drawable/
│   │   │   │   ├── values/
│   │   │   │   └── ...
│   │   │   └── AndroidManifest.xml
│   │   └── test/
│   └── build.gradle
├── build.gradle
└── settings.gradle
```

Feel free to explore the source code and contribute to the project!