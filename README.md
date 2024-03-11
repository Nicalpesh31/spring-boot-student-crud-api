# Spring Boot Student CRUD API

This repository contains a CRUD (Create, Read, Update, Delete) API built using Spring Boot for managing student data.

## Features
- Create, Read, Update, and Delete student records via RESTful API endpoints.
- Supports basic student information such as first name, last name, age, and email.
- Utilizes Spring Data JPA for database interactions.

## Technologies Used
- Spring Boot
- Spring Data JPA
- H2 Database (for development, testing)
- Maven

## Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/spring-boot-student-crud-api.git

2. **Navigate to the project directory**
  cd spring-boot-student-crud-api

3. **Run the application**
  mvn spring-boot:run

## Access the API:
You can now access the API at http://localhost:8081/students  

## Endpoints

- **GET /students:** Retrieve all students.
- **GET /students/{id}:** Retrieve a specific student by ID.
- **POST /students:** Create a new student.
- **PUT /students/{id}:** Update an existing student.
- **DELETE /students/{id}:** Delete a student.


## Testing
You can test the API endpoints using tools like Postman or by writing unit/integration tests.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or create a pull request.
