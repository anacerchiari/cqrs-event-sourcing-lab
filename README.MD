````md
# CQRS Microservices with Spring & Kafka

Enterprise-grade microservices architecture implementing CQRS (Command Query Responsibility Segregation) with Apache Kafka for asynchronous communication and event-driven processing.

This project demonstrates scalable distributed system patterns commonly used in financial systems, cloud-native applications, and modern enterprise platforms.

---

# Architecture Overview

The platform is built using:

- CQRS Pattern
- Event-Driven Architecture
- Apache Kafka Messaging
- Distributed Microservices
- Asynchronous Processing
- Spring Boot Ecosystem
- Containerized Infrastructure

The architecture separates command operations (write side) from query operations (read side), improving scalability, resilience, and maintainability.

---

# Project Structure

## banking-accounts
Microservice responsible for:
- Account management
- Transaction processing
- Command handling
- Domain business rules
- Event publishing

## cqrs.core
Shared core module containing:
- CQRS abstractions
- Base commands
- Domain events
- Shared DTOs
- Utility components

## Kafka Integration
Kafka is responsible for:
- Event streaming
- Asynchronous communication
- Decoupled microservice interaction
- Reliable message delivery

## Docker Compose
Container orchestration for:
- Kafka
- Zookeeper
- Application services
- Local development environment

---

# Main Concepts

## CQRS
Separates:
- Commands → write operations
- Queries → read operations

Benefits:
- Independent scalability
- Better performance
- Clear separation of responsibilities
- Improved maintainability

---

## Event-Driven Architecture
System components communicate through events instead of direct synchronous calls.

Advantages:
- Loose coupling
- Scalability
- Resilience
- Distributed processing

---

## Kafka Event Streaming
Apache Kafka provides:
- High-throughput messaging
- Persistent event storage
- Event replay capabilities
- Distributed communication backbone

---

# Technologies

- Java
- Spring Boot
- Apache Kafka
- Docker
- REST APIs
- Microservices
- Event Sourcing Concepts
- Distributed Systems

---

# Running the Project

## Start Infrastructure

```bash
docker-compose up --build
````

---

# API Testing

Import the Postman collection:

```bash
CQRS.postman_collection.json
```

---

# Use Cases

* Banking systems
* Financial transactions
* Event-driven platforms
* Enterprise integration
* Scalable backend systems
* Distributed architectures

---

# Topics

`cqrs` `kafka` `springboot` `java` `microservices` `event-driven` `distributed-systems` `docker` `banking` `cloud-native`

---

# Author

Ana Luiza Cerchiari de Andrade

Cloud/SRE Engineer specialized in distributed systems, Kafka ecosystems, Kubernetes, observability, cloud-native platforms, and scalable enterprise architecture.

```
```
