<div align="center">

# Denys Demydovskyi

Computer Science Student at PJATK, Warsaw  
Backend-focused Full-Stack Developer (Java | Spring Boot | Node.js)

<a href="https://www.linkedin.com/in/denys-demydovskyi/">
  <img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

</div>

---

## About
- Backend-first full-stack developer focused on **clean REST APIs**, validation, and maintainable architecture
- Working with **Java + Spring Boot** and **Node.js + Express**
- Databases: **PostgreSQL / MySQL / MongoDB**
- Tools: **Docker**, **Git**, migrations (**Liquibase**)

---

## Tech Stack

### Languages
![Java](https://img.shields.io/badge/Java-111111?style=for-the-badge&logo=openjdk)
![JavaScript](https://img.shields.io/badge/JavaScript-111111?style=for-the-badge&logo=javascript)
![Node.js](https://img.shields.io/badge/Node.js-111111?style=for-the-badge&logo=nodedotjs)

### Back-end
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-111111?style=for-the-badge&logo=springboot)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-111111?style=for-the-badge&logo=postgresql)
![MySQL](https://img.shields.io/badge/MySQL-111111?style=for-the-badge&logo=mysql)
![MongoDB](https://img.shields.io/badge/MongoDB-111111?style=for-the-badge&logo=mongodb)
![Liquibase](https://img.shields.io/badge/Liquibase-111111?style=for-the-badge&logo=liquibase)

### Front-end
![React](https://img.shields.io/badge/React-111111?style=for-the-badge&logo=react)
![Vite](https://img.shields.io/badge/Vite-111111?style=for-the-badge&logo=vite)
![React Router](https://img.shields.io/badge/React%20Router-111111?style=for-the-badge&logo=reactrouter)

### DevOps & Tools
![Docker](https://img.shields.io/badge/Docker-111111?style=for-the-badge&logo=docker)
![Git](https://img.shields.io/badge/Git-111111?style=for-the-badge&logo=git)

---

## Featured Projects

### 🏋️ Gym Reservation System (Full-Stack)
**Repo:** `gym-reservation-system`  
**Stack:** Node.js + Express + MySQL | React + Vite + React Router  
Full-stack CRUD application for managing **Users**, **Gym Classes**, and **Reservations** (many-to-many).

**Highlights**
- Many-to-many relation via `user_class_reservations` with extra fields: `status`, `checked_in`, `reserved_at`
- CRUD for users/classes/reservations + detail views with related entities
- Validation on both sides:
  - frontend: required fields, numeric checks, enum values, datetime presence
  - backend: format + consistency checks before DB writes
- Business rule: reservation `user_id` / `gym_class_id` cannot be changed (delete & recreate)

---

### 📦 Order Management Service (Backend)
**Repo:** `order-management-service`  
**Stack:** Java 21 | Spring Boot (Web, Validation, Data JPA) | PostgreSQL | Liquibase  
Spring Boot REST API for managing **customers** and **orders** with filtering, pagination, reporting, and bulk upload.

**Highlights**
- Layered architecture: Controller / Service / Repository / DTO
- Filtered listing with pagination via JPA Specifications
- CSV report generation for filtered orders
- Bulk JSON upload with success/failure statistics
- Liquibase migrations + seed data on startup
- Centralized error handling using `@RestControllerAdvice` + `ProblemDetail`

---

## Contact
- LinkedIn: https://www.linkedin.com/in/denys-demydovskyi/
