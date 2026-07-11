# DECI
# 🛒 E-Commerce Backend API

## Project Overview

This project was developed as the **Semester Project** for the DECI (Digital Egypt Cubs Initiative) Backend Development track.

The goal of the project is to build a **fully functional E-Commerce Backend API** from scratch, applying all backend concepts learned throughout the course into a single, production-ready application.

The API provides the core functionality required for an online store, including user authentication, product management, shopping cart operations, order processing, and secure RESTful endpoints.

---

## Features

* 🔐 User Authentication & Authorization
* 👤 User Management
* 📦 Product Management (CRUD)
* 🛍️ Shopping Cart
* 📋 Order Management
* 🗂️ Category Management
* ✅ Input Validation
* ⚠️ Error Handling
* 🔒 Secure REST API
* 📄 JSON Responses

---

## Technologies Used

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* bcrypt
* dotenv

---

## Project Structure

```text
.
├── controllers/
├── middleware/
├── models/
├── routes/
├── utils/
├── config/
├── app.js
├── package.json
└── README.md
```

---

## Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/your-repository.git
```

2. Navigate to the project directory

```bash
cd your-repository
```

3. Install dependencies

```bash
npm install
```

4. Create a `.env` file and configure the required environment variables.

5. Start the development server

```bash
npm run dev
```

or

```bash
npm start
```

---

## API Endpoints

| Method | Endpoint           | Description         |
| ------ | ------------------ | ------------------- |
| POST   | /api/auth/register | Register a new user |
| POST   | /api/auth/login    | Login user          |
| GET    | /api/products      | Get all products    |
| GET    | /api/products/:id  | Get a product       |
| POST   | /api/products      | Create a product    |
| PUT    | /api/products/:id  | Update a product    |
| DELETE | /api/products/:id  | Delete a product    |
| GET    | /api/orders        | Get user orders     |
| POST   | /api/orders        | Create a new order  |

> **Note:** Endpoint names may vary depending on your implementation.

---

## Learning Objectives

This project demonstrates understanding of:

* RESTful API development
* Authentication and Authorization
* Database Design
* Backend Architecture
* Middleware
* CRUD Operations
* Error Handling
* API Security
* Environment Configuration

---

## Course Information

This project was completed as part of the **Digital Egypt Cubs Initiative (DECI)** Backend Development curriculum.

Project Brief:

> Build a complete server-side application for an online store by applying all backend concepts covered throughout the course into one cohesive, production-ready E-Commerce API.

---

## Author

**Adham Tamer**



GitHub: https://github.com/AdhamTTamer
