# Microservices Commerce Platform

A backend-focused microservices application built with Java and Spring Boot to explore distributed system design, service-to-service communication, event-driven workflows, and cloud-native development practices.

This project is inspired by real-world microservice architecture patterns and focuses on building scalable, independently deployable services.

---

## Architecture Overview

The platform is designed around independently deployable services such as:

- **API Gateway** – single entry point for client requests
- **Product Service** – manages product catalog and inventory
- **Order Service** – handles order creation and order lifecycle
- **User Service** – manages customer data and authentication
- **Notification Service** – async event-based notifications

Additional infrastructure components may include:

- Service discovery
- Centralized configuration
- Message broker for asynchronous communication
- Containerized deployment

---

## Tech Stack

- **Java 17**
- **Spring Boot**
- **Spring Cloud**
- **Spring Data JPA**
- **PostgreSQL**
- **Apache Kafka**
- **Docker**
- **Maven**

---

## Key Concepts Practiced

- Microservices architecture
- API gateway routing
- Inter-service communication
- Event-driven messaging
- Database per service
- Distributed system design
- Containerized local development

---

## Current Status

This project is currently under active development.

Implemented so far:

- Initial project structure
- Base service scaffolding
- Repository setup
- Initial service configuration

Planned next steps:

- Product APIs
- Order workflow
- Kafka-based event publishing
- Service discovery integration
- Docker Compose local environment

---

## Running Locally

```bash
git clone git@github.com:Vishalvj13/microservices-commerce-platform.git
cd microservices-commerce-platform
