# Travel & Tour Management System - Backend API

A robust, scalable RESTful backend API for managing travel and tour bookings, built with Spring Boot 3 and MySQL.

![Java](https://img.shields.io/badge/Java-17-orange)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-green)
![MySQL](https://img.shields.io/badge/MySQL-8.0-blue)
![Maven](https://img.shields.io/badge/Maven-3.9-red)
![License](https://img.shields.io/badge/License-MIT-yellow)

## 📖 About The Project

This project serves as the core backend API for a comprehensive Travel & Tour Management platform. It handles user authentication, tour management, flight scheduling, booking processing, and administrative operations. The API is designed with a layered architecture (Controller → Service → Repository) and uses JPA/Hibernate for data persistence.

### Key Features

- 🔐 **User Authentication & Authorization** — JWT-based security with role-based access control (Admin, User)
- 🗺️ **Tour Management** — Full CRUD operations for tours, categories, itineraries, and pricing
- ✈️ **Flight Management** — Airport, flight, and flight schedule management
- 📅 **Booking System** — Create, manage, and track tour and flight bookings
- 👤 **User Management** — Registration, login, profile management
- 🛡️ **Admin Dashboard API** — Administrative endpoints for managing all entities
- 📊 **Data Validation** — Input validation using Jakarta Bean Validation

## 🛠️ Tech Stack

| Category | Technology |
|----------|------------|
| Language | Java 17 |
| Framework | Spring Boot 3.x |
| Security | Spring Security + JWT |
| Persistence | Spring Data JPA / Hibernate |
| Database | MySQL 8.0 |
| Build Tool | Maven |
| Documentation | SpringDoc OpenAPI (Swagger UI) |
| Testing | JUnit 5, Mockito |
| Containerization | Docker |

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- **Java JDK 17** or higher
- **Maven 3.6+**
- **MySQL 8.0+**
- **Docker** (optional, for containerized deployment)

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Anik385/Travel-and-Tour-Management-S.git
cd Travel-and-Tour-Management-S
