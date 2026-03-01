# 🎨 Poster App

A simple Flutter application that demonstrates the basic structure of a Flutter app using `MaterialApp`, `StatefulWidget`, and `Scaffold`.

---

## 📚 About

This application is designed to help users understand:

- Application entry point
- Widget tree structure
- Difference between stateful and stateless widgets
- Basic UI layout using `Scaffold`
- Theme configuration using `ColorScheme`

---

## ✨ Features

- Material Design user interface
- AppBar with title
- Centered welcome message
- Clean and scalable project structure
- Ready for future development

---

## 📁 Project Structure

```
lib/
│
├── main.dart
└── Pages/
    └── home.dart
```

| File | Description |
|------|-------------|
| `main.dart` | App entry point, `MaterialApp` initialization, theme configuration, sets `HomePage` as default screen |
| `home.dart` | `HomePage` stateful widget with an app bar and centered body text |

---

## 🧠 Concepts Covered

| Concept | Description |
|---------|-------------|
| `runApp()` | Application entry point |
| `MaterialApp` | Root widget for Material apps |
| `ThemeData` | App-wide theme configuration |
| `ColorScheme.fromSeed` | Seed-based color scheme generation |
| `StatefulWidget` | Widget with mutable state |
| `Scaffold` | Basic Material Design layout structure |
| Widget Lifecycle | Basics of widget creation and updates |
| `BuildContext` | Location of a widget in the widget tree |

---

## 🚀 Getting Started

### Prerequisites

Before you begin, make sure you have:

- [Flutter](https://flutter.dev/docs/get-started/install) installed
- A compatible IDE (VS Code or Android Studio)
- An emulator or physical device connected

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/your-username/poster-app.git
```

**2. Navigate to the project folder**

```bash
cd poster-app
```

**3. Install dependencies**

```bash
flutter pub get
```

**4. Run the app**

```bash
flutter run
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Flutter | UI framework |
| Dart | Programming language |
| Material Design | Design system |

---

## 🔮 Future Improvements

- [ ] Navigation between multiple screens
- [ ] State management (Provider / Riverpod / Bloc)
- [ ] Poster creation screen
- [ ] Image upload feature
- [ ] Firebase backend integration
- [ ] Clean architecture implementation

---

## 👤 Author

**Akanshu Jamwal**
Flutter Developer

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
