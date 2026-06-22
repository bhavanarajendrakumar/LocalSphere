# 🌍 LocalSphere

LocalSphere is a full-stack web application that connects users with local services and opportunities through a simple, structured, and secure platform. It includes authentication, service modules, and a Node.js + Express backend with MongoDB database integration and a modern frontend.

---

## 🚀 Features

- 🔐 User Registration & Login system (secure authentication)
- 🧑‍💻 Backend built with Node.js and Express.js
- 🗄️ MongoDB database integration
- 🌐 Frontend with HTML, CSS, and JavaScript
- 📂 Modular structure (frontend + backend separation)
- 🔑 Environment variables using `.env`
- ⚡ Lightweight and easy to run locally

---

## 🏗️ Tech Stack

**Frontend:**
- HTML5
- CSS3
- JavaScript

**Backend:**
- Node.js
- Express.js

**Database:**
- MongoDB

**Tools:**
- Git & GitHub
- dotenv

---

## 📁 Project Structure

```text
LocalSphere/
│
├── frontend/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   └── assets/
│
├── backend/
│   ├── server.js
│   ├── routes/
│   ├── models/
│   └── controllers/
│
├── package.json
├── package-lock.json
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/LocalSphere.git
cd LocalSphere
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment Variables

Create a `.env` file in the project root and add the required variables:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 4. Run the Application

```bash
npm start
```

The application will run at:

```text
http://localhost:5000
```

---

## 🔐 Authentication Flow

1. User registers an account.
2. User data is stored securely in MongoDB.
3. User logs in using registered credentials.
4. Backend validates the user.
5. Access is granted to the application dashboard.

---

## 🚀 Future Enhancements

- AI-powered recommendations
- Role-based access control
- Real-time notifications
- Improved UI/UX
- Cloud deployment

---

## 👩‍💻 Author

**Bhavana Rajendra Kumar**

---

## 📜 License

This project was developed for academic, learning, and demonstration purposes.
