# Meet Hub

Welcome to **Meet Hub**! This application is a full-stack alternative to Zoom, offering a seamless video conferencing experience. With features like meeting creation, joining, screen sharing, and audio/video controls, Meet Hub provides a comprehensive solution for virtual meetings and collaboration.

## Features

- **Authentication:** Sign up or log in using email and password, or Google Sign-In via Firebase Authentication.
- **Create Meeting:** Start new meetings and share the link with participants.
- **Join Meeting:** Enter meetings using the link provided by the host.
- **Share Screen:** Present or demonstrate by sharing your screen during meetings.
- **Audio & Video Controls:** Mute/unmute audio and toggle video on/off during meetings.
- **Persistent User State:** Maintain user authentication state with Hooks_Riverpod for a smooth experience.
- **Data Storage:** Securely store user data with Firebase Cloud Firestore.

## Technologies Used

- **Firebase Authentication:** For user authentication and management.
- **Firebase Cloud Firestore:** For secure data storage.
- **Hooks_Riverpod:** For state management and persistence.
- **Jitsi Meet Flutter SDK:** For seamless video conferencing integration.


## Getting Started

To get started with Zoom Clone, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have Flutter installed on your machine.
3. Set up Firebase project and configure Firebase Authentication and Cloud Firestore.
4. Add necessary dependencies to `pubspec.yaml`.
5. Run `flutter pub get` to install dependencies.
6. Run the application on your preferred device/emulator.

## Usage

1. Sign up or log in to the application using your email and password or Google Sign-In.
2. Create a new meeting or join an existing meeting using the provided options.
3. During the meeting, utilize features like screen sharing, audio/video controls, etc., as needed.
4. Logout from the application when done.

## Contributing

Contributions are welcome! If you'd like to contribute to Zoom Clone, please follow these steps:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Open a pull request.

## Acknowledgements

- **Firebase**: For providing authentication and cloud services.
- **Hooks_Riverpod**: For state management.
- **Jitsi Meet Flutter SDK**: For video conferencing features.

