# Snapchat Clone UI

A sleek and modern Snapchat UI clone built with Flutter. This project demonstrates complex UI/UX designs, smooth animations, and interactive components inspired by the Snapchat mobile application.

## 📱 Features

- **Camera Interface:** An interactive central camera view.
- **Chat & Messages:** User chat layout with a structured message history UI.
- **Discover Page:** A grid-based media discovery feed.
- **Stories Layout:** Interactive stories UI with integrated video player capabilities.
- **Maps View:** Google Maps integration to display location-based snaps.
- **Cross-Platform Support:** Fully responsive and functional on iOS, Android, and Web.

## 🚀 Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install) (Dart 3 compatible)
- Android Studio / Xcode (for mobile development)
- VS Code or your preferred IDE

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/snapchat-clone.git
   cd snapchat-clone
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Google Maps Setup (Web)**
   To make the map view work properly on Flutter Web, open `web/index.html` and ensure the Google Maps JavaScript SDK is included in the `<head>` tag. You can append your API key to remove the development watermark:
   ```html
   <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY"></script>
   ```

4. **Run the application**
   ```bash
   flutter run
   ```

## 📂 Project Structure

- `lib/pages/` - Contains all the individual UI screens (Camera, Chat, Discover, Map, Stories).
- `lib/data/` - Mock data models feeding the UI components.
- `lib/theme/` - Thematic configurations, dimensions, and color constants used consistently across the app.

## 🛠 Built With

- [Flutter](https://flutter.dev/) - Google's UI toolkit for crafting natively compiled applications.
- [Google Maps Flutter](https://pub.dev/packages/google_maps_flutter) - For rendering the Map view.
- [Video Player](https://pub.dev/packages/video_player) - For rendering video stories.
- [Flutter Vector Icons](https://pub.dev/packages/flutter_vector_icons) - For scalable standard icons.

## 📸 Screenshots

![App UI](https://user-images.githubusercontent.com/16510597/105662741-13ffbd80-5f03-11eb-95f6-0f0e61772536.jpg)

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

<!-- Build Checkpoint: 61c37d -->