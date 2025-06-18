# ChatApplication
Real-Time Distributed Chat Application
![chatApp_websockets](https://github.com/user-attachments/assets/c22cdc6f-65e8-49f0-8aa6-46ec3aeddeee)
# 💬 Real-Time Chat Bot (WhatsApp Clone)

![Chat Preview](./assets/chat-ui-preview.png)

A full-stack real-time chat application that replicates the WhatsApp experience using WebSockets. Built for speed, scalability, and responsiveness, this project demonstrates bi-directional communication, user authentication, and a sleek chat interface — ideal for production-scale messaging apps.

---

## 🚀 Features

- 🟢 Real-time bi-directional messaging via **WebSockets**
- 👥 User authentication and session management
- 🗨️ Typing indicators, message delivery status (sent, received)
- 📦 Scalable backend architecture using **Express** and **Socket.IO**
- 📱 Responsive chat UI with a modern, clean WhatsApp-like design
- 🔐 Secure login system with JWT or session cookies
- 🧠 Bot support for auto-replies or test interactions

---

## 🧠 Tech Stack

| Layer        | Technologies Used                                     |
|--------------|--------------------------------------------------------|
| Frontend     | React, TailwindCSS, Socket.IO Client                   |
| Backend      | Node.js, Express, Socket.IO Server                     |
| Database     | MongoDB (Mongoose), Redis (for socket session caching) |
| Auth         | JWT or Express Session                                 |
| Deployment   | Render / Vercel / Hostinger / Localhost (dev)          |

---

## 🛠️ Architecture Overview

```plaintext
Client (React + Socket.IO) ── WebSocket ──> Node.js Server (Socket.IO)
                                         └─> MongoDB (for users & messages)
                                         └─> Redis (for live socket tracking)
