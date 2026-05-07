# JWT Authentication System 🔐

A secure backend authentication system built with **Node.js, Express, MongoDB, and JWT**.
It includes user registration, login, password hashing, and protected routes.

---

## 🚀 Features

* User Registration
* User Login
* Password Hashing (bcrypt)
* JWT Authentication
* Protected Routes (middleware)
* Environment Variables support
* MongoDB database integration

---

## 🛠️ Tech Stack

* Node.js
* Express.js
* MongoDB
* Mongoose
* JSON Web Token (JWT)
* bcryptjs
* dotenv

---

## 📁 Project Structure

```
jwt-auth-system/
│
├── models/
├── routes/
├── middleware/
├── server.js
├── package.json
├── .env.example
└── README.md
```

---

## ⚙️ Installation & Setup

### 1. Clone the repo

```
git clone https://github.com/yourusername/jwt-auth-system.git
```

### 2. Install dependencies

```
npm install
```

### 3. Create `.env` file

Copy `.env.example` and create your own `.env`

```
PORT=3000
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 4. Run the server

```
npm start
```

or

```
nodemon server.js
```

---

## 🔐 API Endpoints

### Register User

```
POST /register
```

### Login User

```
POST /login
```

### Protected Route

```
GET /protected
```

---

## 📌 Security Note

* `.env` file is ignored for security reasons
* Use `.env.example` as reference only

---

## 👨‍💻 Author

Khizar Khan
Backend Developer (Intern)
