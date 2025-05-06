# 🍽️ Zing Bites – Backend API

This is the backend API for **Zing Bites**, a food ordering web application. It handles user authentication, restaurant and menu data management, and interacts with a MongoDB database. Built with **Node.js**, **Express**, and **Mongoose**.

---

## 🚀 Deployed API

🔗 **Base URL**: [https://zing-bites-backend-v2.onrender.com](#)

---

## 📦 Features

- ✅ RESTful APIs
- 🔐 JWT-based Authentication (via **Auth0**)
- 🔓 Login with **Google**
- 📍 Restaurant and Menu Management
- 🔎 Search & Filter Restaurants by City, Cuisine, and more
- ☁️ Image Uploads using **Cloudinary**
- 🕒 Tracks creation & last updated timestamps

---

## 🔧 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/gitxAnkit/zing-bites-backend_v2.git
cd zing-bites-backend
```
### 2. Install Dependencies
```
npm install
```
### 3. Environment Variables

Rename .env.example to .env and fill in the appropriate values:
```
cp .env.example .env
```

### ▶️ Running Locally
```
npm run dev
```

The server will run at http://localhost:7000 by default.