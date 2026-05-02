

# 🚀 Quickstep - Backend Server

A backend server for a real-time live location tracking application built with Flutter. This system enables seamless communication, movement tracking, and user interaction in real time.

---

## ✨ Key Features & Functionalities

### 📍 Real-Time Location Tracking

* Continuously updates user location coordinates in real time
* Broadcasts location changes to users within the same movement room
* Allows users to join or leave movement rooms
* Notifies other participants when someone joins or exits
* Fetches the list of active users in a movement room

### 💬 Real-Time Chat

* Send and receive instant text messages between users

### 🔐 User Authentication & Account Management

* User registration and login
* Email verification system
* Send or resend OTP via email
* Access tokens expire after 2 hours for security

### 👤 Profile Management

* Create and manage user profiles

### 🚶 Movement Management

* Create, delete, or leave movement groups
* Accept or decline movement join requests

### 🔔 Notifications

* Generate, receive, and clear notifications

---

## 🌐 API & Demo

* **API Base URL:**
  [https://quickstep.up.railway.app/](https://quickstep.up.railway.app/)

* **Client Demo Video (YouTube):**
  [https://www.youtube.com/watch?v=V_tnQ8OqVaw](https://www.youtube.com/watch?v=V_tnQ8OqVaw)

---

## 📱 Client Application

The Flutter mobile app for this project is available here:
[https://github.com/aimelive/quickstep_app](https://github.com/aimelive/quickstep_app)

---

## 📄 API Documentation

Interactive API documentation (Swagger) is available at:

```bash
https://quickstep.up.railway.app/api/v1/docs/
```

---

## ⚙️ Running the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/aimelive/quickstep-backend
```

### 2. Navigate to Project Directory

```bash
cd quickstep-backend
```

### 3. Environment Setup

* Create a `.env` file in the root directory
* Add all required variables as specified in `.env.example`

### 4. Install Dependencies

```bash
npm install
```

### 5. Start the Server

* For production:

```bash
npm start
```

* For development:

```bash
npm run dev
```

The server will run on port **3000** or the port defined in your environment variables.

👉 Test the API using:

```
https://localhost:[YOUR_PORT]/api/v1/
```

You can use tools like Postman, Thunder Client, or any REST API client for testing.

---

## 📌 Prerequisites

Ensure you have the following installed before running the project:

* Node.js
* TypeScript
* MongoDB
* AWS S3 Bucket
* Email Service Provider (e.g., Gmail for Nodemailer)

---

## 🛠️ Technologies Used

* Socket.io (Real-time communication)
* Node.js + Express
* TypeScript
* MongoDB
* Agenda (Job scheduling)
* AWS S3 (File storage)
* Nodemailer (Email service)
* Swagger (API documentation)

---

If you want, I can also convert this into a **GitHub README optimized version (with badges + visuals)** or a **presentation format for viva/project submission** 👍
