# E-Commerce Web Application – Spring Boot

## 📌 Project Overview
This project is a complete **E-commerce web application** developed using **Spring Boot**.  
The objective of this project is to understand how a real e-commerce system works, from backend services to frontend interaction, while respecting clean architecture and separation of concerns.

The application allows managing **users, products, and orders** with full CRUD operations and a clear workflow between frontend and backend.

---

## 🏗️ Architecture
The project follows a **backend + frontend architecture**.

### Backend
The backend is built with **Spring Boot** and organized into independent services:
- **User Service**: manages users and profiles
- **Product Service**: manages product catalog and inventory
- **Order Service**: manages orders and order history
- **API Gateway**: acts as a single entry point for all requests

Each service has its **own PostgreSQL database**, ensuring data isolation and better maintainability.  
All requests pass through the **API Gateway**.

### Frontend
The frontend is a **simple React (Vite) application** that communicates with the backend using REST APIs.  
It provides basic interfaces for managing users, products, and orders.

---

## 🛠️ Technologies Used
### Backend
- Java
- Spring Boot
- Spring MVC
- Spring Cloud
- Spring Data JPA / Hibernate
- REST APIs
- PostgreSQL

### Frontend
- React 18
- Vite
- Axios

### DevOps & Tools
- Docker
- Docker Compose
- Bash Scripts
- Git & GitHub

---

## ✨ Features
- CRUD operations for users, products, and orders
- API Gateway routing
- Independent databases per service
- Frontend visualization of data
- Containerized backend using Docker
- Simple and clean user interface
- Modular and scalable architecture

---

## 🧑‍💻 Application Modules

### 👤 User Management
- View all users
- Add new users
- Display user information in real time

### 📦 Product Management
- View all products
- Add new products
- Manage inventory and pricing

### 🛒 Order Management
- View orders
- Create new orders by selecting users and products
- Display order details

---

## 🐳 Containerization
The entire backend is **fully containerized** using Docker.  
To simplify development, automated scripts are provided:

- **Build Script**: builds Docker images
- **Start Script**: runs all services
- **Stop Script**: stops containers
- **Clean Script**: removes containers and images

The project can be launched with a **single command**.

---

## ▶️ How to Run the Project

### Prerequisites
- Java JDK
- Docker & Docker Compose
- Node.js
- PostgreSQL

### Steps
1. Clone the repository
2. Run the build script
3. Start all services
4. Access:
   - API Gateway: `http://localhost:8080`
   - Frontend: `http://localhost:8084`

---

## ⏳ Current Status

### ✅ Completed
- Backend CRUD operations
- API Gateway configuration
- Docker containerization
- Frontend display for users, products, and orders
- Database separation per service

### ❌ Not Completed Yet
- Frontend update and delete operations
- Advanced search and filtering
- Authentication and authorization

---

## 🎯 Project Goal
The goal of this project is to apply:
- Spring Boot and REST APIs
- Microservices architecture
- Database integration
- Frontend-backend communication
- DevOps basics with Docker

This project is **scalable and extendable** and can be enhanced with payment systems, authentication, or analytics.

---

## 👩‍💻 Author
**Nada Fethi**

