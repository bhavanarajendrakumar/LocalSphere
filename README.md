# 🌍 LocalSphere

LocalSphere is a MERN-stack hyperlocal commerce platform that connects local vendors and buyers through a secure and user-friendly digital marketplace. The platform enables nearby vendor discovery, product management, group buying, price negotiation, reviews and ratings, and role-based authentication, helping small businesses expand their digital presence.

---

## 🚀 Features

- 🔐 JWT-based User Authentication
- 🏪 Vendor Dashboard and Product Management
- 📍 Hyperlocal Vendor Discovery
- 🛒 Product Listings and Order Management
- 👥 Group Buying System
- 💬 AI-powered Price Negotiation
- ⭐ Reviews and Ratings
- 🗄️ MongoDB Database Integration
- 🌐 Responsive User Interface
- ⚡ MERN Stack Architecture

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

## 📸 Screenshots

### Home Page
<img width="1379" height="775" alt="image" src="https://github.com/user-attachments/assets/871edab4-5c41-484c-a521-05823c41c7fd" />


### Login Page
<img width="1379" height="775" alt="image" src="https://github.com/user-attachments/assets/485bbc82-e8ec-4c66-b148-a6514d0acde1" />


### Vendor Dashboard
<img width="1379" height="775" alt="image" src="https://github.com/user-attachments/assets/1285cc1f-b974-471e-958d-ae85ea7ef038" />


### Group Buy Page
<img width="1379" height="775" alt="image" src="https://github.com/user-attachments/assets/a3bf0579-2dbd-41fe-822b-4897b3dee53c" />


## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/bhavanarajendrakumar/LocalSphere.git
cd localsphere-v3
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
