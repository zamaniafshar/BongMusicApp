## BongMusic - A Feature-Rich Music Player

BongMusic is a beautifully crafted, high-performance music player application built with Flutter. It offers a seamless and engaging user experience for enjoying your favorite music, both online and offline.

## ✨ Key Features

- **Cross-Platform:** Single codebase for both Android and iOS, thanks to Flutter.
- **Rich Audio & Video Playback:** Supports various audio formats with background playback capabilities powered by `just_audio` and `audio_service`.
- **Offline Storage:** Save your favorite tracks and playlists for offline listening.
- **Playlist Management:** Create, edit, and manage your personal music playlists.
- **Music Discovery:** Explore new music, artists, and albums.
- **Artist Profiles:** View dedicated pages for your favorite artists.
- **Liked Songs & Recents:** Keep a list of your favorite tracks and quickly access recently played songs.
- **Social Features:** Create and share posts with the community.
- **Upcoming Events:** Stay informed about upcoming music events.
- **Personalization:** Customize your profile and experience.
- **Multi-Language & Multi-Theme:** Use the app in your preferred language and switch between light and dark modes.
- **Stunning & Animated UI:** A visually appealing and responsive interface built with a host of animation and UI libraries.
- **State Management with BLoC:** Predictable and scalable state management using the BLoC (Business Logic Component) pattern.
- **Push Notifications:** Stay updated with Firebase-powered push notifications.
- **Feature-Driven Architecture:** A clean and maintainable codebase organized by application features.
- **Advanced Features:** Includes functionalities like palette generation from album art, cached network images for performance, and more.


## 🏗️ Architecture

The application follows a **feature-driven architecture**, which keeps the codebase organized, scalable, and easy to maintain. The core business logic is decoupled from the UI using the **BLoC pattern** for state management.

- **`lib/features`**: Contains the primary application features (e.g., player, playlists, search).
- **`lib/common`**: Holds shared widgets, constants, and utilities used across multiple features.
- **`lib/config`**: Manages application-level configurations like routing (`go_router`) and themes.
- **`lib/main.dart`**: The entry point of the application, responsible for initializing services and setting up the root widget.

Dependency injection is handled by `get_it`, which provides a clean way to access services and BLoCs throughout the app.

## 🛠️ Tools & Technologies

- **Framework:** [Flutter](https://flutter.dev/)
- **State Management:** [flutter_bloc](https://pub.dev/packages/flutter_bloc)
- **Routing:** [go_router](https://pub.dev/packages/go_router)
- **Audio:** [just_audio](https://pub.dev/packages/just_audio), [audio_service](https://pub.dev/packages/audio_service)
- **Database:** [Hive](https://pub.dev/packages/hive)
- **Networking:** [http](https://pub.dev/packages/http), [cached_network_image](https://pub.dev/packages/cached_network_image)
- **Push Notifications:** [Firebase Messaging](https://pub.dev/packages/firebase_messaging)
- **Dependency Injection:** [get_it](https://pub.dev/packages/get_it)
- **Functional Programming:** [fpdart](https://pub.dev/packages/fpdart)





## 📸 Screenshots

| | |
|:-------------------------:|:-------------------------:|
| <img src="resources/1.jpg" width="400"> | <img src="resources/2.jpg" width="400"> |
| <img src="resources/3.jpg" width="400"> | <img src="resources/4.jpg" width="400"> |
| <img src="resources/5.jpg" width="400"> | <img src="resources/6.jpg" width="400"> |
| <img src="resources/7.jpg" width="400"> | <img src="resources/8.jpg" width="400"> |
| <img src="resources/9.jpg" width="400"> | <img src="resources/10.jpg" width="400"> |
| <img src="resources/11.jpg" width="400"> | <img src="resources/12.jpg" width="400"> |
| <img src="resources/13.jpg" width="400"> | <img src="resources/14.jpg" width="400"> |
| <img src="resources/15.jpg" width="400"> | <img src="resources/16.jpg" width="400"> |
| <img src="resources/17.jpg" width="400"> | <img src="resources/18.jpg" width="400"> |

