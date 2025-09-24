# 🛒 Node.js E-Commerce RESTful API

This project is a **Full E-Commerce RESTful API** built with **Node.js, Express, and MongoDB (Mongoose)**.  
It provides all the essential backend features needed for an online store, including authentication, product management, orders, and payments.

---

## 🚀 Features

- **User Authentication & Authorization** (JWT-based, with roles: Admin, Manager, User).
- **Categories & Subcategories** CRUD operations.
- **Brands & Products** management with filtering, sorting, and pagination.
- **Image Upload & Processing** (single/multiple uploads using Multer & Sharp).
- **Product Reviews & Ratings** system.
- **Wishlist & User Addresses** management.
- **Coupons & Shopping Cart** with discount handling.
- **Orders & Payments** (Cash on Delivery & Online Payments with Stripe).
- **Advanced Error Handling** and Validation Layer.
- **Security Enhancements** (Rate limiting, HPP, CORS, Helmet, etc).
- **Deployment Ready** for cloud platforms.

---

## 🛠️ Tech Stack

- **Node.js** (v16+)
- **Express.js**
- **MongoDB & Mongoose**
- **Multer & Sharp** for image handling
- **JWT** for authentication
- **Stripe API** for online payments
- **Nodemailer** for email notifications

---

├── config/ # Database and environment configs
├── controllers/ # Route controllers
├── middlewares/ # Custom middleware (auth, error handling, etc.)
├── models/ # Mongoose models
├── routes/ # Express routes
├── utils/ # Helper functions
├── server.js # Main server entry point
└── package.json


---

## ⚡ Getting Started

1. **Clone the repo**
   ```bash
   git clone https://github.com/medo-hussein/Node.js_Ecommerce_Api.git
   cd Node.js_Ecommerce_Api


Install dependencies

npm install


Setup environment variables
Create a config.env file in the root directory with the following:

PORT=5000
NODE_ENV=development
DB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET=your_stripe_secret


Run the server

npm run start:dev

📌 API Documentation

👉 Full API documentation is available via Postman collection (to be added).
## 📂 Project Structure

