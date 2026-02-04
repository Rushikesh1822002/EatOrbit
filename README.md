# EatOrbit
EatOrbit is a full-stack web app for multi-stall food courts. Customers browse menus, place orders, pay online, and track status in real time. Vendors manage orders and update progress. Admin monitors stalls and activity. Built with React, Spring Boot REST APIs, and MySQL with role-based access.

# 🍽️ EatOrbit – Multi-Vendor Food Ordering Platform

EatOrbit is a **full-stack web application** designed for **multi-stall food courts and campus cafeterias**.  
It provides a centralized digital platform where customers can browse menus, place orders, make payments, and track order status in real time, while vendors and admins manage operations efficiently.

---

## 🚀 Features Overview

### 👤 Customer
- Browse food outlets and menus
- Add items to cart with quantity control
- Secure login and role-based access
- Place orders and simulate UPI QR payment
- Track order status in real time

### 🧑‍🍳 Vendor
- Vendor dashboard for order management
- View live incoming orders
- Update order status (Placed → Preparing → Ready)
- Manage menu items (add/update/enable/disable)
- Upload and manage UPI QR codes
- Toggle outlet availability (Open / Closed)

### 🛠️ Admin
- Admin dashboard for platform monitoring
- Approve or reject vendor registrations
- View and manage outlets and users
- Monitor overall system activity

---

## 🧩 Technology Stack

### Frontend
- React 18
- JavaScript (ES6+)
- HTML5 & CSS3
- Bootstrap 5
- Axios
- React Router DOM
- Context API (AuthContext & CartContext)
- Framer Motion

### Backend
- Java 17
- Spring Boot 3.x
- Spring Security with JWT
- Spring Data JPA
- MySQL
- Spring Mail
- Lombok

---

## 🏗️ Architecture Overview

- Frontend and backend are fully decoupled
- Communication via RESTful APIs (JSON)
- JWT-based stateless authentication
- Role-based routing and access control
- Clean separation of concerns

---

## 🔐 Authentication & Security

- JWT-based authentication
- Role-Based Access Control (Customer / Vendor / Admin)
- Protected frontend routes
- Backend validation via Spring Security
- Sensitive configuration excluded using `.gitignore`

---

## 🔄 API Integration

- Axios with centralized API service layer
- Request & response interceptors for JWT handling
- Proper error and loading state management
- Stateless communication for scalability

---

## 📂 Project Structure
EatOrbit/
│
├── frontend/ # React frontend
│
├── src/ # Spring Boot backend
│ ├── controller
│ ├── service
│ ├── repository
│ ├── entity
│ └── security
│
├── pom.xml
├── .gitignore
└── README.md


---

## 🧪 Database Design

- Normalized relational schema
- Achieved Third Normal Form (3NF)
- No partial or transitive dependencies
- Separate tables for users, roles, outlets, menus, orders, and order items

---

## 📌 Real-World Relevance

EatOrbit simulates a **real production-grade food ordering system**, similar to platforms like Swiggy or Zomato, adapted for **campus and food court environments**.

---

## 👨‍💻 Author

**Rushikesh**  
Full-Stack Developer (Java | Spring Boot | React)

---

## 📜 License

This project is developed for **academic and learning purposes**.
