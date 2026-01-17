# E-Commerce Web Application – Spring Boot

## Project Overview
Complete **E-commerce web app** using **Spring Boot** with microservices architecture.  
Manages **users, products, and orders** with full CRUD.  
*Developed for educational purposes.*

## Architecture

### Backend
- **User Service** – manage users & profiles  
- **Product Service** – manage product catalog & inventory  
- **Order Service** – manage orders & history  
- **API Gateway** – single entry point for requests  
- Each service has its **own PostgreSQL database**.  
- All requests go through **API Gateway**.

### Frontend
- **React (Vite)** app communicating via REST APIs  
- Simple interface for users, products, orders  

## Technologies Used
- **Backend:** Java, Spring Boot, Spring MVC, Spring Data JPA/Hibernate, REST APIs, PostgreSQL  
- **Frontend:** React 18, Vite, Axios  
- **DevOps:** Basic Docker containerization  

## Features
- CRUD operations for users, products, orders  
- API Gateway routing  
- Independent databases per service  
- Frontend visualization of data  
- Basic Docker containerization  

## Application Modules
- **User Management:** view/add users, display info  
- **Product Management:** view/add products, manage inventory  
- **Order Management:** view/create orders  

## How to Run
### Prerequisites
Java JDK, Docker, Node.js, PostgreSQL  

### Steps
1. Clone repository  
2. Run build script  
3. Start all services  
4. Access:  
   - API Gateway: `http://localhost:8080`  
   - Frontend: `http://localhost:8084`  

## Current Status
**Completed:** backend CRUD, API Gateway, frontend display, databases per service  
**Not Completed:** frontend update/delete, search/filter, authentication  

## Project Goal
Practice advanced Spring Boot concepts: REST APIs, microservices, database integration, frontend-backend communication.  
Project is modular, scalable, ready to extend with auth, search, or analytics.

## Author
**Nada Fethi**


