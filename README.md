# Noon E-Commerce RESTful API 🛒

### Production-Ready Back-End for Online Stores  ✅
> A scalable and modular e-commerce back-end API built with **Node.js**, **Express.js**, and **MongoDB** — fully implemented and developed by me as a complete back-end solution for online shopping platforms.

---

## 🚀 Overview

This project provides a robust RESTful API for managing users, products, orders, payments, and more — following modern development practices including:

- Clean architecture & modular structure
- Secure authentication & authorization
- File/image handling with Sharp
- Payment integration with Stripe
- Complete cart, orders, and review systems

---

## 📦 Key Features

### 🔐 User Authentication & Authorization
- User registration, login, and password reset (via email)
- JWT-based access with roles (admin, manager, user)
- Authorization middleware for route protection

### 🛍️ Product Management
- Full CRUD for products, categories, subcategories, and brands
- Filtering by price, rating, category, brand, etc.
- Sorting, searching, and pagination

### 🖼️ Image Upload & Optimization
- Upload single or multiple product images using Multer
- Automatic resizing and compression using Sharp
- File validation and error handling

### ⭐ User Interaction
- Users can add/edit/delete product reviews
- Average rating and review count calculated per product
- Wishlist functionality: add/remove products
- Address book support for users

### 🛒 Cart & Coupons
- Add items to cart and update quantities
- Apply discount coupons with expiration & limits
- Auto-calculate subtotal, total, discounts

### 💳 Orders & Payments
- Place orders using Cash on Delivery or Stripe
- Validate and process Stripe payments
- Update order status (e.g., paid, delivered)

### 🔐 Security Enhancements
- Rate limiting, input sanitization, HPP protection
- Helmet for HTTP headers
- Centralized error handling with custom error classes

### 📁 Clean Code Structure
- Separation of concerns (controllers, models, services, routes, etc.)
- Reusable utilities (email handling, validation, error formatting)
- Environment-based configuration with `.env`

---

## 🧱 Tech Stack

| Layer           | Tech Used                            |
|------------------|----------------------------------------|
| Runtime          | Node.js                               |
| Framework        | Express.js                            |
| Database         | MongoDB + Mongoose                    |
| Authentication   | JWT                                   |
| File Uploads     | Multer + Sharp                        |
| Payments         | Paymob                                |
| Email Services   | Nodemailer                            |
| Security         | Helmet, express-rate-limit, hpp, mongo-sanitize |
| Validation       | Custom logic      |


