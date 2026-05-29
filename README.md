# AI Chatbot MERN App

An AI-powered chatbot web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The application allows users to interact with an intelligent chatbot in real time with authentication, chat history, and responsive UI.

---

# Features

* User Authentication (Login / Signup)
* AI-powered chat responses
* Real-time conversation interface
* Store chat history in MongoDB
* Responsive UI for mobile and desktop
* Secure API integration
* Modern React frontend
* REST API backend using Express.js
* Environment variable configuration

---

# Tech Stack

## Frontend

* React.js
* CSS / Tailwind CSS / Bootstrap
* Axios
* React Router DOM

## Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* bcrypt.js

## AI Integration

* OpenAI API / Gemini API / Any AI Model API

---

# Project Structure

```bash
AI-Chatbot-MERN/
│
├── client/                 # React Frontend
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/                 # Node Backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
├── .env
├── package.json
└── README.md
```

---

# Installation

## Clone Repository

```bash
git clone https://github.com/VaibhavAna/AI-Chatbot-MERN.git
```

```bash
cd AI-Chatbot-MERN
```

---

# Backend Setup

```bash
cd server
npm install
```

Create a `.env` file inside the server folder:

```env
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
OPENAI_API_KEY=your_api_key
```

Run backend server:

```bash
npm start
```

---

# Frontend Setup

```bash
cd client
npm install
```

Run frontend:

```bash
npm start
```

---

# API Endpoints

## Authentication

| Method | Endpoint           | Description   |
| ------ | ------------------ | ------------- |
| POST   | /api/auth/register | Register user |
| POST   | /api/auth/login    | Login user    |

## Chat

| Method | Endpoint          | Description       |
| ------ | ----------------- | ----------------- |
| POST   | /api/chat         | Send chat message |
| GET    | /api/chat/history | Get chat history  |

---

# Environment Variables

| Variable       | Description               |
| -------------- | ------------------------- |
| PORT           | Server Port               |
| MONGO_URI      | MongoDB Connection String |
| JWT_SECRET     | JWT Secret Key            |
| OPENAI_API_KEY | AI API Key                |

---

# Deployment

## Frontend Deployment

* Vercel

## Backend Deployment

* Render
  
## Database

* MongoDB Atlas

---

# Future Improvements

* Voice assistant support
* Dark mode
* Multi-language support
* Image generation support
* Chat export feature
* Real-time socket integration

---

# Contributing

Contributions are welcome.

1. Fork the project
2. Create a new branch
3. Commit changes
4. Push to branch
5. Open Pull Request

---

# Author

Vaibhav Anand
