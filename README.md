# Motive

Motive is a mobile app that connects people looking to play team sports with people hosting said sporting events. This application allows users to host their events and let people nearby be informed of what sports are being played, the specific participant details about the person, and any additional items required to participate. There were a multitude of features implemented to do this. Some of the initial ones planned were not implemented, as well as new features that were initially unplanned being added to improve the user experience.

## Features

- User Authentication using Firebase
- Location-based services
- Google Maps integration
- Real-time data storage with Firebase Firestore
- Modern Material Design UI

## Technical Stack

- **Language**: Java
- **Minimum SDK**: 24 (Android 7.0)
- **Target SDK**: 34
- **Architecture**: MVVM (Model-View-ViewModel)
- **Key Dependencies**:
  - Firebase Authentication
  - Firebase Firestore
  - Google Maps SDK
  - AndroidX Components
  - ViewBinding
  - Lifecycle Components

## Prerequisites

- Android Studio (latest version)
- Google Maps API Key
- Firebase Project setup
- Google Services configuration file (`google-services.json`)

## Setup Instructions

1. Clone the repository
2. Open the project in Android Studio
3. Place your `google-services.json` file in the `app` directory
4. Sync the project with Gradle files
5. Build and run the application

## Project Structure

```
app/
├── src/
│   └── main/
│       ├── java/com/motive/motive/
│       │   ├── Activities/     # UI components
│       │   ├── Models/         # Data models
│       │   ├── data/          # Data management
│       │   └── FirebaseUtil.java
│       └── res/               # Resources
└── build.gradle.kts          # App-level build configuration
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Firebase for authentication and database services
- Google Maps Platform for mapping features
- AndroidX for modern Android development components
