# 🚌 Online Bus Booking - A MERN Based Web Application

**Bus Book** is a full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) that allows users to **search, book, and manage bus tickets online**. It supports both user and admin roles, enabling passengers to browse routes, select available seats, and book trips securely, while admins can manage buses, schedules, and bookings from a dedicated dashboard.

This project solves the real-world problem of manual and offline ticketing by offering a 24/7 accessible, user-friendly platform that minimizes booking errors and long queues. It improves convenience for travelers and streamlines transport operations via centralized management.

---

## 🔍 Summary

- Role-based access: User & Admin
- Secure authentication using **JWT & Google OAuth**
- Real-time seat selection and booking
- Admin dashboard to manage buses, routes, schedules, and bookings
- CRUD operations for buses, users, and bookings
- Responsive UI matching high-fidelity mockups
- File upload support (e.g., bus images)

---

## 🎯 Objectives

- Build a responsive bus ticket booking system using the MERN stack.
- Allow users to search buses, view seat availability, and book in real-time.
- Implement secure authentication for users and admins (JWT & Google OAuth).
- Enable admins to manage buses, schedules, and bookings efficiently.
- Eliminate manual ticketing errors through digital automation.

---

## 🛠️ Tech Stack

| Layer        | Technology                          |
|--------------|-------------------------------------|
| Frontend     | React.js, React Router, Tailwind CSS |
| Backend      | Node.js, Express.js                 |
| Database     | MongoDB with Mongoose               |
| Auth         | JWT & Google OAuth (Firebase)       |
| Deployment   | Vercel, MongoDB Atlas               |
| Tools        | GitHub, Postman, Figma              |

---

## 📅 Day-wise Development Plan

### ✅ Day 1: Project Kick-off
- Finalize idea, features
- Create low-fidelity design (wireframes via Figma or pen-paper)

### ✅ Day 2: High-Fidelity Design + Tracking Setup
- Design high-fidelity UI using Figma
- Set up GitHub Project board for task tracking

### ✅ Day 3: Backend Initialization
- Initialize backend with Express.js
- Install dependencies (`express`, `mongoose`, etc.)
- Connect MongoDB using Mongoose
- Design initial schemas (User, Book)
- Push to GitHub

### ✅ Day 4: CRUD API - GET & POST
- Create GET endpoints (`/books`, `/users`)
- Create POST endpoints (`/register`, `/books/add`)
- Test APIs using Postman
- Update API documentation

### ✅ Day 5: Database Integration
- Implement DB operations using Mongoose
- Add sample data to MongoDB Atlas
- Update GitHub board with progress

### ✅ Day 6: PUT API + Relationships
- Create PUT APIs (update user/book)
- Define schema relationships (e.g., user → bookings)
- Test update routes

### ✅ Day 7: Backend Deployment
- Deploy backend to **Vercel**
- Add base URL to `.env` and documentation

### ✅ Day 8: React Frontend Initialization
- Set up frontend using Vite or CRA
- Connect to GitHub
- Create folder structure (components, pages)
- Add issues to project board

### ✅ Day 9: UI Components & Design Matching
- Build key components (Header, BookList, Login, etc.)
- Match high-fidelity design using TailwindCSS

### ✅ Day 10: Frontend Deployment
- Deploy frontend to **Vercel**
- Connect with backend API
- Add deployed URLs to README

### ✅ Day 11: Auth (Username/Password)
- Implement login & registration with **bcrypt**
- Use **JWT** for token-based auth
- Store tokens in `localStorage`
- Protect routes using React guards

### ✅ Day 12: Auth (Google Login)
- Set up Google OAuth with Firebase
- Store user info in DB if not present
- Add Google login button

### ✅ Day 13: Update & Delete Functionality
- Add frontend for PUT/DELETE actions
- Sync UI updates with backend
- Ensure data consistency

### ✅ Day 14: File Upload
- Use `multer` in backend for image uploads
- Upload files (e.g., bus image) from React
- Display uploaded images in UI

### ✅ Day 15: Final Wrap-Up
- Clean code, fix bugs
- Submit:
  - Low & High-Fidelity Designs
  - GitHub Repos (Frontend & Backend)
  - GitHub Project Board (10+ tracked entries)
  - Deployed Links
  - Screenshots (API test, Auth flow, UI match, etc.)





