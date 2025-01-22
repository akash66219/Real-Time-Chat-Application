# Chatting App (MERN Stack)

## Overview
This is a full-stack real-time chat application built using the **MERN** (MongoDB, Express.js, React.js, Node.js) stack with **Socket.io** for real-time communication.

## Features
- User authentication (Signup/Login)
- Real-time messaging with WebSockets (Socket.io)
- Conversations list with recent messages
- Secure JWT authentication
- Responsive UI with TailwindCSS & DaisyUI

## Tech Stack
### Frontend
- **React.js** (with Vite for fast builds)
- **TailwindCSS** for styling
- **React Router** for navigation
- **Zustand** for state management
- **Socket.io-client** for real-time communication

### Backend
- **Node.js & Express.js** for server-side logic
- **MongoDB & Mongoose** for database management
- **JWT Authentication** for security
- **Socket.io** for real-time messaging

## Installation & Setup
### Prerequisites
Ensure you have the following installed:
- **Node.js** (v16 or later)
- **MongoDB** (locally or use MongoDB Atlas)

### Steps to Run the Project
1. **Clone the repository**
   ```sh
   git clone https://github.com/your-username/rahul5403-chatting_app_mern.git
   ```

2. **Setup the backend**
   ```sh
   cd backend
   npm install
   npm run server
   ```

3. **Setup the frontend**
   ```sh
   cd frontend
   npm install
   npm run dev
   ```

4. **Run the application**
   Open [http://localhost:3000](http://localhost:3000) in your browser.

## Environment Variables
Create a `.env` file in the `backend` directory and add the following:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

## Project Structure
```
rahul5403-chatting_app_mern/
├── backend/
│   ├── controllers/
│   ├── db/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── socket/
│   ├── utils/
│   ├── server.js
│   └── .env.example
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── context/
│   ├── zustand/
│   ├── tailwind.config.js
│   ├── vite.config.js
│   ├── package.json
│   └── public/
├── package.json
└── README.md

