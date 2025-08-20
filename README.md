
---

## 🚀 Features

### 🔐 Authentication
- User **signup & login** with JWT
- Passwords stored securely with **bcrypt hashing**
- Access & Refresh token system

### 🛡️ Authorization
- Middleware to **protect routes**
- Only authenticated users can access certain APIs

### ⚡ Backend (Node.js + Express.js)
- Express server setup with REST API
- MongoDB (via Mongoose) for data storage
- JWT authentication & authorization
- Centralized error handling

### 🎨 Frontend (React + Tailwind)
- User registration & login forms
- Token storage in local storage
- Redirects for authenticated routes
- Logout functionality

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js, MongoDB, JWT, Bcrypt
- **Frontend:** React.js, Tailwind CSS
- **Others:** dotenv, nodemon, axios

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/harshaddesai04/JWT-auth.git
cd JWT-auth
```
### 2️⃣ Setup Backend
```bash
cd backend
npm install

Create a .env file in the backend/ folder:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

Run backend:
npm start
```
### 3️⃣ Setup Frontend
```bash
cd client
npm install
```
