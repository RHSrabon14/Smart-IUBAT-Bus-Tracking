# 🚌 Smart IUBAT Bus Tracking & Passenger Monitoring System

An IoT-based smart university transportation system combining real-time GPS tracking, AI-powered passenger detection, and web-based bus management.

## 📌 Project Overview

Smart IUBAT Bus Tracking & Passenger Monitoring is designed to improve university transportation by helping students and faculty check bus locations and passenger counts before choosing a bus.

The system combines IoT hardware, GPS technology, computer vision, and a MERN stack web application to provide smarter and more convenient transportation information.

## ✨ Key Features

- 📍 Real-time GPS-based bus tracking.
- 👨‍🎓 Separate Student and Faculty panels.
- 🔐 University ID-based access for students and faculty.
- 👨‍💻 Dedicated Admin login.
- 🚌 Bus information management.
- 📷 ESP32-CAM-based passenger image capture.
- 📡 SIM800L mobile internet connectivity.
- 📶 Wi-Fi as an alternative image transmission method.
- 🤖 YOLO-based passenger detection.
- 📊 Passenger count display on the website.

## 🏗️ Technologies Used

| Category | Technologies |
|---|---|
| Frontend | React.js |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| AI & Computer Vision | Python, YOLO |
| Hardware Controller | ESP32-CAM |
| GPS Module | NEO-6M |
| Communication | SIM800L, Wi-Fi |
| Mobile Network | Grameenphone SIM / GPRS |

## 🔌 Hardware Components

- **ESP32-CAM:** Captures images of passengers inside the bus.
- **NEO-6M GPS:** Retrieves geographical coordinates for live bus tracking.
- **SIM800L GSM/GPRS:** Provides mobile internet connectivity using a Grameenphone SIM.
- **Wi-Fi:** Provides an alternative connection for image transmission when SIM800L connectivity is unavailable or unsuccessful.

## 🔄 How It Works

1. The NEO-6M GPS module obtains the bus's geographical location.
2. The ESP32-CAM captures images inside the bus.
3. Images are transmitted through SIM800L mobile internet.
4. If SIM800L connectivity is unavailable or transmission fails, Wi-Fi is used as an alternative.
5. The backend receives the uploaded images.
6. A separate Python service processes the images using YOLO.
7. YOLO detects people and calculates the passenger count.
8. Bus location and passenger information are displayed on the website.

## 👥 User Panels

### 🎓 Student Panel
- Access using university ID.
- View available buses.
- Check live bus locations.
- View passenger counts before choosing a bus.

### 👨‍🏫 Faculty Panel
- Access using university ID.
- View bus information.
- Track bus locations.
- Check passenger counts.

### 🛠️ Admin Panel
- Dedicated administrator login.
- Manage and update bus information.
- Maintain transportation data.

## 📸 Software Screenshots

### 1. Homepage and Login

![Homepage and Login](./homepage.png)

### 2. Admin Dashboard

![Admin Dashboard](./admin-dashboard.png)

### 3. Live GPS Tracking

![Live GPS Tracking](./live-gps-tracking.png)

## 🚀 Future Improvements

- Improve passenger detection accuracy.
- Implement bus arrival-time estimation.
- Add historical passenger statistics.
- Improve connectivity and transmission reliability.
- Introduce advanced transportation analytics.

## 🎯 Project Goal

To make university transportation smarter, more transparent, and more convenient by combining IoT, GPS tracking, artificial intelligence, and web technologies.

## 👨‍💻 Project Information

**Project Name:** Smart IUBAT Bus Tracking & Passenger Monitoring System

**Institution:** International University of Business Agriculture and Technology (IUBAT)

**Location:** Dhaka, Bangladesh

---

⭐ If you find this project interesting, feel free to explore the repository!
