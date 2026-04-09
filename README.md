# AI-Based Digital Fatigue & Productivity Risk Prediction System

## Overview

The AI-Based Digital Fatigue & Productivity Risk Prediction System is a full-stack intelligent application designed to monitor user activity across multiple devices, analyze behavioral patterns, and predict fatigue levels using machine learning.

The system provides real-time insights, alerts, and recommendations to help users improve productivity and maintain healthy digital habits.

---

## Key Features

* Secure User Authentication (JWT-based)
* Multi-Device Integration (Laptop and Mobile)
* QR-Based Device Pairing
* Real-Time Activity Monitoring
* Machine Learning-Based Fatigue Prediction
* Interactive Dashboard with Graphs and Insights
* Smart Alerts and Recommendations
* Scalable Cloud-Ready Architecture

---

## System Architecture

The system follows a Three-Tier Architecture:

* Presentation Layer: Flutter Mobile App and Web Dashboard
* Application Layer: FastAPI Backend
* Data Layer: MongoDB Database

---

## Modules

* Authentication Module – User registration and login
* Device Pairing Module – QR-based device linking
* Data Collection Module – Captures activity data
* Data Processing Module – Cleans and structures data
* ML Prediction Module – Predicts fatigue levels
* Dashboard Module – Displays insights and analytics
* Alerts Module – Generates notifications
* Database Module – Stores system data

---

## Tech Stack

### Backend

* FastAPI (Python)
* JWT Authentication

### Frontend

* Flutter (Mobile App)
* Web Dashboard (React)

### Database

* MongoDB Atlas

### Machine Learning

* Scikit-learn
* Pandas, NumPy

---

## Project Structure

```
project-root/
│── backend/
│   ├── routes/
│   ├── models/
│   ├── services/
│   ├── ml_models/
│   └── main.py
│
│── frontend/
│   ├── mobile_app/
│   ├── web_app/
│
│── database/
│── docs/
│── README.md
```

---

## Installation and Setup

### Clone Repository

```bash
git clone https://github.com/Chandanac52/fatigue-system.git
cd fatigue-system
```

### Backend Setup

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

### Frontend Setup

```bash
cd frontend
flutter pub get
flutter run
```

---

## API Endpoints (Sample)

* POST /auth/register – Register user
* POST /auth/login – Login user
* POST /device/pair – Pair device
* POST /data/upload – Send activity data
* GET /dashboard – Fetch insights
* GET /predict – Get fatigue prediction

---

## How It Works

1. User logs in and pairs devices
2. System collects activity data from laptop and mobile
3. Data is processed and sent to the machine learning model
4. Model predicts fatigue level
5. Results are displayed on the dashboard
6. Alerts and recommendations are generated

---

## Security Features

* Password hashing using bcrypt
* JWT-based authentication
* Secure API endpoints
* Data privacy controls

---

## Future Enhancements

* Integration with wearable devices
* Advanced AI models (Deep Learning)
* Personalized recommendations
* Cross-platform expansion

---

## Contributors

Rachabattuni Sai Sindhu
Reddy Akkamma Chandana

---

## License

This project is for academic and educational purposes.

---

## Acknowledgement

This project was developed as part of MCA coursework, focusing on solving real-world problems related to digital fatigue and productivity.
