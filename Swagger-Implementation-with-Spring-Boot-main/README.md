# Swagger Implementation with Spring Boot

This repository contains a Spring Boot application that demonstrates the implementation of Swagger for API documentation and testing.

## Features

- Spring Boot 3.x
- Spring Security configuration for Swagger UI access
- OpenAPI 3.0 documentation
- Swagger UI for API exploration and testing

## Prerequisites

- Java 17 or higher
- Maven 3.6 or higher

## Getting Started

1. Clone the repository:
```sh
 git clone https://github.com/yourusername/swagger-spring-boot-demo.git
```

2.Navigate to the project directory:
```sh
 cd swagger-spring-boot-demo
```
3. Build the project:
```sh
 mvn clean install
```

4. Run the application:
```sh
mvn spring-boot:run
```
5. Access Swagger UI:
Open a web browser and go to `http://localhost:8080/swagger-ui/index.html`

## Configuration

The `SecurityConfiguration` class configures Spring Security to allow access to Swagger UI and API documentation endpoints. You can modify this class to add authentication or additional security measures as needed.

## API Endpoints

- GET `/api/v1/hello`: A sample endpoint that returns a greeting message.

For a complete list of endpoints and their documentation, please refer to the Swagger UI after starting the application.

Happy Coding!!