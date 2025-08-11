# 🚀 Spring Boot Application

A modern Spring Boot application built with Java and Maven, following clean architecture principles.  
Easily extensible, testable, and production-ready.

---

## 📋 Table of Contents
1. [About the Project](#-about-the-project)
2. [Tech Stack](#-tech-stack)
3. [Getting Started](#-getting-started)
4. [Running the Application](#-running-the-application)
5. [Running Tests](#-running-tests)
6. [Build & Package](#-build--package)
7. [Project Structure](#-project-structure)
8. [License](#-license)

---

## 📖 About the Project

Briefly describe what your project does here.  
For example:

> This application is a REST API that provides endpoints for managing resources such as users, orders, or products.  
> Built with Spring Boot, it leverages modern Java practices and Maven for dependency management.

---

## 🛠 Tech Stack

- **Java 17+**
- **Spring Boot 3+**
- **Maven**
- **JUnit 5** for testing
- **Lombok** for reducing boilerplate
- (Optional) **H2 / PostgreSQL / MySQL** for database

---

## 🚀 Getting Started

### Prerequisites
Make sure you have:

- **Java 17+** installed → [Download](https://adoptium.net/)
- **Maven** installed or use Maven Wrapper included in the project
- An IDE like **IntelliJ IDEA** or **VS Code**

---

## ▶ Running the Application

### **Option 1 – Maven Wrapper (Recommended)**
_No need to install Maven globally._

**Windows (CMD/PowerShell):**
```powershell
.\mvnw spring-boot:run


## 🚀 Running the Application

### Option 3 – IntelliJ IDEA
1. Open the project in IntelliJ IDEA  
2. Wait for Maven dependencies to be downloaded  
3. Locate the Application main class (`src/main/java/...`)  
4. Click the **Run ▶️** button or press `Shift + F10`

---

## 🧪 Running Tests

**Run all tests:**
```bash
./mvnw test
