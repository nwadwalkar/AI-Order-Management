# Spring Boot Order Service

A Spring Boot application for managing orders.

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