# 🚗 ParkEase — Smart Parking Management System

<p align="center">
  <strong>Find. Book. Park. Stress-Free.</strong>
</p>

<p align="center">
  A full-stack smart parking platform that helps users discover available parking spaces, reserve slots, and manage bookings through a modern web application.
</p>

<p align="center">
  <a href="https://parkease-h0p3o4mfe-ranadheer.vercel.app">
    <strong>🌐 Live Demo</strong>
  </a>
  •
  <a href="https://github.com/Ranadheer5232/Parkease">
    <strong>📂 Source Code</strong>
  </a>
</p>

---

## 📌 Project Overview

**ParkEase** is a full-stack parking management application designed to simplify the process of finding and reserving parking spaces.

Traditional parking systems often require users to search manually for available spaces. ParkEase provides a centralized platform where users can explore parking locations, view parking details, and manage their reservations from one place.

The project includes a React-based frontend, a Node.js/Express backend, JWT authentication, and MongoDB database integration.

---

## ✨ Key Features

### 👤 User Features

* 🔐 User registration and login
* 🛡️ JWT-based authentication
* 🅿️ Browse available parking locations
* 🔎 View parking space details
* 📅 Reserve parking slots
* 📋 View booking history
* 👤 Manage user profile
* 🚪 Secure logout functionality

### 🛠️ Admin Features

* 📊 Admin dashboard
* 🅿️ Manage parking locations
* 📈 View parking and booking information
* 👥 Monitor registered users
* 📋 Manage reservations

### ⚙️ Technical Features

* Responsive user interface
* REST API architecture
* MongoDB database integration
* Password-based authentication
* JWT token handling
* Environment-based configuration
* Separate frontend and backend architecture
* Cloud deployment using Vercel and Render

---

## 🧰 Tech Stack

### Frontend

![React](https://img.shields.io/badge/React-2026-blue?logo=react)
![Vite](https://img.shields.io/badge/Vite-Fast%20Build-purple?logo=vite)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?logo=javascript)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-Styling-38B2AC?logo=tailwindcss)

* React.js
* Vite
* JavaScript
* Tailwind CSS
* React Router

### Backend

![Node.js](https://img.shields.io/badge/Node.js-Runtime-green?logo=node.js)
![Express](https://img.shields.io/badge/Express.js-Backend-black?logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green?logo=mongodb)

* Node.js
* Express.js
* MongoDB
* Mongoose
* JSON Web Token
* REST APIs

### Deployment

* **Frontend:** Vercel
* **Backend:** Render
* **Database:** MongoDB Atlas
* **Version Control:** Git and GitHub

---

## 🏗️ System Architecture

```text
┌──────────────────────┐
│      User Browser    │
│   React + Vite UI    │
└──────────┬───────────┘
           │ REST API Requests
           ▼
┌──────────────────────┐
│     Express Server   │
│      Node.js API     │
└──────────┬───────────┘
           │ Mongoose
           ▼
┌──────────────────────┐
│     MongoDB Atlas    │
│      Database        │
└──────────────────────┘
```

---

## 📁 Project Structure

```text
Parkease/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── package.json
│   └── vite.config.js
│
├── backend/
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── middleware/
│   │   ├── models/
│   │   ├── routes/
│   │   └── validations/
│   ├── server.js
│   └── package.json
│
├── .gitignore
└── README.md
```

---

## 🚀 Live Deployment

### Frontend

🌐 [Open ParkEase Live Website](https://parkease-h0p3o4mfe-ranadheer.vercel.app)

### Backend

🔗 [ParkEase Backend API](https://parkease-backend-2rxy.onrender.com)

### GitHub Repository

📂 [View Source Code](https://github.com/Ranadheer5232/Parkease)

---

## 💻 Run the Project Locally

### 1. Clone the Repository

```bash
git clone https://github.com/Ranadheer5232/Parkease.git
cd Parkease
```

---

### 2. Setup Backend

```bash
cd backend
npm install
```

Create a `.env` file inside the `backend` folder:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

Start the backend:

```bash
npm start
```

The backend will run on:

```text
http://localhost:5000
```

---

### 3. Setup Frontend

Open another terminal:

```bash
cd frontend
npm install
```

Create a `.env` file inside the `frontend` folder:

```env
VITE_API_URL=http://localhost:5000
```

Start the frontend:

```bash
npm run dev
```

The frontend will run on the Vite development URL shown in your terminal.

---

## 🔐 Authentication Flow

```text
User Registration
        ↓
Backend validates user details
        ↓
Password is stored securely
        ↓
User logs in
        ↓
Backend generates JWT token
        ↓
Frontend stores authentication state
        ↓
Protected pages become accessible
```

---

## 🔌 Main API Endpoints

| Method | Endpoint             | Description                     |
| ------ | -------------------- | ------------------------------- |
| POST   | `/api/auth/register` | Register a new user             |
| POST   | `/api/auth/login`    | Login and receive JWT           |
| GET    | `/api/parking`       | Fetch parking information       |
| POST   | `/api/booking`       | Create a booking                |
| GET    | `/api/booking`       | Fetch booking information       |
| GET    | `/api/dashboard`     | Access dashboard data           |
| POST   | `/api/payment`       | Process payment-related request |

> API availability may depend on the current backend configuration and database records.

---

## 🧪 Testing Checklist

* [x] Frontend runs successfully
* [x] Backend runs successfully
* [x] MongoDB Atlas connected
* [x] User registration tested
* [x] User login tested
* [x] JWT authentication implemented
* [x] Frontend and backend deployed
* [x] Environment variables separated from source code

---

## 🔮 Future Enhancements

* 📍 GPS-based parking discovery
* 📡 IoT-based live parking occupancy
* 🤖 AI-powered parking recommendations
* 📊 Machine-learning parking demand prediction
* 💳 Advanced online payment integration
* 🔔 Booking and reminder notifications
* 🗺️ Interactive parking map
* 📱 Progressive Web App support
* ⭐ User reviews and parking ratings

---

## 🎯 Learning Outcomes

Through this project, we gained practical experience in:

* Full-stack web development
* React component architecture
* REST API development
* JWT authentication
* MongoDB database management
* Backend routing and controllers
* Frontend-backend integration
* Cloud deployment
* Git and GitHub workflow
* Environment variable security

---

## 👨‍💻 Contributors

* **Rana Dheer** — Full-Stack Development, Integration and Deployment
* **ParkEase Team** — Project Design and Development

---

## 📜 License

This project is developed for educational and academic purposes.

---

<p align="center">
  <strong>⭐ If you like ParkEase, consider starring the repository!</strong>
</p>

<p align="center">
  Made with ❤️ by the ParkEase Team
</p>
