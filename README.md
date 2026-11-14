# DailyDone

**A simple, modern, offline-ready task manager for Android.**

DailyDone helps you organize everyday activities, track completed tasks, and stay productive with a clean, minimal interface. The app is built with HTML, CSS, and JavaScript and is designed to keep your tasks on your device.

<div align="center">

[⬇️ Download the DailyDone APK](https://github.com/fahimshahriar-cs/DailyDone/raw/refs/heads/main/dailydone.apk)

*Direct APK download · Early build, not a Play Store release*

</div>

## Features

- **Personalized welcome:** Enter your name for a personalized dashboard.
- **Task management:** Add and delete tasks.
- **Completion tracking:** Mark tasks as complete or unfinished.
- **Live progress:** See task completion progress update automatically.
- **Task statistics:** View completed and unfinished task counts.
- **Automatic saving:** Your name and tasks are saved locally.
- **Offline support:** Continue using core features offline after the app has loaded and its required files have been cached.
- **No daily reset:** Tasks remain saved until you delete them.
- **Privacy friendly:** No account, login, or external database is required.

## Technologies

- **HTML5** for app structure
- **CSS3** for styling and responsive layouts
- **JavaScript** for task management and app behavior
- **LocalStorage** for saving your name and tasks on the device
- **Web App Manifest** and **Service Worker** for PWA installation and offline caching
- **Netlify** as a hosting option for the web version

## Offline use and data

DailyDone stores your name and tasks locally on your device. Data is not automatically synchronized between devices. Clearing the app or browser storage may remove locally saved information.

The web version needs to load successfully once so its service worker can cache the app files. The APK and web version may keep their local data separately, so data may not transfer between them.

## This repository

This repository provides the Android APK for direct download:

- Download dailydone.apk · 9.67 MB

The app’s web source files are not included in this repository.

## Developer

**Fahim Shahriar** · Computer Science student at **BRAC University**

---

*Stay organized. Stay focused. Get things done.*

**DailyDone — Small tasks. Big progress.**
