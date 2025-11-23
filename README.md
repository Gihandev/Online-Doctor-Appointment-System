
# Online Doctor Appointment System (MERN + Selenium)

A full-stack **Doctor Appointment Booking System** developed for a **Software Quality Assurance (SQA)** module.  
Built with the **MERN Stack** (MongoDB, Express, React, Node.js) and styled with **Tailwind CSS**, this project focuses on functionality and automated testing using **Selenium**.

<!-- REPLACE WITH YOUR ACTUAL SCREENSHOT -->
<img width="1877" height="917" alt="image" src="https://github.com/user-attachments/assets/2aad3d92-e992-4998-b9d7-74f3e590f272" />


---

## 🚀 Features
- 🔐 **Secure Authentication** (Login/Register for Patients & Admins)
- 📅 **Appointment Booking** (Patients can browse and book slots)
- 👨‍⚕️ **Doctor Management** (Admin can add/edit doctor details)
- 📊 **Admin Dashboard** (Manage users, appointments, and system data)
- 🧪 **Automated Testing** (SQA testing scripts using Selenium)

---

## 🛠 Tech Stack

| Layer | Technology |
|--------|-------------|
| **Frontend** | React (Vite), Tailwind CSS, Axios |
| **Backend** | Node.js, Express.js, Mongoose, JWT (Auth) |
| **Database** | MongoDB |
| **Quality Assurance** | Selenium (Automated Testing) |

---

## 📦 Setup Guide

### 1. Clone Repository
```bash
git clone https://github.com/Gihandev/Online-Doctor-Appointment-System.git
```

### 2. Backend Setup
```bash
cd server
npm install
```

### 3.  Configure Backend (.env)
```bash
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

### 4. Run Backend Server
```bash
npm start
```

### 5. Frontend Setup
```bash
cd ../client
npm install
```

### 6. Run React App
```bash
npm run dev
```

## 🧪 Running Tests (Selenium)
This project includes Selenium scripts for SQA purposes.

- Ensure the local server is running (Frontend: 5173, Backend: 5000).
- Navigate to the testing directory (if applicable) and execute the test suite.

## 🎥 Demo
Live Portfolio - https://github.com/Gihandev/Online-Doctor-Appointment-System


## ⚠️ Notes & Trade-offs
- Focus: This project was built primarily to demonstrate SQA principles and Selenium automation.
- Database: Uses MongoDB Atlas or local instance.
- Roles: Distinct flows for Admin vs. Patient users.

## 👨‍💻 Author

Gihan Serasinghe

- Portfolio: https://gihandev.vercel.app/
- GitHub: https://github.com/Gihandev


If you like this project, please give it a ⭐!
