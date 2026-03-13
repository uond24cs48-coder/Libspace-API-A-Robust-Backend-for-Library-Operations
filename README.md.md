# 📚 LibSpace - Library Management System (Backend)

LibSpace is a robust backend application built with **Node.js**, **Express**, and **MongoDB**. It handles user authentication and library book management with secure token-based access.

## 🚀 Features
* **User Management:** Register, Login, and Secure Logout (with Token Blacklisting).
* **Book Management:** Add new books, view all books, and delete books.
* **Security:** JWT (JSON Web Token) for authentication and Middleware for protected routes.
* **Database:** Scalable data storage using MongoDB Atlas.

---

## 🛠️ Tech Stack
* **Backend:** Node.js, Express.js
* **Database:** MongoDB (Mongoose ODM)
* **Authentication:** JWT, Bcrypt (Password Hashing)

---

## 📂 Project Structure
```text
LibSpace/
├── controllers/    # Logic for Users and Books
├── models/         # Database Schemas (User, Book, Blacklist)
├── routes/         # API Endpoints
├── middleware/     # Auth & Validation
└── index.js        # Main Server entry point
API Endpoints
​👤 User Routes
Method Endpoint Description
POST /api/auth/register Create a new account
POST /api/auth/login Login and get Token
POST /api/auth/logout Logout
Book Routes (Protected)Method Endpoint Description
POST /api/book/add Add a new book
GET /api/book/ Get list of all books
DELETE /api/book/:id Delete a specific book
​Clone the repository.
​Run npm install to install dependencies.
​Create a .env file and add your MONGO_URI and JWT_SECRET.
​Start the server using npm run dev.
developed by gowri