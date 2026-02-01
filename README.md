<div align="center">

# 💰 Expense Tracker

### Smart Personal Finance Management

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev/)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com/)
[![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev/)

</div>

---

## 📋 Overview

A modern, cloud-powered mobile application for tracking and managing daily expenses with real-time synchronization. Built with Flutter and Firebase to deliver a seamless cross-platform experience.

### 🎯 What Makes It Special

- **Real-Time Sync**: All your expenses are instantly backed up to Firebase cloud storage
- **Cross-Platform Ready**: Built with Flutter for Android, iOS, and more
- **User-Friendly**: Minimalist design focused on simplicity and efficiency
- **Fast & Reliable**: Optimized performance with smooth animations
- **Secure**: Firebase authentication and secure data storage

## ✨ Key Features

### 💼 Core Functionality
- 📊 **Expense Management** - Add, view, and organize expenses with ease
- 🏷️ **Smart Categorization** - Multiple categories: Food, Transport, Shopping, Bills, Entertainment, and more
- 💰 **Amount Tracking** - Record precise amounts with currency support
- 📝 **Descriptions** - Add notes and details to each expense

### 📆 Organization & Navigation
- 📅 **Monthly Tracking** - Navigate through expense history month by month
- 🔍 **Date-Based Sorting** - Expenses organized chronologically for easy review
- 🗂️ **Category Filters** - View expenses by specific categories

### ☁️ Cloud & Performance
- ☁️ **Real-Time Sync** - Automatic synchronization with Firebase Firestore
- 📱 **Offline Support** - View cached expenses even without internet
- ⚡ **Fast Loading** - Optimized database queries for instant access
- 🎨 **Modern UI** - Beautiful interface with Google Fonts typography

## � Download & Install

<div align="center">

[![Download APK](https://img.shields.io/badge/Download-APK-3DDC84?style=for-the-badge&logo=android&logoColor=white)](app-release.apk)

**[📱 Download app-release.apk](app-release.apk)**

</div>

### Installation Steps
1. Download the `app-release.apk` file
2. Enable "Install from Unknown Sources" in your Android settings
3. Open the APK file and tap "Install"
4. Launch the app and start tracking your expenses!

> ⚠️ **Note:** This app requires Android 5.0 (Lollipop) or higher

## �📸 Screenshots

<div align="center">
  <img src="screenshots/Logo_page.jpeg" width="200" alt="Splash Screen" />
  <img src="screenshots/Home.jpeg" width="200" alt="Home Screen" />
  <img src="screenshots/Add_Expense.jpeg" width="200" alt="Add Expense" />
  <img src="screenshots/Insert_data.jpeg" width="200" alt="Insert Data" />
</div>

## 🛠️ Tech Stack

| Technology | Version | Purpose |
|-----------|---------|---------|
| **Flutter** | 3.10.7+ | Cross-platform UI framework for beautiful native apps |
| **Firebase Firestore** | 6.1.2 | Cloud NoSQL database for real-time data storage |
| **Firebase Core** | 4.4.0 | Firebase SDK initialization and configuration |
| **Google Fonts** | 6.1.0 | Custom typography and beautiful font styling |
| **Intl** | 0.20.2 | Date formatting and internationalization |
| **Dart** | 3.0+ | Modern, fast programming language |

## 📂 Project Structure

```
lib/
├── main.dart                    # App entry point & initialization
├── firebase_options.dart        # Firebase configuration file
├── models/
│   └── expense.dart            # Expense data model
├── screens/
│   ├── SplaceScreen.dart       # Splash screen UI
│   ├── add_expense.dart        # Add/Edit expense screen
│   └── expense_card.dart       # Expense card widget
└── services/
    └── firestore_services.dart # Firebase CRUD operations
```

## 🚀 Quick Start

### Installation & Setup

```bash
# Clone repository
git clone https://github.com/Param-vadher/flutter_application_1.git
cd flutter_application_1

# Install dependencies
flutter pub get

# Configure Firebase
flutterfire configure

# Run app
flutter run
```

### Prerequisites
- ✅ Flutter SDK 3.10.7 or higher
- ✅ Dart SDK 3.0 or higher
- ✅ Firebase account (free tier works)
- ✅ Android Studio or VS Code with Flutter extensions
- ✅ Android device or emulator (Android 5.0+)

### Firebase Setup
1. Create a project at [Firebase Console](https://console.firebase.google.com/)
2. Enable Cloud Firestore Database
3. Download configuration files:
   - **Android**: `google-services.json` → Place in `android/app/`
   - **iOS**: `GoogleService-Info.plist` → Place in `ios/Runner/`
4. Run `flutterfire configure` to complete setup

## 💡 How It Works

1. **Launch** → Splash screen displays app logo
2. **Home Screen** → View all expenses organized by date
3. **Add Expense** → Tap (+) button to create new entry
4. **Fill Details** → Enter amount, category, date, and description
5. **Save** → Data instantly syncs to Firebase cloud
6. **Navigate** → Use month navigation to view expense history

## 🎓 Learning Outcomes

This project demonstrates proficiency in:
- ✅ Flutter framework and widget architecture
- ✅ Firebase integration and cloud database management
- ✅ State management and data handling
- ✅ UI/UX design principles and responsive layouts
- ✅ API integration and third-party packages
- ✅ Version control with Git and GitHub

## 👨‍💻 Developer

**Param Vadher**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github)](https://github.com/Param-vadher)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/param-vadher-b1a9b7333)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:paramvadher04@gmail.com)

---

<div align="center">

**⚡ Developed as part of Mobile Application Development Workshop**

Made with ❤️ using Flutter & Firebase

</div>
