# Expense Tracker App (MERN)

A full-stack expense tracking application built with MongoDB, Express, React, and Node.js.

## Tech Stack

- Frontend: React, React Router, Bootstrap, MUI
- Backend: Node.js, Express
- Database: MongoDB, Mongoose

## Prerequisites

- Node.js (v18+ recommended)
- npm
- MongoDB (local MongoDB service or MongoDB Atlas)

## Project Structure

- backend: Express API
- frontend: React app

## Setup and Run (Local)

### 1. Clone the repository

```bash
git clone https://github.com/Atharv3527/Expense-Tracker-App.git
cd Expense-Tracker-App
```

### 2. Install backend dependencies

```bash
cd backend
npm install
```

### 3. Create backend environment file

Create a file named .env inside the backend folder and add:

```env
PORT=5000
MONGO_URL=your_mongodb_connection_string
```

Examples:

- Local MongoDB: mongodb://localhost:27017/expense-tracker
- Atlas: mongodb+srv://username:password@cluster.mongodb.net/expense-tracker

### 4. Start backend server

```bash
npm run dev
```

Backend default URL: http://localhost:5000

### 5. Install frontend dependencies

Open a new terminal:

```bash
cd frontend
npm install
```

### 6. Start frontend server

```bash
npm run dev
```

Frontend default URL: http://localhost:3000
