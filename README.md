# 🌱 Seed Entry Ecommerce Platform

A full-stack web-based e-commerce platform for buying and selling plant
seedlings.\
Developed for **CS 3332 -- Software Engineering, Troy University**.

------------------------------------------------------------------------

## 📌 Project Overview

This application allows users to:

-   Browse and search seedling products
-   Add products to cart
-   Place orders
-   Receive confirmation emails
-   Manage personal profile
-   View transaction history

The system follows a **Monolithic Three-Tier Architecture**:

-   **Frontend:** React.js
-   **Backend:** Spring Boot (Java)
-   **Database:** MySQL

------------------------------------------------------------------------

## 🚀 Tech Stack

### Backend

-   Java 21
-   Spring Boot 3.x
-   Spring Security + JWT
-   Spring Data JPA
-   JavaMailSender
-   Maven

### Frontend

-   React.js
-   React Router
-   Axios
-   CSS

### Database

-   MySQL 8

------------------------------------------------------------------------

## 🔐 Core Features

### 👤 Authentication

-   Register (Email & Password)
-   Login with JWT
-   Google OAuth Login
-   Refresh Token
-   Logout

### 🛍 Product Management

-   View product list
-   Search and filter by category/type
-   View product details

### 🛒 Shopping Cart

-   Add to cart
-   Update quantity
-   Remove items
-   Clear cart

### 📦 Order Processing

-   Create order from cart
-   Save Order, OrderItems, and Transaction
-   Send confirmation email

### 👤 Profile Management

-   View user info
-   Update personal details

### 💳 Transaction History

-   View past orders
-   Filter by status

------------------------------------------------------------------------

## 🏗 System Architecture

The application uses a **Three-Tier Monolithic Architecture**:

1.  Presentation Layer (React Frontend)
2.  Business Logic Layer (Spring Boot Backend)
3.  Data Layer (MySQL Database)

------------------------------------------------------------------------

## 🛠 How to Run Locally

### 1️⃣ Prerequisites

Make sure you have installed:

-   Node.js (v16+)
-   Java JDK 21+
-   Maven 3.8+
-   MySQL (via XAMPP recommended)
-   Visual Studio Code

------------------------------------------------------------------------

### 2️⃣ Clone Repository

``` bash
git clone https://github.com/DevFreshman/Group3.git
cd Group3
```

------------------------------------------------------------------------

### 3️⃣ Setup Database

-   Start MySQL (XAMPP)
-   Create a database (e.g., `seedling_store`)
-   Import SQL script from `/sql` folder

------------------------------------------------------------------------

### 4️⃣ Run Backend

``` bash
cd backend
mvn clean install
mvn spring-boot:run
```

Backend runs at:

    http://localhost:8080

------------------------------------------------------------------------

### 5️⃣ Run Frontend

``` bash
cd frontend
npm install
npm run dev
```

Frontend runs at:

    http://localhost:5173

------------------------------------------------------------------------

## ⚠️ Current Limitations

-   Local deployment only
-   No online payment integration
-   No admin dashboard
-   Limited input validation in some forms

------------------------------------------------------------------------

## 🚀 Future Improvements

-   Deploy to AWS / Render / Railway
-   Integrate Stripe / PayPal
-   Add Admin Dashboard
-   Implement Role-Based Access Control (RBAC)
-   Improve UI responsiveness for mobile

------------------------------------------------------------------------

## 👨‍💻 Team Members

-   Hoang Duc Manh -- Team Leader (Backend, Architecture)
-   Dinh Hoang Viet -- Frontend Developer
-   Le Minh Hanh -- API Testing & Documentation
-   Tran Trung Anh -- Testing & Email Service

------------------------------------------------------------------------

## 📚 References

-   Spring Boot Documentation
-   ReactJS Documentation
-   JWT (Auth0)
-   Postman
-   GitHub

------------------------------------------------------------------------

## 📂 Repository Structure

    /frontend   → React client
    /backend    → Spring Boot APIs
    /sql        → Database scripts

------------------------------------------------------------------------

## 📄 License

This project was developed for academic purposes (CS 3332 -- Software
Engineering).
