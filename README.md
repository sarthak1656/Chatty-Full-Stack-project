# 💬 Chatty - Fullstack Real-time Chat Application

Welcome to **Chatty**, a modern fullstack chat app built with **MERN** and **Socket.io**, featuring real-time messaging, secure authentication, and cloud image upload support.

🌐 **Live App**: [chat-app-frontend-l6g2.vercel.app](https://chat-app-frontend-l6g2.vercel.app/login)

---

## 📸 Features

- 🔐 Authentication using JWT and HTTP-only cookies
- 💬 Real-time chat with Socket.io
- 🧠 Global state management with Zustand
- 📁 Cloudinary integration for profile image upload
- 🎨 Modern UI using React and Lucide Icons
- 🔔 Toast notifications with `react-hot-toast`

---


---

## 🚀 Tech Stack

- **Frontend**: React, Zustand, React Router, Axios, Socket.io-client
- **Backend**: Express.js, MongoDB, Mongoose, JWT, Bcrypt, Socket.io
- **Image Upload**: Cloudinary
- **Hosting**: Vercel (Frontend), Render (Backend or local)

---

## 📦 Backend Dependencies

| Package         | Purpose                                                                 |
|----------------|-------------------------------------------------------------------------|
| `express`       | Node.js web framework                                                   |
| `mongoose`      | ODM to interact with MongoDB                                            |
| `bcryptjs`      | Password hashing                                                        |
| `jsonwebtoken`  | JWT generation and verification for auth                                |
| `dotenv`        | Load environment variables                                              |
| `cors`          | Allow cross-origin requests                                             |
| `cookie-parser` | Parse cookies (used for JWT in cookies)                                 |
| `cloudinary`    | Upload/store images to Cloudinary                                       |
| `socket.io`     | Real-time communication                                                 |
| `nodemon`       | (Dev) Auto-restart server on changes                                    |

---

## 🎨 Frontend Dependencies

| Package                   | Purpose                                                         |
|---------------------------|-----------------------------------------------------------------|
| `react` & `react-dom`     | Core React packages                                             |
| `react-router-dom`        | SPA routing                                                     |
| `axios`                   | HTTP client for API calls                                       |
| `zustand`                 | Lightweight global state management                             |
| `socket.io-client`        | Real-time messaging from client side                            |
| `lucide-react`            | Icon library for UI                                             |
| `react-hot-toast`         | Toast notifications                                             |
| `browser-image-compression` | Compress images before uploading to Cloudinary              |

---

## 🛠️ Installation

### Backend

```bash
cd backend
npm install
npm run dev
```
###.env config
```bash
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

