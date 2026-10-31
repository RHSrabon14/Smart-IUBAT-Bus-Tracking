# 🚌 Smart IUBAT Bus Tracking & Passenger Monitoring System

An IoT-based university transportation solution combining real-time GPS tracking, AI-powered passenger detection, and web-based bus management.

## 📌 Project Overview

Smart IUBAT Bus Tracking helps IUBAT students and faculty check bus locations and passenger counts before choosing a bus.

The system combines an ESP32-CAM-based hardware setup, NEO-6M GPS, SIM800L mobile connectivity, a MERN web application, MongoDB, and Python-based YOLO passenger detection.

## ✨ Key Features

- Real-time bus location tracking.
- Separate Student and Faculty panels.
- University ID-based access.
- Dedicated Admin login.
- Bus information management.
- ESP32-CAM passenger image capture.
- SIM800L mobile internet with Wi-Fi fallback.
- YOLO-based passenger detection.
- Passenger count display on the website.

## 🏗️ Technologies Used

**Frontend:** React.js

**Backend:** Node.js, Express.js

**Database:** MongoDB

**AI & Computer Vision:** Python, YOLO

**Hardware:** ESP32-CAM, NEO-6M GPS, SIM800L

**Connectivity:** Grameenphone SIM / GPRS and Wi-Fi

## 🔄 How It Works

1. NEO-6M GPS obtains the bus location.
2. ESP32-CAM captures images inside the bus.
3. Images are uploaded using SIM800L mobile internet, with Wi-Fi as an alternative.
4. The backend receives the images.
5. A separate Python service processes images using YOLO.
6. YOLO detects people and calculates the passenger count.
7. Bus location and passenger information are displayed on the website.

## 👥 User Panels

- **Student:** View bus locations and passenger counts.
- **Faculty:** Access bus tracking and passenger information.
- **Admin:** Sign in and manage bus information.

## 📸 Software Screenshots

### Homepage and Login
![Homepage](homepage.png)

### Admin Dashboard
![Admin Dashboard](admin-dashboard.png)

### Live GPS Tracking
![Live GPS Tracking](live-gps-tracking.png)

## 🔮 Future Improvements

- Improved passenger detection accuracy.
- Bus arrival-time estimation.
- Passenger statistics and analytics.
- Enhanced connectivity and reliability.

## 🎯 Project Goal

To make university transportation smarter, more convenient, and more transparent through IoT, AI, GPS, and web technologies.

**Developed as a university project at International University of Business Agriculture and Technology (IUBAT), Dhaka, Bangladesh.**
