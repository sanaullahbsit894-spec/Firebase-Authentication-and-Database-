# 🔥 FireAuth — Flutter + Firebase Week 5

A Flutter application with Firebase Authentication and Cloud Firestore integration.

## Features

- Email/Password Sign Up & Login
- User profile stored in Firestore
- Real-time data sync
- Persistent auth state (auto-login)
- Clean dark UI with animations

## Setup Instructions

### Prerequisites

- Flutter SDK ≥ 3.0.0
- Firebase account
- Node.js (for FlutterFire CLI)

### Steps

1. **Clone the repo**

```bash
   git clone <your-repo-url>
   cd your-project
```

2. **Install dependencies**

```bash
   flutter pub get
```

3. **Configure Firebase**

```bash
   dart pub global activate flutterfire_cli
   flutterfire configure
```

Select your Firebase project and target platforms.

4. **Run the app**

```bash
   flutter run
```

## Firebase Services Used

| Service         | Purpose                       |
| --------------- | ----------------------------- |
| Firebase Auth   | Email/Password authentication |
| Cloud Firestore | User profile storage          |

## Project Structure

```
lib/
├── main.dart
├── models/user_model.dart
├── services/auth_service.dart
├── services/firestore_service.dart
├── screens/ (splash, login, signup, profile)
└── widgets/custom_text_field.dart
```

# 1. Get packages

flutter pub get

# 2. Configure Firebase (run once)

flutterfire configure

# 3. Run app

flutter run
