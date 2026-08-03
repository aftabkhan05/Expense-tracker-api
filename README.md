Smart Expense Tracker API is a secure RESTful backend application that helps users manage their daily expenses efficiently. 
The application provides user authentication using JWT and allows every user to securely create,  update, delete, and view only their own expense records.

The project follows a clean layered architecture using Spring Boot best practices and demonstrates secure API development with role-based authentication, 
database integration, and RESTful design.

Client (Postman)

        │

        ▼

Controller Layer
        │

        ▼

Service Layer
        │

        ▼

Repository Layer
        │

        ▼

MySQL Database


⚙ Tech Stack :

| Technology      | Purpose                           |
| --------------- | --------------------------------- |
| Java 21         | Programming Language              |
| Spring Boot     | Backend Framework                 |
| Spring Security | Authentication & Authorization    |
| JWT             | Secure Token-Based Authentication |
| Spring Data JPA | ORM                               |
| Hibernate       | Database Mapping                  |
| MySQL           | Database                          |
| Maven           | Dependency Management             |
| Postman         | API Testing                       |


📂 Project Structure

src
 ├── controller
 ├── service
 ├── repository
 ├── entity
 ├── dto
 ├── security
 ├── configuration
 ├── exception
 └── util

🚀 Features

🔐 Authentication & Authorization
• User Registration
• User Login
• JWT Token Generation
• Spring Security Integration
• Password Encryption using BCrypt
• Protected REST APIs
• Users can access only their own expense records

💵 Expense Management

• Add New Expense
• Update Existing Expense
• Delete Expense
• View All Expenses
• View Expense by ID

🔍 Filtering

Users can filter expenses based on:
 • Category
 • Date Range
 • Multiple search combinations

 Example:
 • Food expenses
 • Travel expenses
 • Expenses between two dates

✅ Validation

Implemented request validation for:
• Empty fields
• Invalid amount
• Invalid category
• Missing required fields

🔐 Authentication Flow

Register User
      │
      ▼
Login
      │
      ▼
Generate JWT Token
      │
      ▼
Send Token in Authorization Header

Authorization:
Bearer <JWT_TOKEN>

      │
      ▼
Access Protected APIs


📖 Key Learnings

During this project, I gained practical experience in:

 • Building secure REST APIs using Spring Boot
 • Implementing JWT-based authentication and authorization
 • Designing layered backend architecture
 • Using Spring Security for endpoint protection
 • Database integration with Spring Data JPA
 • Exception handling and request validation
 • API testing using Postman

🚀 Future Improvements

Expense Analytics Dashboard
Monthly Expense Reports
Budget Management
Email Notifications
Export Reports to PDF/Excel
Docker Containerization
Swagger/OpenAPI Documentation
Unit & Integration Testing





 
