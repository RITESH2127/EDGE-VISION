<div align="center">
  
  # 👁️ EdgeVision
  **An AI-Powered Real-Time Monitoring & Geospatial Intelligence Platform**

  ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
  ![face-api.js](https://img.shields.io/badge/face--api.js-AI-FF6F00?style=for-the-badge)
  ![MapGL](https://img.shields.io/badge/react--map--gl-Geospatial-4CAF50?style=for-the-badge)
  ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)

</div>

<br />

## 📖 Project Description

**EdgeVision** is a cutting-edge web application designed for intelligent surveillance, location tracking, and real-time facial analysis. Built with a modern React architecture, it seamlessly integrates live webcam feeds with advanced machine learning models in the browser to detect and process facial data. Coupled with interactive geospatial mapping, EdgeVision provides a comprehensive dashboard for situational awareness and monitoring. 

Whether it's for advanced security analytics, spatial tracking, or real-time video intelligence, this platform delivers a visually stunning, highly interactive user interface designed for modern web standards.

---

## ✨ Features

- **Real-Time Facial Recognition:** Utilizes `face-api.js` for on-the-fly face detection, landmark tracking, and facial feature analysis directly in the browser.
- **Live Video Feed Integration:** Captures and processes real-time webcam streams using `react-webcam`.
- **Geospatial Mapping:** Interactive, high-performance map visualizations powered by `react-map-gl` for location-based intelligence and tracking.
- **Media Playback & Analysis:** Support for custom video analysis and media playback via `react-player`.
- **Modern UI/UX:** A highly responsive, visually appealing front-end designed to handle complex data streams gracefully.
- **Client-Side Processing:** Leverages Web Workers (`worker-loader`) to maintain a smooth, non-blocking user interface during heavy AI computations.

---

## 🛠️ Tech Stack

- **Frontend Framework:** React 18 (`react`, `react-dom`)
- **Routing:** React Router (`react-router-dom`, `react-router-hash-link`)
- **AI / Computer Vision:** `face-api.js`
- **Mapping & Geospatial:** `react-map-gl`
- **Media & Hardware:** `react-webcam`, `react-player`
- **HTTP Client:** `axios`
- **Testing:** React Testing Library (`@testing-library/react`, `@testing-library/jest-dom`)

---

## 🚀 Installation & Setup

Follow these steps to get the project up and running on your local machine.

### Prerequisites
- Node.js (v14 or higher recommended)
- npm or yarn package manager

### Steps

1. **Clone the repository**
   ```bash
   git clone [https://github.com/your-username/edgevision.git](https://github.com/your-username/edgevision.git)
   cd edgevision
   Install dependencies

2. Bash
npm install
Configure Environment Variables
Create a .env file in the root directory and add any necessary API keys (e.g., Mapbox token for react-map-gl):

3. Code snippet
REACT_APP_MAPBOX_TOKEN=your_mapbox_access_token_here
Start the development server

4. Bash
npm run start
Access the application
Open your browser and navigate to http://localhost:3000.
.

💻 Usage
Dashboard Overview: Upon launching, navigate to the main dashboard to view the map interface and camera feeds.

Webcam Access: Grant the browser permission to access your webcam when prompted to initialize the face-api.js detection models.

Map Navigation: Use the interactive map to track flagged events or monitored locations.

Analysis: Review captured data streams or play back specific video segments for further insights.

📂 Project Structure

edgevision/
├── public/                 # Static assets, index.html, and face-api models
├── src/
│   ├── components/         # Reusable UI components (Map, Webcam, VideoPlayer)
│   ├── pages/              # Route views (Dashboard, Settings, etc.)
│   ├── services/           # API calls (Axios) and ML logic (face-api configs)
│   ├── workers/            # Web worker scripts for off-thread processing
│   ├── App.js              # Main application entry point
│   └── index.js            # React DOM rendering
├── .gitignore              # Ignored files and directories
├── LICENSE.txt             # MIT License
├── package.json            # Project metadata and dependencies
└── package-lock.json       # Dependency lockfile


🔮 Future Improvements
NLP-Powered Querying: Integrate Natural Language Processing to allow users to search event logs using conversational text.

Backend Infrastructure: Implement a robust backend architecture for persistent storage of surveillance data and user authentication.

Advanced Data Structures: Optimize the event-logging system using more efficient data structures to handle high-frequency streams of tracking data.

Multi-Camera Support: Expand the UI to support and tile multiple concurrent webcam/IP camera feeds.
