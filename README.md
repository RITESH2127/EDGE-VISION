<div align="center">

# 👁️ EdgeVision

**An AI-Powered Real-Time Monitoring & Geospatial Intelligence Platform**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge\&logo=react\&logoColor=61DAFB)
![face-api.js](https://img.shields.io/badge/face--api.js-AI-FF6F00?style=for-the-badge)
![MapGL](https://img.shields.io/badge/react--map--gl-Geospatial-4CAF50?style=for-the-badge)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)

</div>

<br />

## 📖 Project Description

**EdgeVision** is a cutting-edge web application designed for intelligent surveillance, location tracking, and real-time facial analysis. Built with a modern React architecture, it seamlessly integrates live webcam feeds with advanced machine learning models in the browser to detect and process facial data.

Coupled with interactive geospatial mapping, EdgeVision provides a comprehensive dashboard for situational awareness and monitoring.

Whether it's for advanced security analytics, spatial tracking, or real-time video intelligence, this platform delivers a visually stunning, highly interactive user interface designed for modern web standards.

---

## ✨ Features

* 🔍 **Real-Time Facial Recognition**
  Uses `face-api.js` for live face detection, landmark tracking, and facial analysis directly in the browser.

* 🎥 **Live Video Feed Integration**
  Captures and processes webcam streams using `react-webcam`.

* 🗺️ **Geospatial Mapping**
  Interactive maps powered by `react-map-gl` for tracking and visualization.

* 🎬 **Media Playback & Analysis**
  Supports video playback and analysis via `react-player`.

* 🎨 **Modern UI/UX**
  Clean, responsive interface built for performance and usability.

* ⚡ **Client-Side Processing**
  Uses Web Workers to ensure smooth performance during heavy AI processing.

---

## 🛠️ Tech Stack

* **Frontend:** React 18 (`react`, `react-dom`)
* **Routing:** React Router (`react-router-dom`, `react-router-hash-link`)
* **AI / Computer Vision:** `face-api.js`
* **Mapping:** `react-map-gl`
* **Media:** `react-webcam`, `react-player`
* **HTTP Client:** `axios`
* **Testing:** React Testing Library

---

## 🚀 Installation & Setup

### 📌 Prerequisites

* Node.js (v14 or higher recommended)
* npm or yarn

---

### ⚙️ Steps

1. **Clone the repository**

```bash
git clone https://github.com/your-username/edgevision.git
cd edgevision
```

2. **Install dependencies**

```bash
npm install
```

3. **Configure environment variables**

Create a `.env` file in the root directory:

```env
REACT_APP_MAPBOX_TOKEN=your_mapbox_access_token_here
```

4. **Run the development server**

```bash
npm start
```

5. **Open the app**

Go to:
👉 http://localhost:3000

---

## 💻 Usage

* **Dashboard:** View real-time map and video feeds.
* **Webcam Access:** Allow camera permissions for facial detection.
* **Map Interaction:** Track locations and events visually.
* **Analysis:** Review captured video and data insights.

---

## 📂 Project Structure

```
edgevision/
├── public/                 # Static assets & ML models
├── src/
│   ├── components/         # UI components
│   ├── pages/              # Application pages
│   ├── services/           # API & ML logic
│   ├── workers/            # Web workers
│   ├── App.js              # Main app
│   └── index.js            # Entry point
├── .gitignore
├── LICENSE.txt
├── package.json
└── package-lock.json
```

---

## 🔮 Future Improvements

* 🤖 **NLP-Based Search**
  Query event logs using natural language.

* 🗄️ **Backend Integration**
  Add database & authentication system.

* ⚙️ **Performance Optimization**
  Improve handling of high-frequency data streams.

* 📷 **Multi-Camera Support**
  Enable multiple camera feeds in UI.

---

## 📜 License

This project is licensed under the **MIT License**.

---

<div align="center">

⭐ *If you like this project, consider giving it a star!*

</div>
