# 🔔 Smart Notice Board using Firebase and ESP32

A real-time digital notice board system that uses **ESP32** and **Firebase Realtime Database** to display announcements remotely on a large LED panel. This project is ideal for smart campuses, institutions, offices, or public displays.

---

## 🚀 Features

- 📡 Realtime communication with Firebase
- 🔒 Secure notice control via Firebase Authentication
- 🖥️ Intuitive Web Dashboard for uploading and managing notices
- 📲 Scalable for large LED matrix panels (tested with 3ft+ displays)
- 🌐 Easily deployable dashboard on GitHub Pages
- 🔧 Modular code structure (easy to upgrade with sensors later)

---

## 🧱 Tech Stack

- **Microcontroller:** ESP32
- **Cloud Platform:** Firebase Realtime Database + Authentication
- **Frontend:** HTML, CSS, JavaScript
- **Deployment:** GitHub Pages
- **Display Module:** LED Matrix or OLED Panel (via SPI)

---

## 📁 Project Structure

```plaintext
├── public/
│   ├── index.html       # Main Web Dashboard
│   ├── styles.css       # Styling
│   └── app.js           # Firebase logic & real-time sync
├── esp32/
│   └── esp32_firebase.ino # ESP32 code for syncing with RTDB
├── firebase/
│   └── firebase-config.js # Firebase Web SDK config
└── README.md
