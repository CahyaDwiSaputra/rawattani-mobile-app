# 🌾 RawatTani - Agricultural Mobile Application

**RawatTani** is a modern Flutter-based mobile application designed to empower local farmers and agricultural stakeholders by providing direct access to crop monitoring, plant health consultation, and agricultural market resources.

---

## 📱 Features
- **User Authentication**:
  - Secure **Registration** with role-based profile creation (Farmer / Agronomist / Buyer).
  - Modern **Login** screen with input validation, password toggle visibility, and error handling.
- **UI & Experience**:
  - Built with **Flutter Material 3** design system.
  - Tailored color palette with agricultural themes (`#1565C0` deep blue & clean neutral tones).
  - Fully responsive across Android, iOS, Web, and Desktop targets.
- **System Documentation**:
  - Complete Software Requirements Specification (**SRS**).
  - Blackbox and UI **Testing Report**.
  - System flow **Activity Diagrams**.

---

## 🏗️ Architecture & Tech Stack
- **Framework**: [Flutter](https://flutter.dev/) (SDK ^3.10.1)
- **Language**: Dart
- **Design Paradigm**: Material Design 3 (`ThemeData` with `ColorScheme.fromSeed`)
- **Target Platforms**: Android, iOS, Web, Windows

---

## 🚀 Getting Started

### Prerequisites
- [Flutter SDK](https://flutter.dev/docs/get-started/install) installed (v3.10.x or higher)
- Android Studio / VS Code with Flutter extension
- Connected physical device or emulator

### Installation & Run
1. Clone this repository:
   ```bash
   git clone https://github.com/CahyaDwiSaputra/rawattani-mobile-app.git
   cd rawattani-mobile-app
   ```
2. Install dependencies:
   ```bash
   flutter pub get
   ```
3. Run the application:
   ```bash
   flutter run
   ```

---

## 📂 Project Structure
```text
├── lib/
│   └── main.dart             # Application entrypoint & authentication UI
├── docs/
│   ├── SRS_RawatTani.pdf     # Software Requirements Specification
│   ├── Testing_RawatTani.pdf # QA Test Cases & Execution Report
│   └── activity_diagram.drawio # System activity diagrams
├── android/                  # Native Android configuration
├── ios/                      # Native iOS configuration
├── web/                      # Flutter Web wrapper
├── pubspec.yaml              # Dependencies and asset management
└── README.md
```

---

## 👥 Contributors
- **Cahya Dwi Saputra** (Lead Frontend & System Design)
- **Candra Jasmine Habibah** (QA & Testing Documentation)
