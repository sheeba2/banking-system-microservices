# Banking System – Microservices Application

## Project Overview

A backend Banking System application developed using Java and Spring Boot, following a Microservices Architecture. The application is divided into independent services to handle different banking operations, with a focus on modularity, service communication, data management, and backend security.

## Technology Stack

- **Backend:** Java, Spring Boot, Spring Data JPA
- **Architecture:** Microservices
- **API Gateway:** Spring Cloud Gateway
- **Database:** MySQL
- **Messaging:** Apache Kafka
- **Caching:** Redis
- **Build Tool:** Maven
- **Version Control:** Git

## Microservices

The application consists of the following services:

| Service | Responsibility |
|---|---|
| Account Service | Handles account-related operations. |
| API Gateway | Provides a common entry point for incoming API requests. |
| Fraud Detection Service | Handles fraud detection-related operations. |
| Notification Service | Manages notification-related functionality. |
| Payment Service | Handles payment-related operations. |
| Transaction Service | Manages banking transaction-related operations. |

## Key Technical Implementations

- Designed the application using a microservices-based architecture with separate Spring Boot services.
- Developed REST APIs for communication with application services.
- Integrated Apache Kafka for asynchronous, event-driven communication.
- Used Redis for caching to support efficient data access.
- Implemented API Gateway functionality to manage incoming requests.
- Used Spring Data JPA and MySQL for database interactions.

## Project Structure

```text
banking-system/
│
├── account-service/
├── api-gateway/
├── fraud-detection-service/
├── notification-service/
├── payment-service/
├── transaction-service/
│
├── .gitignore
└── README.md
```

## Planned Enhancements

- Integrate Razorpay payment gateway for online payment processing.
- Implement payment signature verification and webhook handling.
- Develop an Angular frontend for interacting with banking services.
- Improve payment processing through secure and reliable payment workflows.

## Purpose

This project was developed to gain practical experience in building backend applications using Spring Boot Microservices, exploring inter-service communication, asynchronous processing, caching, API gateway concepts, and payment gateway integration.

