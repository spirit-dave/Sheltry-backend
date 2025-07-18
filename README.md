# 🏡 Sheltry - Backend API

Welcome to the backend codebase of **Sheltry** — a platform connecting people in need of temporary accommodation with those offering shelter.

This backend powers the authentication, apartment listings, booking operations, and user notifications for the Sheltry app.


## 🔧 Tech Stack

> Replace with your actual stack

- ⚙️ Node.js
- 🛣 Express.js
- 📦 MongoDB (via Mongoose) or Firebase Firestore
- 🔐 JWT for Authentication
- 🌐 REST API


## 📁 Project Structure

```plaintext
sheltry-backend/
├── controllers/     # API logic (auth, listings, bookings)
├── models/          # MongoDB schema definitions
├── routes/          # Route definitions and middlewares
├── services/        # Business logic, email, push services
├── config/          # Environment configs
├── middlewares/     # Auth, error handling, etc.
├── utils/           # Utility functions (validators, formatters)
├── app.js           # Entry point
└── README.md        # This file
