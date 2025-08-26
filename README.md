# Auxia_Hackathon
# Student Attendance Tracker and Viewer

## Project Overview
The **Student Attendance Tracker and Viewer** is a web-based system designed to automate attendance management in educational institutions. It replaces manual roll calls with a secure, real-time, and fraud-proof solution. The system uses innovative features like QR codes, geofencing, and WiFi authentication to ensure accurate and fraud-free attendance marking.

---

## Features
- **Real-Time Attendance**: QR Code + Geofencing + WiFi authentication ensures accurate and immediate attendance marking.
- **Transparent Attendance Records**: Students can view their attendance history and track their participation in courses.
- **Teacher Dashboard**: Teachers can upload course materials, generate attendance reports, and track student participation.
- **Scalable**: Built using MongoDB and FastAPI, the system supports thousands of concurrent users.
- **Cross-Platform**: Fully responsive for both desktop and mobile devices.
- **Efficient & Secure**: JWT-based authentication, Role-Based Access Control (RBAC), and secure attendance tracking features.

---

## Tech Stack
- **Frontend**: React.js, Redux, Tailwind CSS (Responsive UI, State Management, Styling)
- **Backend**: Node.js with Express.js, FastAPI (High-Performance API Services)
- **Database**: MongoDB (NoSQL, Scalable)
- **Authentication & Security**: JWT, Role-Based Access Control (RBAC), OAuth 2.0 (Optional)
- **Verification**: QR Code Generation, Geofencing (GPS Location Validation), WiFi Authentication

---

## System Flow

### **For Students:**
- **Login**: Students log in using their credentials.
- **Attend Class**: Scan the QR code provided by the teacher. The system verifies location, time, and WiFi connection.
- **View Attendance**: Students can view their attendance history and download course resources (e.g., PDFs, PPTs).

### **For Teachers:**
- **Login**: Teachers log in with their credentials.
- **Create Class Session**: Generate a unique QR code for each class session.
- **Upload Resources**: Teachers can upload materials like PDFs, PPTs, and class notes.
- **View Reports**: Teachers can view and export attendance reports.
  

