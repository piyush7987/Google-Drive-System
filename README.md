# Google Drive System 🚀

A full-stack Google Drive clone built with **React** on the frontend and **Spring Boot (Java)** on the backend, using **MySQL** as the database.

---

## 🔧 Tech Stack

### 💻 Frontend
- React.js
- Axios
- CSS (custom or framework)

### ⚙️ Backend
- Java
- Spring Boot
- Spring Data JPA
- REST APIs

### 🗄️ Database
- MySQL

---

## 📁 Folder Structure

Google-Drive-System/
├── frontend/ # React.js frontend
├── backend/ # Spring Boot backend
└── README.md # Project instructions

---

## 🚀 Getting Started

### 🧩 Prerequisites

- Node.js & npm (for frontend)
- Java 17+ (for backend)
- MySQL Server

---

### 📦 Run Frontend

```bash
cd frontend
npm install
npm start

🛠️ Run Backend
Open the backend folder in your IDE

Configure MySQL in src/main/resources/application.properties:


spring.datasource.url=jdbc:mysql://localhost:3306/your_db_name
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update

Then run the application using:

```bash
./mvnw spring-boot:run

Or run DriveBeApplication.java directly in your IDE.

✨ Features
📁 Upload and manage files

🧠 Google Drive-like user interface

💾 File metadata stored in MySQL

🔄 REST API support with Spring Boot


