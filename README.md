# Loopers – A Minimal Gamified Study Tracker

**Loopers** is a clean, modern, and highly interactive study management web application designed to help you organize your learning journey. Instead of relying on XP, streaks, badges, or other traditional gamification systems, Loopers motivates you through beautiful visuals, smooth animations, and satisfying progress tracking.

Everything runs entirely inside your browser using **HTML, CSS, and Vanilla JavaScript**, with all data stored locally via **LocalStorage**. No accounts, no servers, and no internet connection are required after opening the app.

---

# ✨ Features

## 📚 Subject Management

* Create unlimited subjects.
* Assign each subject:

  * Custom emoji
  * Subject name
  * Theme color
* Every subject has its own unique visual identity.

---

## 📖 Chapter Organization

* Add unlimited chapters inside every subject.
* Each chapter automatically inherits the subject's roadmap.
* Edit or remove chapters anytime.

---

## 🛣️ Shared Roadmap System

Each subject contains one customizable roadmap template.

Example:

```
Notes → Concepts → Examples → Practice → Revision → Quiz
```

All chapters inside that subject use the same roadmap.

If the roadmap template is edited, every chapter updates instantly without losing progress where possible.

---

## ✅ Progress Tracking

Complete your study one level at a time.

Each roadmap level has three possible states:

* 🔒 Locked
* 🟡 Active
* 🟢 Completed

Clicking a level opens a modal where you can:

* View the level
* Mark it as complete

Once completed:

* Progress updates instantly
* The next level unlocks automatically
* Progress bars animate smoothly
* Completion rings refresh in real time

No page reload is ever required.

---

## 🎯 Duolingo-Inspired Roadmap

Loopers features a clean vertical roadmap inspired by modern learning apps.

Features include:

* Circular progress nodes
* Animated connector lines
* Locked, active, and completed states
* Smooth transitions
* Interactive level modals

The roadmap provides a clear visual representation of your learning progress.

---

## 🏠 Dashboard

The Home page provides an overview of your entire study journey.

Includes:

* Total subjects
* Total chapters
* Completed levels
* Overall completion percentage
* Continue Studying shortcut
* Recently studied chapters

Everything updates automatically as you study.

---

## 📊 Statistics

Track your progress with beautiful interactive charts powered by Chart.js.

Statistics include:

* Overall completion
* Subject-wise progress
* Chapter-wise progress
* Daily activity (simulated)
* Monthly activity (simulated)
* Top performing subjects

---

## ⚙️ Settings

Customize and manage your data with ease.

Features include:

* 🌙 Dark / Light mode
* 📤 Export all data as JSON
* 📥 Import previous backups
* 🗑 Reset all data with confirmation

---

## ⚡ Instant Updates

Loopers behaves like a modern Single Page Application (SPA).

Every action updates the interface immediately:

* Create
* Edit
* Delete
* Complete levels
* Import data
* Change settings

No refresh is ever needed.

---

# 🧩 Project Structure

The project is intentionally lightweight and consists of only two files.

```
loopers/
├── index.html      # Complete application (HTML, CSS & JavaScript)
└── README.md       # Project documentation
```

All styles and functionality are embedded inside `index.html`, making the application easy to distribute, modify, and run without any build tools.

---

# 🚀 Getting Started

1. Download or clone this repository.
2. Open `index.html` in any modern web browser.
3. Start creating subjects and chapters.
4. Your progress is automatically saved using LocalStorage.

No installation, dependencies, or server setup required.

---

# 🛠 Technologies

* HTML5
* CSS3
* Vanilla JavaScript (ES6+)
* Chart.js
* LocalStorage API

---

# 🎨 Design Inspiration

Loopers draws inspiration from several beautifully designed applications, including:

* Notion
* Duolingo
* Linear
* Arc Browser
* Apple Human Interface Guidelines

The goal is to provide a distraction-free experience with polished interactions and elegant visuals.

---

# 💾 Data Storage

All application data is stored locally in your browser using the LocalStorage API.

Your data never leaves your device unless you choose to export it as a JSON backup.

---

# 📄 License

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute it for personal or commercial purposes.

---

Built with ❤️ as a focused, distraction-free study companion for students, developers, and lifelong learners.
