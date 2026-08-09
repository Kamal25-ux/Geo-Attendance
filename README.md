# Geo Attendance System

A location-based attendance management system that uses GPS/geofencing to verify whether a student is within the permitted attendance area before marking attendance.

## 📌 Overview

The **Geo Attendance System** is designed to make attendance more reliable, secure, and convenient by using geographical location verification.

Instead of relying only on manual attendance, the system verifies the user's current location and allows attendance to be marked only when the user is within the configured attendance area.

## ✨ Features

* 📍 GPS-based attendance verification
* 🗺️ Geofencing for attendance locations
* 📏 Distance calculation between user and attendance location
* 👨‍🎓 Student attendance management
* 👨‍💼 Admin management
* 🔐 User authentication and authorization
* 📊 Attendance records and tracking
* 🕒 Attendance date and time recording
* 🔒 Protected API routes
* 📱 Responsive user interface
* 📈 Attendance analytics and reports

## ⚙️ How It Works

1. The student logs into the system.
2. The system obtains the student's current geographical location.
3. The location is compared with the configured attendance location.
4. The distance between the two locations is calculated.
5. If the student is within the allowed geofence, attendance can be marked.
6. The attendance record is stored with the student's details, date, time, and location information.
7. Administrators can view and manage attendance records.

## 🛠️ Technology Stack

### Frontend

* React.js
* HTML
* CSS
* JavaScript

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Authentication

* JWT (JSON Web Token)

### Location Services

* Browser Geolocation API
* GPS coordinates
* Geofencing
* Haversine distance calculation

## 📂 Project Structure

```text
Geo-Attendance/
│
├── client/              # Frontend application
├── server/              # Backend application
├── README.md
├── .gitignore
└── package.json
```

> The exact folder structure may vary depending on the project configuration.

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/Kamal25-ux/Geo-Attendance.git
```

Move into the project directory:

```bash
cd Geo-Attendance
```

Install the required dependencies for the project.

For the frontend:

```bash
npm install
```

For the backend:

```bash
npm install
```

## 🔐 Environment Variables

Create a `.env` file for configuration values such as:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
PORT=your_port
```

Do not upload `.env` to GitHub because it may contain sensitive credentials.

## ▶️ Running the Project

Start the backend server:

```bash
npm start
```

Start the frontend application:

```bash
npm start
```

The exact commands may depend on the project's package configuration.

## 👨‍🎓 Student Features

Students can:

* Register and log in
* Access their attendance dashboard
* Allow location access
* Mark attendance based on their location
* View attendance records
* Track attendance status

## 👨‍💼 Admin Features

Administrators can:

* Manage students
* Manage attendance locations
* Configure geofencing parameters
* View attendance records
* Monitor attendance statistics
* Manage user accounts

## 📍 Geolocation & Geofencing

The system uses geographical coordinates to determine whether a student is physically present within the permitted attendance area.

The distance between the student's location and the registered attendance location can be calculated using the **Haversine formula**.

Attendance is accepted only when the calculated distance is within the configured radius.

## 🔒 Security

The system uses authentication and authorization mechanisms to protect user data and application resources.

Security considerations include:

* JWT-based authentication
* Protected API endpoints
* Role-based access
* Environment variables for sensitive configuration
* Server-side validation

## 🔮 Future Enhancements

Possible future improvements include:

* Face recognition
* Fingerprint authentication
* Real-time attendance notifications
* Advanced attendance analytics
* Export attendance reports
* Mobile application
* Multiple campus/location support
* Improved anti-spoofing mechanisms

## 👨‍💻 Author

**Kamal**

GitHub:
https://github.com/Kamal25-ux

Project Repository:
https://github.com/Kamal25-ux/Geo-Attendance

## 📄 License

This project is developed for educational and project purposes.
