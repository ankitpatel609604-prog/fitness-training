# ForgeFit Gym Backend

A Spring Boot REST API for a gym and fitness training website.

## Features
- User registration and login
- Fitness programs listing
- Trainer profiles
- Membership plans
- Contact form submission
- Spring Security configuration

## Tech Stack
- Java 17
- Spring Boot 3
- Spring Security
- Spring Data JPA
- H2 Database
- Maven

## Project Structure
```text
src/
├── main/
│   ├── java/com/forgefit/
│   │   ├── config/
│   │   ├── controller/
│   │   ├── model/
│   │   ├── repository/
│   │   ├── service/
│   │   ├── DataLoader.java
│   │   └── FitnessApplication.java
│   └── resources/
│       └── application.properties
└── test/