# ✈️ Airlines Management System

A full-stack web application for managing airline operations such as flight scheduling, ticket booking, and passenger data. Built with **Java Spring Boot**, **HTML/CSS**, and **MySQL**.

---

## 🔧 Tech Stack

- **Frontend**: HTML, CSS  
- **Backend**: Java Spring Boot  
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
│           ├── templates/         
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

---
## 📸 Screenshots

> Soon

---

## 💡 Future Enhancements

- JWT authentication
- Admin/user dashboards
- Email notifications

---

## 🤝 Contributing

1. Fork this repository
2. Create a new branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m "Add new feature"`
4. Push to your branch: `git push origin feature-name`
5. Create a Pull Request

---

## 📄 License

This project is licensed under the MIT License.  
© 2025 Chiranth-Moger
