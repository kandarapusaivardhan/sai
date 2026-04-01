# 🎓 SkillForge

SkillForge is a full-stack web application designed to manage courses, subjects, and student learning efficiently. It provides user authentication, course management, and structured learning modules.

---

## 🚀 Features

* 👤 User Registration & Login (JWT Authentication)
* 📚 Course Management
* 📖 Subject Management
* 🔐 Secure Backend APIs
* 🌐 Frontend UI for interaction
* 🗄️ MySQL Database Integration

---

## 🛠️ Tech Stack

### Frontend

* React.js
* HTML, CSS, JavaScript

### Backend

* Spring Boot
* Java
* Maven

### Database

* MySQL

---

## 📂 Project Structure

skillforge/
│
├── backend/
│   ├── src/
│   ├── pom.xml
│
├── frontend/
│   ├── src/
│   ├── package.json
│
└── database/

---

## ⚙️ Installation & Setup

### 🔹 Backend (Spring Boot)

1. Open terminal in backend folder

2. Run:
   mvn spring-boot:run

3. Server runs on:
   http://localhost:8080

---

### 🔹 Frontend (React)

1. Open terminal in frontend folder

2. Run:
   npm install
   npm start

3. Runs on:
   http://localhost:3000

---

### 🔹 Database (MySQL)

* Create database:
  CREATE DATABASE skillforge;

* Update application.properties:
  spring.datasource.url=jdbc:mysql://localhost:3306/skillforge
  spring.datasource.username=root
  spring.datasource.password=your_password

---

## 📌 API Example

* POST /register → Register user
* POST /login → Login user
* GET /courses → Fetch courses

---

## 🎯 Project Objective

The goal of SkillForge is to build a scalable learning platform that allows users to manage and access educational content efficiently.

---

## 👨‍💻 Author

Sai

---

## 📜 License

This project is licensed under the MIT License.
