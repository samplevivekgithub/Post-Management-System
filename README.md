📝 Blog Application System

(React + Spring Boot)

📌 Overview

The Blog Application System is a full-stack web application developed using React.js for the frontend and Spring Boot for the backend. It allows users to create, read, update, and delete blog posts through a secure and responsive interface. The application follows RESTful architecture and separates frontend and backend concerns clearly.

🎯 Features

User Registration & Login

JWT-based Authentication

Create Blog Posts

Edit & Update Blogs

Delete Blogs

View All Blogs

View Single Blog Details

User-specific Blog Dashboard

Responsive UI

REST API Integration

🛠️ Technologies Used
Frontend

React.js

JavaScript (ES6+)

HTML5

CSS3

React Router DOM

Axios

Backend

Spring Boot

Java

Spring REST

Spring Data JPA

Spring Security (JWT)

Database

MySQL

Tools

Maven

Postman

Git & GitHub

🧩 Application Modules
1. Authentication Module

User Registration

User Login

JWT Token Generation

Secure API Access

2. Blog Module

Create Blog

Update Blog

Delete Blog

View Blogs

View Blog by ID

3. User Module

User Profile

User-specific Blogs

⚙️ System Architecture

React handles UI and client-side routing

Spring Boot exposes REST APIs

JWT secures API communication

MySQL stores users and blog data

Axios handles frontend-backend communication

📂 Project Structure
Frontend (React)
blog-frontend/
│
├── src/
│   ├── components/
│   ├── pages/
│   │   ├── Login.js
│   │   ├── Register.js
│   │   ├── Home.js
│   │   ├── CreateBlog.js
│   │   └── BlogDetails.js
│   ├── services/
│   │   └── api.js
│   ├── App.js
│   └── index.js
│
└── package.json
Backend (Spring Boot)
blog-backend/
│
├── controller/
├── service/
├── repository/
├── model/
├── config/
├── BlogApplication.java
└── pom.xml🚀 How to Run the Project
Backend (Spring Boot)

Open backend project in IDE

Configure MySQL database in application.properties

Run:

mvn spring-boot:run

Backend runs on:

http://localhost:8080
Frontend (React)

Navigate to frontend folder

cd blog-frontend

Install dependencies

npm install

Start the server

npm start

Open browser:

http://localhost:3000
🔐 Security

JWT-based authentication

Password encryption

Protected APIs using Spring Security

Role-based access (optional)

📈 Future Enhancements

Comment System

Like & Share Feature

Blog Categories & Tags

Search & Filter Blogs

Admin Dashboard

Image Upload for Blogs

👨‍💻 Author

Vivekanand
BE – Computer Science
React & Spring Boot Developer
Aspiring Full Stack Engineer
