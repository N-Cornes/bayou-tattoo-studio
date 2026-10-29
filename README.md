# Bayou Tattoo Studio Management

An original full-stack tattoo studio management application designed and developed by Nicholas Cornes to organize clients, artists, services, appointments, inventory, and operational reporting in one system.

## Live Application

https://bayou-tattoo-studio.onrender.com/

## Tech Stack

- Java 17
- Spring Boot
- Spring MVC
- Spring Security
- Spring Data JPA
- Hibernate
- Thymeleaf
- HTML / CSS
- PostgreSQL
- H2
- Maven
- Docker
- Render

## Core Features

- Client management
- Artist management
- Tattoo service management
- Appointment creation, editing, search, and deletion
- Inventory tracking with reorder-level monitoring
- Operational reporting
- Form validation
- Authentication and authorization
- Persistent relational data storage
- Cloud deployment

## Architecture

The application uses a layered architecture that separates presentation, request handling, business logic, persistence, and database storage.

```text
Browser / Thymeleaf UI
        ↓
Spring MVC Controllers
        ↓
Service Layer
        ↓
Spring Data JPA Repositories
        ↓
PostgreSQL / H2
```

This structure keeps responsibilities separated and makes the application easier to maintain, test, and extend.

## Security

Spring Security is used to protect application functionality through authentication and authorization. Deployment configuration uses environment variables for sensitive database credentials instead of storing production secrets directly in source code.

## Database

The application uses:

- **H2** for local development
- **PostgreSQL** for the deployed cloud environment

Hibernate and Spring Data JPA manage persistence and relational data access.

## Deployment

The application is containerized using a multi-stage Docker build and deployed to Render. The production environment connects to a Render-hosted PostgreSQL database using environment-based configuration.

## What I Built

I designed the Bayou Tattoo Studio concept and developed the application around the workflow of a real tattoo studio. The project combines full-stack development, relational database design, authentication, validation, inventory logic, reporting, Docker containerization, and cloud deployment in one application.

## Source Code

The complete implementation is maintained in a private repository. Source access can be provided for professional review upon request.

## Author

**Nicholas Cornes**  
B.S. Software Engineering
