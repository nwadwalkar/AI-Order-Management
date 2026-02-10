# Spring Boot Order Service

A Spring Boot application for managing orders.


A production-ready Spring Boot backend service demonstrating
clean architecture, transactional boundaries, and REST API design.

## Tech Stack
- Java 17
- Spring Boot
- Spring Web
- Spring Data JPA
- PostgreSQL
- Maven

## Architecture
- Thin REST controllers
- Transactional service layer
- JPA repositories
- Centralized exception handling
- Health and observability endpoints

## Endpoints
- POST /api/v1/orders
- GET /api/v1/orders/{id}
- GET /actuator/health

## Deployment
Deployed on Railway with managed PostgreSQL.

## Project Structure

```
springboot-order-service/
├── pom.xml
├── README.md
├── .gitignore
└── src/
    ├── main/
    │   ���── java/com/example/orders/
    │   │   ├── OrderServiceApplication.java
    │   │   ├── controller/
    │   │   ├── service/
    │   │   ├── repository/
    │   │   └── domain/
    │   └── resources/
    │       ├── application.properties
    │       └── logback.xml (optional)
    └── test/
```

## Prerequisites

- Java 17 or higher
- Maven 3.6+

## Building the Project

```bash
mvn clean install
```

## Running the Application

```bash
mvn spring-boot:run
```

## Dependencies

- Spring Boot Web Starter
- Spring Boot Test Starter

## License

MIT
