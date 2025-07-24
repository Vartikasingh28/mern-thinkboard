# 📝 MERN ThinkBoard - Notes App

A full-stack Notes App built using the **MERN** stack (MongoDB, Express, React, Node.js). It allows users to create, read, and delete notes easily.

---

## 🚀 Features

- Create, Read, and Delete Notes
- React.js Frontend with Axios
- Node.js + Express.js Backend API
- MongoDB Database
- Clean UI & RESTful APIs

---

## 🛠 Tech Stack

- **Frontend**: React.js, Axios, Vite  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB Atlas  

---

## 📁 Folder Structure

mern-thinkboard/
├── backend/ # Express server
│ ├── models/
│ ├── routes/
│ └── server.js
├── frontend/ # React app
│ ├── components/
│ ├── pages/
│ └── main.jsx


---

## ⚙️ Getting Started

1. **Clone the repository**

```bash
git clone https://github.com/Vartikasingh28/mern-thinkboard.git
cd mern-thinkboard
Start Backend


cd backend
npm install
node server.js
Start Frontend


cd frontend
npm install
npm run dev
Make sure MongoDB connection string is correctly set in backend (in db.js or server.js).

📦 API Endpoints
GET /api/notes – Fetch all notes

POST /api/notes – Create a new note

DELETE /api/notes/:id – Delete a note

https://mern-thinkboard-4-spr6.onrender.com

https://mern-thinkboard-8.onrender.com
