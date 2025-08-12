# 🏋️‍♂️ Workout Tracker (MERN Stack)

A simple **Exercise Tracking Application** built using the **MERN Stack**.  
This project demonstrates the fundamentals of a full-stack web application without authentication initially, focusing on CRUD operations, data flow, and the interaction between frontend and backend.  

Later, features like **user authentication** (signup, login, logout, protected routes) can be added in an advanced version.

---

## 🚀 Features

- ➕ **Add Exercises** – Log your workouts with relevant details.
- 📋 **View Exercises** – See a list of your past workouts.
- ✏ **Edit Exercises** – Update workout details anytime.
- ❌ **Delete Exercises** – Remove workouts you no longer want to track.
- 🔄 **Real-Time UI Updates** – Frontend updates automatically when data changes.
- 🛡 **Secure Architecture** – Backend acts as a shield between frontend and database.

---

## 🛠 Tech Stack

| Technology  | Purpose |
|-------------|---------|
| **MongoDB** | NoSQL database to store workouts and user data. |
| **Express.js** | Backend framework to handle API requests and routing. |
| **React.js** | Frontend library to build the interactive user interface. |
| **Node.js** | Runtime environment for executing backend JavaScript code. |

---

## ⚙ How It Works

1. **Frontend (React)**  
   - Renders the UI and manages navigation between pages.  
   - Sends API requests (e.g., add/view exercises) to the backend.

2. **Backend (Node.js + Express)**  
   - Receives requests from the frontend.  
   - Processes them, interacts with the database, and returns responses.

3. **Database (MongoDB)**  
   - Stores all exercise data securely.  
   - Backend fetches, updates, and deletes data here.

---

## 🔄 Data Flow

1. 🧑 User interacts with the **React frontend**.  
2. 🔗 React sends a request to the **Express backend**.  
3. 📦 Backend interacts with **MongoDB** to get/update data.  
4. 📬 MongoDB sends data back to the backend.  
5. 🎨 Backend sends the data to the frontend.  
6. ⚡ React updates the UI dynamically.

---

## 📂 Project Structure

```bash
workout-tracker/
├── backend/         # Node.js + Express API
│   ├── models/      # Mongoose models
│   ├── routes/      # API route handlers
│   └── server.js    # Entry point for backend
├── frontend/          # React frontend
│   ├── src/         # React components & pages
│   ├── public/      # Static assets
│   └── package.json # Frontend dependencies
└── README.md
