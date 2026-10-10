# TrafficEase BD 🚦

An urban traffic management application built to tackle real-world congestion challenges in Bangladesh. Developed as the final project for CSE470: Software Engineering at BRAC University.

## 📋 About the Project
TrafficEase BD provides a digital solution for monitoring and managing urban traffic flow. This project was developed with a strong emphasis on the complete software development lifecycle (SDLC), moving beyond basic implementation to include rigorous requirements engineering and automated testing.

## 💻 Tech Stack
* **Frontend:** React.js, CSS, Leaflet.js
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Authentication:** JWT & bcrypt
* **Architecture:** MVC (Strictly followed)

## ✨ Implemented Modules
* **Role-Based Authentication:** JWT login and registration with Commuter, Driver, Admin, and Authority roles.
* **Live Traffic Command Center:** Real-time panels for congestion, speed, queues, signals, transit, weather, and route recommendations.
* **Live Traffic Map:** Interactive Leaflet.js map with incident markers, vehicle trackers, and colored corridor pressure overlays.
* **Incident Management:** End-to-end incident reporting and verification tracking.
* **City Infrastructure:** Live monitoring for parking lot capacity, traffic signals, and public transit routes.
* **Fleet & Communications:** Vehicle registration, fleet status, and public alert broadcasting.

<details>
<summary><strong>View all 30 Feature Modules</strong></summary>

* Live congestion index & Corridor speed monitor
* Queue length estimator & Signal phase tracking
* Adaptive signal timing & Signal failure alerts
* Incident reporting & Verification queue
* Emergency vehicle priority & School-zone safety mode
* Weather impact scoring & Flood-prone road alerts
* Air quality mobility note
* Bus/Metro route status & Transit delay prediction
* Crowding level monitor & Parking availability/forecast
* Ride-share pickup zones & CNG stand availability
* Pedestrian crossing load & Road work scheduling
* Event traffic plan & Route recommendation
* ETA comparison & Hotspot heat ranking
* Authority dispatch board & Public alert broadcast
* Audit-ready activity log
</details>



## 🚀 Setup Instructions

### Prerequisites
Use MongoDB Atlas or a local MongoDB instance. Update the `MONGO_URI` in the backend accordingly.

### 1. Backend Setup
Create a `.env` file in the `backend/` directory:
```env
PORT=5000
MONGO_URI=mongodb://localhost:27017/trafficease_bd
JWT_SECRET=your_super_secret_key
