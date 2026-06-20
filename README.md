# Flutter_Task_Scheduling_App

A visual task management app built with Flutter, where tasks appear as colorful leaves on an animated tree. Instead of a boring list, your to-dos grow on branches — watch leaves fall when tasks are completed and removed.

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)

---

## About

Task Scheduling Tree reimagines the traditional to-do list as an interactive tree. Each task becomes a leaf placed on a branch of your choosing, colored by priority. As you complete or delete tasks, leaves animate and fall away — giving visual, satisfying feedback for productivity.

---

## Features

- **Animated tree visual** — hand-drawn trunk and branches using custom canvas painting
- **Tasks as leaves** — color-coded by priority (red = high, yellow = medium, green = low)
- **Branch placement** — choose exactly which branch each task sits on
- **Animated sky** — slow-drifting clouds and swaying leaves for a calm, living feel
- **Search & filter** — find tasks by name, description, priority, or completion status
- **Reminders dashboard** — tasks grouped into Overdue, Due Today, and Upcoming
- **Task management** — add, edit, mark complete, and delete with smooth fall animations
- **Persistent storage** — tasks saved locally and restored automatically between sessions
- **Responsive design** — works across mobile, web, and desktop screen sizes
- **Settings panel** — view stats and manage stored data

---

## Built With

| Technology | Purpose |
|---|---|
| [Flutter](https://flutter.dev) | Cross-platform UI framework |
| [Dart](https://dart.dev) | Programming language |
| [Provider](https://pub.dev/packages/provider) | State management |
| [SharedPreferences](https://pub.dev/packages/shared_preferences) | Local data persistence |
| [UUID](https://pub.dev/packages/uuid) | Unique task ID generation |
| [Intl](https://pub.dev/packages/intl) | Date formatting |

---

## Getting Started

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install) (3.0.0 or higher)
- A code editor (VS Code or Android Studio recommended)
- Chrome (for web testing) or an Android/iOS emulator

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/task-scheduling-tree.git
   cd task-scheduling-tree
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Run the app**

   On Chrome (web):
   ```bash
   flutter run -d chrome
   ```

   On a connected device or emulator:
   ```bash
   flutter run
   ```

---

## 📦 Building for Production

**Web build:**
```bash
flutter build web --release
```
Output located in `build/web/`

**Android APK:**
```bash
flutter build apk --release
```
Output located in `build/app/outputs/flutter-apk/app-release.apk`

---

## How to Use

1. Tap **Add Task** and fill in the task name, priority, due date, and an optional description
2. Choose which branch to place your task on from the branch selector
3. Your task appears as a colored leaf on the tree
4. Tap any leaf to view details, edit, mark complete, or delete it
5. Use the **Search** tab to find tasks quickly
6. Check the **Reminders** tab to see what's overdue or coming up
7. Visit **Settings** for app stats and to manage stored data

---

## Priority Color Guide

| Priority | Color |
|---|---|
| High | 🔴 Red |
| Medium | 🟡 Yellow |
| Low | 🟢 Green |
| Completed | 🟤 Brown |

---

## Data & Privacy

All task data is stored locally on your device using `SharedPreferences` (browser `localStorage` on web). No account or sign-up is required, and no data is sent to any external server — your tasks stay completely private to your device.

---

## Roadmap

- [ ] Push notifications for due dates
- [ ] Cloud sync across devices
- [ ] Dark mode theme
- [ ] Multiple tree types/themes
- [ ] Task categories/tags

