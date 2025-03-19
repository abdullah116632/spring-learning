# 🌱 Spring Learning

## 📌 Overview
**spring-learning** is a Java **Spring Boot** project created for learning and practicing the **Spring framework**. This project covers essential Spring Boot concepts, including **REST API development, dependency injection, database integration, and security**.  

It serves as a hands-on reference for understanding the fundamentals of **Spring Boot and backend development**.

## 🎯 Topics Covered
- 🌟 **Spring Boot Basics** (Project Setup, Annotations, Configuration)
- 🔗 **REST API Development** (Controllers, Request Handling, Responses)
- 📦 **Dependency Injection & Spring Beans**
- 🗄️ **Database Integration** (Spring Data JPA, Hibernate)
- 🔑 **Authentication & Security** (Spring Security, JWT)
- 🏷️ **DTO & Model Mapping**
- ⚡ **Exception Handling & Logging**
- 🚀 **Building & Running a Spring Boot Application**
  
## 🛠️ Technologies Used
- **Java** (JDK 17+ recommended)
- **Spring Boot** (Spring Web, Spring Data JPA, Spring Security)
- **Hibernate** (ORM for database interaction)
- **Maven** (Dependency management)
- **H2** (Database)

## 📂 Folder Structure
```
spring-learning/
│── src/
│   ├── main/
│   │   ├── java/com/example/springlearning/
│   │   │   ├── controller/      # REST Controllers
│   │   │   ├── service/         # Business Logic
│   │   │   ├── repository/      # Database Repositories
│   │   │   ├── model/           # Entity Models
│   │   │   ├── config/          # Security & App Configurations
│   │   │   ├── SpringLearningApplication.java  # Main entry point
│   ├── resources/
│   │   ├── application.properties  # Environment Configurations
│── pom.xml           # Maven Dependency File
│── README.md         # Documentation
```

## 🔑 Environment Variables
Create an `application.properties` file inside the **resources** folder with the following values:

```
# Server Configuration
server.port=8080

# Database Configuration
spring.datasource.url=jdbc:h2:mem:your_db_name
spring.datasource.username=your_db_username
spring.datasource.password=your_db_password
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true

# JWT Authentication
jwt.secret=your_jwt_secret

```

## 🚀 How to Run Locally
1. **Clone the repository**
   ```sh
   git clone https://github.com/abdullah116632/spring-learning.git
   cd spring-learning
   ```

2. **Install dependencies**
   ```sh
   mvn clean install
   ```

3. **Run the application**
   ```sh
   mvn spring-boot:run
   ```

4. **Access the API**
   - API will be available at: **`http://localhost:8080/`**


## 📜 License
This project is open-source and can be modified for learning purposes.
