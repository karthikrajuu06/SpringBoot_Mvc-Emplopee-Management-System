# SpringBoot_Mvc-Emplopee-Management-System
# Employee Management System

A web-based Employee Management System developed using **Java, Spring Boot, Spring MVC, Thymeleaf, and MySQL**. This application allows users to register employees, store employee information, and manage employee records through a web interface.

## 🚀 Features

- Add/Register new employees
- Store employee details in MySQL database
- View employee information
- Spring MVC architecture
- Server-side form handling
- Database integration using Spring Data JPA
- Dynamic web pages using Thymeleaf

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Java | Backend programming |
| Spring Boot | Application development |
| Spring MVC | Web request handling |
| Spring Data JPA | Database operations |
| MySQL | Database |
| Thymeleaf | Frontend template engine |
| HTML & CSS | User interface |
| Maven | Dependency management |
| Spring Tool Suite (STS) | Development IDE |

## 📂 Project Structure

```text
EmployeeManagementSystem/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/example/
│   │   │       ├── controller/
│   │   │       ├── entity/
│   │   │       ├── repository/
│   │   │       ├── service/
│   │   │       └── EmployeeManagementApplication.java
│   │   │
│   │   └── resources/
│   │       ├── templates/
│   │       ├── static/
│   │       └── application.properties
│   │
│   └── test/
│
├── pom.xml
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Open the Project

- Open Spring Tool Suite (STS).
- Import the project as an Existing Maven Project.
- Wait for Maven dependencies to download.

### 3. Configure MySQL Database

Create a database:

```sql
CREATE DATABASE springboot_mvc;
```

Configure `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/springboot_mvc
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

server.port=8080
```

### 4. Run the Application

Run the main Spring Boot application class from STS.

Or use Maven:

```bash
mvn spring-boot:run
```

### 5. Access the Application

Open your browser:

```text
http://localhost:8080
```

## 🔄 Application Workflow

1. User opens the Employee Registration page.
2. User enters employee details.
3. Form submits the data to the Spring MVC Controller.
4. Controller processes the request.
5. Service layer handles business logic.
6. Repository saves employee information into MySQL.
7. Application returns the appropriate response.

## 📸 Screenshots

_Add application screenshots here._

## 🔮 Future Enhancements

- Employee update functionality
- Employee deletion functionality
- Employee search functionality
- Employee list and details page
- Form validation
- REST API integration
- Spring Security authentication and authorization

## 👨‍💻 Author

**Kartheek Atmakuru**

- GitHub: https://github.com/karthikrajuu06
- LinkedIn: https://linkedin.com/in/kartheekatmakuru

---

⭐ If you find this project useful, feel free to star the repository!
