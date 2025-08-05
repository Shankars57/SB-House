# 🏠 HouseHunt: Finding Your Perfect Rental Home

A full-stack MERN (MongoDB, Express.js, React, Node.js) web application designed to simplify and streamline the house rental process. HouseHunt connects renters with property owners on a transparent, secure, and user-friendly platform.

---

## 📌 1. Introduction

**Project Title:** HouseHunt: Finding Your Perfect Rental Home  
**Team Members:**
- **Vidya Prasunna** (Team Leader) – Full Stack Developer (Frontend, Backend, DB, Deployment)  
- **Botla Veerendra** – Full Stack Developer (Frontend, Backend, DB, Deployment)  
- **Bonam Chandra Durga Gowri Shankar** – Full Stack Developer (Frontend, Backend, DB, Deployment)

---

## 🌐 2. Project Overview

### 🔍 Purpose
To make the house renting process smooth and digital by connecting property owners and tenants through an intuitive and scalable web platform.

### ✨ Features
- User Authentication (Renter, Owner, Admin)
- Property Listings with Images and Descriptions
- Search & Filter (location, price, type, bedrooms)
- Owner Property Management (Add/Edit/Delete Listings)

---

## ⚙️ 3. Architecture

### 🖥 Frontend (React)
- Built using **ReactJS**
- **React Router** for navigation
- **Axios** for API communication
- UI Libraries: **Bootstrap**, **Material UI**

### ⚙️ Backend (Node.js + Express)
- RESTful APIs with **Express.js**
- **JWT-based authentication**
- Role-based middleware for secure access

### 🗃 Database (MongoDB)
- Collections: `users`, `properties`, `bookings`, `messages`

---

## 🛠️ 4. Setup Instructions

### 🔧 Prerequisites
- Node.js (v18+)
- MongoDB
- npm or yarn

### 📥 Installation Steps
bash
git clone https://github.com/Shankars57/SB-House
cd househunt
🚀 Frontend Setup
bash
Copy
Edit
cd client
npm install
🛡️ Backend Setup
bash
Copy
Edit
cd server
npm install
📄 Environment Variables (.env in server)
env
Copy
Edit
MONGO_DB = 'mongodb://127.0.0.1:27017/'
JWT_KEY = '12345'
PORT = 8001

📁 5. Folder Structure
Client Folder:
pgsql
Copy
Edit
client/
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── context/
│   ├── App.js
│   └── index.js
Server Folder:
pgsql
Copy
Edit
server/
├── controllers/
├── models/
├── routes/
├── middleware/
├── config/
├── server.js
🏃‍♂️ 6. Running the Application
Frontend
bash
Copy
Edit
cd client
npm start
Backend
bash
Copy
Edit
cd server
npm start
📡 7. API Documentation
Endpoint	Method	Description
/api/auth/register	POST	Register a new user
/api/auth/login	POST	Login user
/api/properties/	GET	Get all properties
/api/properties/:id	GET	Get single property
/api/bookings/	POST	Create a booking
/api/bookings/user	GET	Get bookings for a renter
/api/bookings/owner	GET	Get bookings for an owner

🔐 8. Authentication
JWT-based authentication

Role-based access using middleware

Tokens stored in localStorage and attached in headers

🎨 9. User Interface
Clean and responsive UI

Search & filter properties

Booking submission forms

Role-based dashboards

🧪 10. Testing
Tools Used:
Postman (API testing)

Manual end-to-end flow testing

📸 11. Screenshots / Demo
GitHub Repo: https://github.com/Shankars57/SB-House

Live Demo: https://house-rental-project-tqa3.vercel.app/

🐞 12. Known Issues
No real-time chat yet

No support for multiple image uploads

Mobile responsiveness needs improvement

🚀 13. Future Enhancements
Real-time messaging using Socket.IO

Push/email notifications

Online payment integration

Auto-generated lease contracts

Analytics dashboard for Admin

Built with ❤️ by Team HouseHunt – 2025