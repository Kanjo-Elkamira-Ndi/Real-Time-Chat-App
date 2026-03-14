forked and reviewed by sirrirosenforbi 
# 💬 Full-Stack Real-Time Chat Application
# Full-Stack Chat App with Authentication & Email Notifications ✨
<p align="center">

![Node.js](https://img.shields.io/badge/Node.js-Backend-green)
![Express](https://img.shields.io/badge/Express.js-Framework-black)
![React](https://img.shields.io/badge/React-Frontend-blue)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green)
![Socket.io](https://img.shields.io/badge/Socket.io-Realtime-black)
![License](https://img.shields.io/badge/License-MIT-yellow)

</p>
A modern real-time messaging platform built with the <b>MERN stack</b>, featuring secure authentication, WebSocket communication, media sharing, and email integration.

---

# 📌 Project Overview

This project is a **full-stack real-time chat application** designed to demonstrate modern web development practices including secure authentication, real-time communication, state management, and scalable backend architecture.

The platform allows users to:

* Register and authenticate securely
* Send and receive messages instantly
* view online/offline presence of other users
* upload and share images
* receive automated welcome emails

The application was built with **scalability, modular architecture, and developer best practices in mind**, making it suitable as a foundation for larger messaging systems.

---

# ✨ Key Features

### 🔐 Authentication & Security

* Custom **JWT-based authentication**
* Secure password handling
* Protected API routes
* Authentication without third-party auth providers

### 💬 Real-Time Messaging

* **Instant chat messaging** powered by **Socket.io**
* Message synchronization across clients
* Real-time event handling

### 🟢 User Presence

* Online/offline status indicators
* Real-time presence tracking

### 🔔 Notifications

* Message notification sounds
* Typing sound indicators
* Toggleable notification settings

### 📨 Email Integration

* Automatic **welcome emails** sent on account registration
* Powered by **Resend Email API**

### 🖼️ Media Uploads

* Image upload support
* Cloud storage integration via **Cloudinary**

### 🚦 API Protection

* API **rate limiting**
* Bot/spam protection using **Arcjet**

### 🎨 Modern UI

* Responsive UI built with:

  * **React**
  * **Tailwind CSS**
  * **DaisyUI**

### 🧠 State Management

* Lightweight state management using **Zustand**


### 🚀 Deployment Ready

* Supports deployment on **free-tier hosting services**
* Backend and frontend can be deployed independently

---

# 🛠️ Technology Stack

## Frontend

* **React.js**
* **Tailwind CSS**
* **DaisyUI**
* **Zustand**
* **Socket.io Client**

## Backend

* **Node.js**
* **Express.js**
* **Socket.io**
* **MongoDB**
* **Mongoose**

## External Services

* **Cloudinary** → Image Storage
* **Resend** → Email Services
* **Arcjet** → Rate Limiting & API Protection

---

# 🧱 System Architecture

```
Frontend (React)
       │
       │ REST API
       ▼
Backend (Node.js + Express)
       │
       ├── MongoDB (Database)
       ├── Socket.io (Real-time messaging)
       ├── Cloudinary (Image storage)
       ├── Resend (Email service)
       └── Arcjet (API rate limiting)
```


---

# 🧪 Environment Variables

Create a `.env` file in the **backend directory**.

## Backend (`/backend`)

```bash
PORT=3000

MONGO_URI=your_mongo_uri_here

NODE_ENV=development

JWT_SECRET=your_jwt_secret

RESEND_API_KEY=your_resend_api_key
EMAIL_FROM=your_email_from_address
EMAIL_FROM_NAME=your_email_from_name

CLIENT_URL=http://localhost:5173

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

ARCJET_KEY=your_arcjet_key
ARCJET_ENV=development
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/Kanjo-Elkamira-Ndi/Real-Time-Chat-App.git
cd chat-app
```

---

## 2️⃣ Install Backend Dependencies

```bash
cd backend
npm install
```

Run the backend server:

```bash
npm run dev
```

---

## 3️⃣ Install Frontend Dependencies

```bash
cd frontend
npm install
```

Run the frontend development server:

```bash
npm run dev
```

---

# 🌐 Running the Application

After starting both servers:

Frontend:

```
http://localhost:5173
```

Backend API:

```
http://localhost:3000
```

---

# 🚀 Deployment

This application can be deployed using free-tier platforms.

### Recommended Stack

Frontend

* **Vercel**
* **Netlify**

Backend

* **Render**
* **Railway**
* **Sevalla**

Database

* **MongoDB Atlas**

---

# 📸 Screenshots (Will Be Added Soon)

* Chat interface
* Login/Register pages
* Real-time messaging
* Image sharing


---

# 🤝 Contributing

Contributions are welcome!

If you'd like to improve this project:

1. Fork the repository
2. Create a new branch

```
git checkout -b feature/new-feature
```

3. Commit your changes

```
git commit -m "Add new feature"
```

4. Push to your branch

```
git push origin feature/new-feature
```

5. Open a Pull Request

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👨‍💻 Author

# Kanjo Elkamira Ndi
