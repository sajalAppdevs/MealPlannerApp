# Meal Tracker App

A beautiful and feature-rich meal tracking application built with Flutter for Android and iOS devices. The app helps users track their daily meals with an intuitive interface, Firebase authentication, and cloud storage capabilities.

## Features

### Authentication & User Management
- Email and password authentication using Firebase
- User profile management
- Secure password update functionality
- Email address modification capability

### Meal Management
- Add, edit, and delete meals
- Categorize meals (Breakfast, Lunch, Dinner, Snacks, Dessert)
- Track meals with timestamps
- Weekly and monthly meal tracking using Table Calendar

### UI/UX
- Engaging onboarding screen with animations
- Responsive and adaptive UI design
- Theme customization options:
  - Light mode
  - Dark mode
  - System default theme
- Beautiful and smooth transitions
- Google Fonts integration
- Toast notifications for user feedback

### Data Management
- Cloud Firestore database integration
- Real-time data synchronization
- Secure data storage and retrieval

## Tech Stack

- **Frontend Framework**: Flutter
- **Backend Service**: Firebase
  - Authentication
  - Cloud Firestore
- **State Management**: Provider
- **UI Components**:
  - Table Calendar
  - Animated Text Kit
  - Google Fonts
  - Lottie Animations

## Getting Started

### Prerequisites

- Flutter SDK
- Android Studio / VS Code
- Firebase account
- Git

### Installation

1. Clone the repository
```bash
git clone [repository-url]
cd MealPlannerApp
```

2. Install dependencies
```bash
flutter pub get
```

3. Configure Firebase
- Create a new Firebase project
- Add Android/iOS apps in Firebase console
- Download and add the configuration files
  - `google-services.json` for Android
  - `GoogleService-Info.plist` for iOS

4. Run the app
```bash
flutter run
```

## Screenshots

![Preview](meal_app.png)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.