# SwiftTalk 💬⚡

SwiftTalk is a real-time chat application with a modern frontend and a scalable backend architecture.  
It is built with a **client–server setup**, designed for speed, simplicity, and real-time communication.

---

## 🚀 Features

- Real-time messaging
- Modern and responsive UI
- Client–server architecture
- Environment-based configuration
- Scalable backend setup
- Clean project structure

---

## 🛠️ Tech Stack

### Frontend (Client)
- React
- Vite
- JavaScript
- CSS / Tailwind (if applicable)

### Backend (Server)
- Node.js
- Express.js
- Socket.IO
- MongoDB

---

## 📂 Project Structure
```bash
SwiftTalk/
│
├── client/ # Frontend (React + Vite)
│ ├── src/
│ ├── public/
│ ├── .env.example
│ └── package.json
│
├── server/ # Backend (Node + Express)
│ ├── controllers/
│ ├── routes/
│ ├── models/
│ ├── .env.example
│ └── package.json

```
## ⚙️ Environment Setup

Create `.env` files using the provided `.env.example` files:

- `server/.env.example`
- `client/.env.example`

Copy each `.env.example` to `.env` and fill in the required values.

## ▶️ How to Run Locally

### 1️⃣ Install dependencies
```bash
cd server && npm install
cd ../client && npm install
```
### 2️⃣ Start the servers
### Backend
```bash
cd server
npm run server
```

### Client
```bash
cd client
npm run dev
```
