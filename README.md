# 🗂️ Advanced File Organizer Bot — Smart Desktop Utility

An intelligent Python utility that automatically **sorts files** in real-time based on **file type**, **date**, **extension**, or **size**. It features a user-friendly **GUI toggle** and uses the `watchdog` library for **live folder monitoring**.

---

## 📝 Description

This tool helps keep your download or workspace folders neat by auto-sorting files into categorized folders. You can toggle options through a minimal GUI and let the organizer run in the background while you work.

---

## ✨ Features

- 🔄 **Real-time folder monitoring** using `watchdog`
- 🧠 **Auto-sorts files** by:
  - File type (e.g., images, videos, documents)
  - Extension (e.g., `.pdf`, `.mp3`)
  - Size range (small, medium, large)
  - Creation or modification date
- 🖥️ **Minimal GUI** with toggle buttons for organizing mode
- 📁 Custom folder selection for source/destination
- 💾 Runs in background and handles file events instantly

---

## 💻 Technologies Used

- **Python 3.x**
- `Tkinter` – for GUI
- `watchdog` – for real-time file system event monitoring
- `os`, `shutil`, `time`, `pathlib` – for file operations

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/advanced-file-organizer-bot.git
cd advanced-file-organizer-bot
