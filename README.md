# First-Rest-Api-Spring – Task 2

This project represents Task 2 of the First-Rest-Api-Spring application.
The objective of this task is to implement a full CRUD REST API for managing
products using Spring Boot and Spring Data JPA.

All endpoints were tested using Swagger UI, and screenshots of each use case
are provided as required.

---

## Features

- REST API based on Spring Boot
- Product entity with CRUD operations
- Exception handling for missing resources
- H2 in-memory database
- Swagger UI for API documentation and testing

---

## Technologies Used

- Java 17
- Spring Boot
- Spring Web
- Spring Data JPA
- H2 Database
- Swagger (springdoc-openapi)
- Maven

---

## How to Run the Application

1. Clone or download the repository.
2. Open the project in IntelliJ IDEA.
3. Wait for Maven to download all dependencies.
4. Run the `FirstRestApiSpringApplication` class.
5. Open your browser and navigate to:# First-Rest-Api-Spring – Task 2

This project represents Task 2 of the First-Rest-Api-Spring application.
The objective of this task is to implement a full CRUD REST API for managing
products using Spring Boot and Spring Data JPA.

All endpoints were tested using Swagger UI, and screenshots of each use case
are provided as required.

---

## Features

- REST API based on Spring Boot
- Product entity with CRUD operations
- Exception handling for missing resources
- H2 in-memory database
- Swagger UI for API documentation and testing

---

## Technologies Used

- Java 17
- Spring Boot
- Spring Web
- Spring Data JPA
- H2 Database
- Swagger (springdoc-openapi)
- Maven

---

## How to Run the Application

1. Clone or download the repository.
2. Open the project in IntelliJ IDEA.
3. Wait for Maven to download all dependencies.
4. Run the `FirstRestApiSpringApplication` class.
5. Open your browser and navigate to:http://localhost:8080/swagger-ui/index.html


---

## API Endpoints

| Method | Endpoint                     | Description               |
|------|------------------------------|---------------------------|
| POST | /api/v1/products             | Create a new product      |
| GET  | /api/v1/products             | Get all products          |
| GET  | /api/v1/products/{id}        | Get product by ID         |
| PUT  | /api/v1/products/{id}        | Update product            |
| DELETE | /api/v1/products/{id}      | Delete product            |

---

## API Usage – Screenshots

All endpoints of the application were tested using Swagger UI.

### Create Product (POST)
![POST example 1](screenshots/post1.png)
![POST example 2](screenshots/post2.png)

### Get All Products (GET)
![GET all example 1](screenshots/get1.png)
![GET all example 2](screenshots/get2.png)
![GET all example 3](screenshots/get3.png)

### Get Product by ID (GET)
![GET by id example 1](screenshots/get1-id.png)
![GET by id example 2](screenshots/get2-id.png)

### Update Product (PUT)
![PUT example 1](screenshots/put1-id.png)
![PUT example 2](screenshots/put2-id.png)
![PUT example 3](screenshots/put3-id.png)

### Delete Product (DELETE)
![DELETE example 1](screenshots/delete1-id.png)
![DELETE example 2](screenshots/delete2-id.png)

---

## Additional Task – Theory Question

![Answer to repository question](screenshots/question.png)

---

## Author

Student: Ayse Erdem
Course: First REST API Spring  
Task: #2 – CRUD REST API




