# Employee Management System

A full-stack web application for managing employee information, built with Spring Boot and React.

## 🚀 Features

- **Backend (Spring Boot)**
  - RESTful API endpoints for CRUD operations
  - JPA/Hibernate for database operations
  - MySQL database integration
  - Exception handling and validation

- **Frontend (React)**
  - Coming soon...

## 🛠️ Tech Stack

- **Backend**
  - Java 17
  - Spring Boot 3.x
  - Spring Data JPA
  - MySQL Database
  - Maven

## 🏗️ Project Structure

```
employee/
├── src/
│   └── main/
│       └── java/com/priyansh/employee/
│           ├── controller/      # REST controllers
│           ├── entity/          # JPA entities
│           ├── repository/      # Data access layer
│           ├── service/         # Business logic
│           └── EmployeeApplication.java  # Main application class
│       └── resources/
│           └── application.properties    # Configuration
```

## 🚀 Getting Started

### Prerequisites
- Java 17 or higher
- MySQL 8.0 or higher
- Maven 3.6.3 or higher

### Backend Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/priyansh18/employee-web.git
   cd employee-web
   ```

2. **Configure the database**
   - Create a MySQL database named `employee`
   - Update the database credentials in `employee/src/main/resources/application.properties`

3. **Build and run the application**
   ```bash
   cd employee
   mvn spring-boot:run
   ```

## 📚 API Documentation

### Employee Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET    | /api/employees | Get all employees |
| GET    | /api/employees/{id} | Get employee by ID |
| POST   | /api/employees | Create a new employee |
| PUT    | /api/employees/{id} | Update an employee |
| DELETE | /api/employees/{id} | Delete an employee |

### Example Requests

**Create Employee**
```http
POST /api/employees
Content-Type: application/json

{
    "name": "John Doe",
    "email": "john.doe@example.com",
    "phone": "+1234567890",
    "department": "Engineering"
}
```

**Update Employee**
```http
PUT /api/employees/1
Content-Type: application/json

{
    "name": "John Doe Updated",
    "email": "john.doe.updated@example.com",
    "phone": "+1234567891",
    "department": "HR"
}
```

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Spring Boot Team
- React Team
- All contributors