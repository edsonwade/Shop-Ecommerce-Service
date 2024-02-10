# 🛒 Shop Service: Ecommerce Microservices 🛍️

This project implements a microservice architecture for an e-commerce system. It consists of several independent services, each responsible for specific aspects of the system such as product management, order processing, user authentication, payment handling, and notifications.


## Objectives

The main objectives of this project are:
- Implement a scalable and maintainable e-commerce system using microservices architecture.
- Utilize various technologies and concepts such as Spring Boot, Spring Cloud, Docker, Docker Compose, Kafka, Prometheus, and more.
- Ensure security using Spring Security for authentication and authorization.
- Facilitate CI/CD pipelines with Jenkins Pipeline for automated build, test, and deployment.
- Provide thorough documentation and instructions for setting up and running the project.

## Microservices

1. **Product Service**: Manages products and their details.
    - **REST API**:
        - GET /products: Get all products
        - GET /products/{id}: Get product by ID
        - POST /products: Create a new product
        - PUT /products/{id}: Update an existing product
        - DELETE /products/{id}: Delete a product

2. **Order Service**: Handles order management and processing.
    - **REST API**:
        - GET /orders: Get all orders
        - GET /orders/{id}: Get order by ID
        - POST /orders: Create a new order
        - PUT /orders/{id}: Update an existing order
        - DELETE /orders/{id}: Delete an order

3. **User Service**: Responsible for user authentication and authorization.
    - **REST API**:
        - GET /users: Get all users
        - GET /users/{id}: Get user by ID
        - POST /users: Create a new user
        - PUT /users/{id}: Update an existing user
        - DELETE /users/{id}: Delete a user

4. **Payment Service**: Deals with payment processing.
    - **REST API**:
        - POST /payments: Process a payment for an order

5. **Notification Service**: Sends notifications to users.

## Shared Libraries

1. **Common Library**: Contains shared code, models, and utilities used across multiple services.
2. **Security Library**: Contains security-related functionality such as authentication and authorization.

## Technologies and Concepts Used

- Spring Boot
- Spring Cloud (Gateway API, Load Balancing, Cache, Health, Metrics)
- Spring Security
- Maven
- Docker, Dockerfile, Docker Compose
- Flyway Migration, JPA, PostgreSQL, MongoDB
- OpenAPI (Swagger), HATEOAS Rest
- Apache Kafka, Email, Prometheus, Grafana, Testcontainers (Unit Test, Functional Test, Integration Test with Mockito)
- CI/CD with Jenkins Pipeline
- Dev Configuration and Production Environment Setup

## Entity Model

The entity model includes entities such as:
- Product
- Order
- User
- Payment
- Notification

Each microservice manages its related entities and exposes APIs for CRUD operations and business-specific functionality.

## Setup and Configuration

1. Clone the repository.
2. Install Docker and Docker Compose.
3. Navigate to the project directory.
4. Run `docker-compose up` to build and start the microservices and their dependencies.
5. Access the individual microservices' endpoints as per their documentation for further configuration and usage.

## Contributing

If you'd like to contribute to this project, please follow these guidelines:
- Fork the repository.
- Create a new branch for your feature or fix.
- Make your changes and commit them.
- Push to your fork and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).


[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-2.5.5-brightgreen)](https://spring.io/projects/spring-boot)
[![Spring Cloud](https://img.shields.io/badge/Spring%20Cloud-2020.0.4-brightgreen)](https://spring.io/projects/spring-cloud)
[![Java](https://img.shields.io/badge/Java-11-blue)](https://www.java.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-13.3-blue)](https://www.postgresql.org/)
[![MongoDB](https://img.shields.io/badge/MongoDB-5.0-blue)](https://www.mongodb.com/)
[![REST API](https://img.shields.io/badge/API-REST-blue)](https://restfulapi.net/)
[![Security](https://img.shields.io/badge/Security-Spring%20Security-yellow)](https://spring.io/projects/spring-security)
[![Gateway API](https://img.shields.io/badge/Gateway%20API-Spring%20Cloud%20Gateway-yellow)](https://spring.io/projects/spring-cloud-gateway)
[![Docker](https://img.shields.io/badge/Docker-20.10.8-blue)](https://www.docker.com/)
[![Kafka](https://img.shields.io/badge/Apache%20Kafka-2.8.0-red)](https://kafka.apache.org/)
[![Prometheus](https://img.shields.io/badge/Prometheus-2.30.0-red)](https://prometheus.io/)
[![Grafana](https://img.shields.io/badge/Grafana-8.1.5-red)](https://grafana.com/)
[![Jenkins](https://img.shields.io/badge/Jenkins-2.319.2-blue)](https://www.jenkins.io/)
[![Swagger](https://img.shields.io/badge/OpenAPI-Swagger-brightgreen)](https://swagger.io/)
[![Mockito](https://img.shields.io/badge/Mockito-Used-green)](https://site.mockito.org/)
[![Hibernate](https://img.shields.io/badge/Hibernate-Used-blue)](https://hibernate.org/)
[![Maven](https://img.shields.io/badge/Maven-Used-blue)](https://maven.apache.org/)
[![Testcontainers](https://img.shields.io/badge/Testcontainers-Used-blue)](https://www.testcontainers.org/)
[![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)](https://www.linux.org/)
[![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)](https://www.java.com/)
[![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white)](https://www.jetbrains.com/idea/)
[![SonarLint](https://img.shields.io/badge/SonarLint-CB2029?style=for-the-badge&logo=sonarlint&logoColor=white)](https://www.sonarlint.org/)
[![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white)](https://www.notion.so/)
[![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)](https://hibernate.org/)
[![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=Spring-Security&logoColor=white)](https://spring.io/projects/spring-security)
[![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white)](https://www.jenkins.io/)
[![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=Jira&logoColor=white)](https://www.atlassian.com/software/jira)


