> **This project has been merged into [PryFry](https://github.com/priyansh18/Resturant_site) - a full restaurant management platform.**
> **Live:** [pryfry-priyanshsinghal.vercel.app](https://pryfry-priyanshsinghal.vercel.app)

---

# Employee Management System

A full-stack web application for managing employee information, built with Spring Boot and React.

## 🚀 Features

- **Backend (Spring Boot)**
  - RESTful API endpoints for employee management
  - JPA/Hibernate for database operations
  - MySQL database integration
  - Clean architecture with Controller-Service-Repository pattern

- **Frontend (React)**
  - Modern UI with React 18
  - Bootstrap 5 for responsive design
  - Axios for API integration
  - Clean component structure

## 🛠️ Tech Stack

- **Backend**
  - Java 17
  - Spring Boot 3.x
  - Spring Data JPA
  - MySQL Database
  - Maven

## 🏗️ Project Structure

```
project/
├── employee/                    # Backend (Spring Boot)
│   ├── src/
│   │   └── main/
│   │       ├── java/com/priyansh/employee/
│   │       │   ├── controller/      # REST controllers
│   │       │   ├── entity/          # JPA entities
│   │       │   ├── repository/      # Data access layer
│   │       │   ├── service/         # Business logic
│   │       │   └── EmployeeApplication.java
│   │       └── resources/
│   │           └── application.properties
│   └── pom.xml
│
└── employeeweb/                 # Frontend (React)
    ├── src/
    │   ├── components/          # Reusable components
    │   ├── services/            # API services
    │   └── App.js               # Main application component
    └── package.json
```

## 🚀 Getting Started

### Prerequisites
- Java 17 or higher
- Node.js 16+ and npm
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

3. **Build and run the backend**
   ```bash
   cd employee
   ./mvnw spring-boot:run
   ```
   The backend will be available at `http://localhost:8080`

### Frontend Setup

1. **Install dependencies**
   ```bash
   cd employeeweb
   npm install
   ```

2. **Start the development server**
   ```bash
   npm start
   ```
   The frontend will be available at `http://localhost:3000`

## 📚 API Documentation

### Employee Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST   | /api/employee | Create a new employee |

### Example Request

```http
POST /api/employee
Content-Type: application/json

{
    "name": "John Doe",
    "email": "john@example.com",
    "phone": "1234567890",
    "department": "Engineering"
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
