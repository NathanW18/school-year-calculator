# 🎓 Academic Progress Tracker

A lightweight, customizable browser extension that calculates real-time academic year progress with custom parameter handling.

## ✨ Features
* **Real-Time Progress Engine:** Calculates completion metrics down to micro-percentages, updating every second.
* **Custom Break Parameters:** Adjust calendar bounds to exclude weekends, holidays, and custom break periods.
* **Persistent Configuration:** Stores user-defined school year parameters via `chrome.storage.local`.
* **Zero-Lag UI:** Optimized CSS/JS lifecycle preventing DOM layout thrashing and background resource drain.

## 🛠️ Tech Stack
* **Frontend:** HTML5, CSS3, Vanilla JavaScript (ES6+)
* **Runtime:** Web Extensions API (Manifest V3)
* **Storage:** `chrome.storage` API

## 🚀 Getting Started
1. Clone this repository to your local machine.
2. Open Chrome and navigate to `chrome://extensions/`.
3. Enable **Developer Mode** (top-right toggle).
4. Click **Load Unpacked** and select the project directory.
