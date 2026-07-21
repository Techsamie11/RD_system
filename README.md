
# RD Management System

A robust **Recurring Deposit (RD) Management System** developed using **Java**, **Spring Boot**, **Spring Data JPA**, **Hibernate**, and **PostgreSQL**. The application provides RESTful APIs for managing recurring deposit accounts, enabling efficient creation, retrieval, updating, and deletion of RD records. The project follows a layered architecture to ensure scalability, maintainability, and clean code practices.

---

## 📖 Project Overview

The RD Management System is designed to simplify the management of Recurring Deposit accounts by automating daily banking operations. It allows users to maintain customer RD records, track deposit details, update account information, and perform CRUD operations through RESTful APIs.

The application follows industry-standard software development practices using Spring Boot's MVC architecture, ensuring a modular and maintainable codebase.

---

## ✨ Features

- Create new Recurring Deposit (RD) accounts
- View all RD account details
- Search RD records by ID
- Update customer or deposit information
- Delete RD records
- RESTful API implementation
- Layered Architecture (Controller → Service → Repository)
- Database integration with PostgreSQL
- Exception handling for reliable API responses
- Maven-based dependency management
- Clean and structured project organization

---

## 🛠️ Tech Stack

### Backend
- Java
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate

### Database
- PostgreSQL

### Build Tool
- Maven

### API Testing
- Postman
- Swagger UI (if enabled)

### Version Control
- Git
- GitHub

---

## 📂 Project Structure

```
RD_System/
│
├── src/
│   ├── main/
│   │
│   ├── java/
│   │   ├── controller/
│   │   ├── service/
│   │   ├── repository/
│   │   ├── entity/
│   │   ├── dto/
│   │   ├── exception/
│   │   └── config/
│   │
│   └── resources/
│       ├── application.properties
│
├── pom.xml
├── README.md
└── .gitignore
```


