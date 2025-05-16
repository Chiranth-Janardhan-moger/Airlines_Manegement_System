# ✈️ Airlines Management System

A full-stack web application for managing airline operations such as flight scheduling, ticket booking, and passenger data. Built with **Java Spring Boot**, **HTML/CSS**, and **MySQL**.

---

## 🔧 Tech Stack

- **Backend**: Java Spring Boot  
- **Frontend**: HTML, CSS  
- **Database**: MySQL  
- **Build Tool**: Maven  
- **IDE**: IntelliJ IDEA / Eclipse

---

## 🚀 Features

- Add, update, and delete flights
- Book and cancel tickets
- Manage passenger details
- View all scheduled flights
- Optional: Admin and user roles, dashboard

---

## 📁 Project Structure

```
AirlinesManagementSystem/
├── src/
│   └── main/
│       ├── java/com/airlines/
│       │   ├── controller/
│       │   ├── model/
│       │   ├── repository/
│       │   └── service/
│       └── resources/
│           ├── static/            # HTML, CSS
│           ├── templates/         # Thymeleaf (optional)
│           └── application.properties
├── pom.xml
└── README.md
```

---

## 🛠️ Setup Instructions

### 📌 Prerequisites

- JDK 17 or higher
- MySQL server
- Maven
- Git

### ⚙️ Setup Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/airlines-management-system.git
   cd airlines-management-system
   ```

2. **Create the MySQL database**
   ```sql
   CREATE DATABASE airlines_db;
   ```

3. **Configure database in `application.properties`**
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/airlines_db
   spring.datasource.username=root
   spring.datasource.password=yourpassword
   spring.jpa.hibernate.ddl-auto=update
   ```

4. **Run the application**
   ```bash
   mvn spring-boot:run
   ```

5. **Access the app**
   - Frontend: `http://localhost:8080`
   - API endpoints: `http://localhost:8080/api/...`

---
