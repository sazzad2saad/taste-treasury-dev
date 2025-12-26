# **Flavixor** 🥘🍴

**A Full-Stack Restaurant Management Platform**

## Video Demo

🎥 [https://youtu.be/oVijqiSfP3A](https://youtu.be/oVijqiSfP3A)

## Live Deployment

* 🌐 **Frontend**: [https://flavixor.netlify.app/](https://flavixor.netlify.app/)
* 🔗 **Backend API**: [https://taste-treasury-server.onrender.com/](https://taste-treasury-server.onrender.com/)

---

## 📌 Description

**Flavixor** is a full-stack web application developed as the **Final Project for CS50x**.
It is designed to modernize restaurant management by providing a seamless experience for both **customers** and **administrators**.

Customers can browse menus, explore food items, and enjoy a responsive, visually engaging interface with light/dark mode support. Administrators can securely manage menus, track orders, and control platform content through a protected admin system.

The project demonstrates my understanding of **frontend development, backend APIs, authentication, databases, and full-stack integration**, all built using modern web technologies.

---

## 🧱 Project Structure

```
flavixor/
├── README.md              # Main CS50 documentation
├── flavixor-client/       # Frontend (React)
└── flavixor-server/       # Backend (Node + Express)
```

---

## ✨ Key Features

### 👤 User & Admin Features

* Secure user authentication using **Firebase + JWT**
* Role-based admin access
* Cookie-based session handling

### 🖥️ Frontend

* Fully responsive UI (mobile, tablet, desktop)
* Dark / Light mode toggle
* Smooth animations with Framer Motion & React Awesome Reveal
* SEO optimization using React Helmet
* Axios Secure for protected API requests

### ⚙️ Backend

* RESTful API using Express.js
* MongoDB Atlas database integration
* CRUD operations for menus and orders
* JWT-based authentication
* CORS-enabled secure API communication

---

## 🛠️ Technologies Used

### Frontend

* React.js
* Tailwind CSS
* React Router DOM
* Firebase Authentication
* Axios & Axios Secure
* Framer Motion

### Backend

* Node.js
* Express.js
* MongoDB Atlas
* JWT Authentication
* Cookie Parser
* dotenv

---

## 🚀 How to Run the Project Locally

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/sazzad2saad/flavixor-dev.git
cd flavixor-dev
```

---

### 2️⃣ Run Backend Server

```bash
cd flavixor-server
npm install
```

Create a `.env` file:

```env
DB_USER=your_mongo_user
DB_PASS=your_mongo_password
JWT_SECRET=your_jwt_secret
PORT=5000
```

Start the server:

```bash
npm start
```

Backend runs on: `http://localhost:5000`

---

### 3️⃣ Run Frontend Client

```bash
cd ../flavixor-client
npm install
npm run dev
```

Frontend runs on: `http://localhost:5173`

---

## 📈 Future Improvements

* Online payment integration (Stripe / PayPal)
* AI-based food recommendations
* Multi-language support
* Real-time order & inventory updates

---

## 👨‍💻 About the Developer

Built with 💻 and dedication by **Sazzadur Rahman Saad**
as part of **CS50x – Introduction to Computer Science**.

* GitHub: [https://github.com/sazzad2saad](https://github.com/sazzad2saad)

---

## 🏁 Final Notes

This project represents my understanding of:

* Frontend & backend separation
* REST APIs
* Authentication & security
* Database-driven applications
* Full-stack deployment

**Flavixor is submitted as my CS50x Final Project.**

---
