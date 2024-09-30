
# Authentication Service

This is a microservice that provides authentication and authorization functionalities using **Spring Boot**, **Spring Security**, and **JWT** for token-based authentication. It uses **PostgreSQL** as the database to store user credentials and related data.

## Features
- User registration and login functionality.
- Secure password hashing using **BCrypt**.
- JWT-based authentication and authorization.
- PostgreSQL integration for persistent storage of users.

## Prerequisites
Before running this service locally, ensure you have the following tools installed:
- Java 17 or above
- PostgreSQL

## PostgreSQL Database Configuration
spring.datasource.url=jdbc:postgresql://<HOST>:<PORT>/<DB_NAME>
spring.datasource.username=<YOUR_DB_USERNAME>
spring.datasource.password=<YOUR_DB_PASSWORD>

## JWT Secret Key
jwt.secret=<YOUR_JWT_SECRET_KEY>


### Clone the Repository

```bash
git clone <repository-url>
cd authentication-service


