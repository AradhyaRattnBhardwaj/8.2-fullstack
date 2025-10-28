# 8.2-fullstack
# 🚀 Express Middleware Demo

A simple and well-structured **Express.js** project demonstrating the use of **custom middleware** for logging and authentication.

---

## 📋 Overview

This project showcases two core middlewares:
1. **Request Logger Middleware** – Logs every HTTP request with a timestamp, method, and URL.  
2. **Bearer Token Authentication Middleware** – Validates requests using a `Bearer mysecrettoken` token.

It includes both **public** and **protected** routes for easy testing.

---

## 🛠️ Setup Instructions

### 1️⃣ Install Dependencies
```bash
npm init -y
npm install express
```

### 2️⃣ Create the Server File
Save the server code as `server.js` (code already provided in this repo).

### 3️⃣ Run the Server
```bash
node server.js
```

Server will start at:  
👉 `http://localhost:3000`

---

## 🧪 Testing with cURL

### ✅ Test 1: Public Route (No Authentication)
```bash

