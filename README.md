# 🤖 Smart Chat AI – Fullstack Chatbot (React + Node.js + MongoDB + Gemini API)

A complete AI-powered Smart Chat Application built using **React.js (Frontend)** and  
**Node.js + Express.js (Backend)** with **MongoDB** for database and  
**Google Gemini API** for intelligent chat responses.

This project includes a modern UI, secure backend, authentication,  
and persistent chat history.

---

## 🚀 Features

### 🌐 Frontend Features
- Modern responsive UI using Tailwind CSS  
- Real-time AI chat interface  
- React Context API global state management  
- Smooth alerts using React Hot Toast  
- Persistent chat history  
- Clean scalable folder structure  

### 🔧 Backend Features
- Secure REST APIs (Node.js + Express.js)  
- MongoDB with Mongoose ODM  
- JWT Authentication  
- Google Gemini API integration  
- Save chats & messages  
- Nodemailer email service  
- Protected routes with middleware  

---

## 🛠 Tech Stack

### 🎨 Frontend
- React.js  
- Vite  
- Tailwind CSS  
- Axios  
- React Router DOM  
- React Hot Toast  

### ⚙️ Backend
- Node.js  
- Express.js  
- MongoDB  
- Mongoose  
- Nodemailer  
- JWT  
- Dotenv  

---

## 📂 Project Structure

SMART-CHATBOT/  
│  
├── Backend/  
│   ├── controllers/  
│   ├── database/  
│   ├── middlewares/  
│   ├── models/  
│   ├── routes/  
│   ├── .env  
│   ├── index.js  
│   ├── package.json  
│   └── package-lock.json  
│  
└── Frontend/  
    ├── public/  
    ├── src/  
    │   ├── components/  
    │   ├── context/  
    │   ├── pages/  
    │   ├── assets/  
    │   ├── App.jsx  
    │   ├── main.jsx  
    │   └── index.css  
    ├── index.html  
    ├── vite.config.js  
    ├── package.json  
    └── package-lock.json  

---

## 🔧 Backend Setup

### 1️⃣ Install Dependencies
cd Backend  
npm install

### 2️⃣ Create `.env`
PORT=5000  
Db_url=your_mongodb_url  
Password=your_email_password  
Gmail=your_gmail  
GEMINI_API_KEY=your_gemini_api_key  
Activation_sec=your_activation_secret  
Jwt_sec=your_jwt_secret  

### 3️⃣ Run Backend
npm run dev

Backend URL → http://localhost:5000

---

## 🎨 Frontend Setup

### 1️⃣ Install Dependencies
cd Frontend  
npm install

### 2️⃣ Add Base URL  
Inside `src/main.jsx`:
export const server = "http://localhost:5000";

### 3️⃣ Run Frontend
npm run dev

Frontend URL → http://localhost:5173

---

## 🤖 Gemini API (Secure Flow)

- Frontend sends request → Backend  
- Backend uses Gemini API key from `.env`  
- API key **never exposed** on UI  

Route used:
POST /api/gemini/generate

---

## 🖼️ Project Screenshot  
![Chat UI](./ai-chat.png)

---

## 👨‍💻 Developer
Built and customized by **Farhan Gheri** — Smart Chat AI Fullstack Project.
