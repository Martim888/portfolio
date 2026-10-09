# Port Management & Logistics System

**Academic Group Project | ISEP | 2025/2026**

[Back to Portfolio](README.md)

---

## Project Overview

The Port Management & Logistics System is a full-stack web application developed as part of the Computer Engineering degree at Instituto Superior de Engenharia do Porto (ISEP).

The platform supports the management of maritime port operations, combining vessel administration, dock management, logistics resources, operational scheduling and vessel visit monitoring.

The system integrates multiple backend services, a modern Angular frontend and an interactive 3D visualization of the port environment.

## Main Features

### Vessel & Port Infrastructure Management
- Registration and management of vessels and vessel types.
- Management of docks and storage areas.
- Administration of shipping agent organizations and representatives.
- Vessel Visit Notifications (VVN), including submission and approval workflows.

### Logistics & Resource Management
- Management of port staff and qualifications.
- Administration of operational resources.
- Scheduling of port operations.
- Resource allocation for logistics activities.

### Operational Execution & Monitoring
- Creation and management of operation plans.
- Monitoring of vessel visit executions.
- Recording of executed operations.
- Management of operational incidents and complementary tasks.

### Interactive 3D Port Visualization
- Interactive visualization of port infrastructure using Three.js.
- 3D representation of vessels, cranes, trucks and warehouses.
- Integration of 3D components into the Angular application.

### Authentication & Authorization
- User authentication and account activation workflows.
- Role-Based Access Control (RBAC).
- Different permissions for port authority officers, shipping agents, logistics operators and system users.

### Deployment & Automation
- Containerized services using Docker and Docker Compose.
- Nginx reverse proxy and frontend load balancing.
- Automated build, testing and deployment workflows using GitHub Actions.
- Backup and recovery procedures.

## Technologies

| Category | Technologies |
|---|---|
| Frontend | Angular 20, TypeScript, HTML, SCSS |
| Backend | C#, ASP.NET Core (.NET 8) |
| Additional Backend | NestJS, Node.js, TypeScript |
| Database | SQLite, Entity Framework Core, TypeORM |
| 3D Visualization | Three.js |
| Architecture | Domain-Driven Design, REST APIs |
| Infrastructure | Docker, Docker Compose, Nginx |
| CI/CD | GitHub Actions |
| Testing | xUnit, Jest, Cypress |
| Modeling | UML, C4 Model, PlantUML |

## Software Architecture

The application follows a modular architecture with separated responsibilities across its frontend, backend services and persistence components.

### Frontend - Angular

The Angular Single Page Application (SPA) provides user interfaces for port management, operational planning, resource administration and interactive 3D visualization.

### Core Backend - ASP.NET Core

The .NET API manages core port entities, such as vessels, docks, storage areas, staff, shipping organizations and vessel visit notifications.

### Operations Backend - NestJS

The NestJS service handles operational execution, operation plans, incidents and complementary tasks.

### Database & Persistence

The system uses SQLite databases with persistence frameworks such as Entity Framework Core and TypeORM.

### Infrastructure & Deployment

Docker Compose coordinates the application services, while Nginx acts as a reverse proxy and gateway.

GitHub Actions workflows support automated builds, testing, deployment and backups.

## Technical Concepts

- Full-Stack Web Development
- Object-Oriented Programming
- Domain-Driven Design
- RESTful API Development
- Modular Backend Architecture
- Role-Based Access Control
- Database Persistence
- 3D Computer Graphics
- Containerization
- Continuous Integration and Deployment
- Automated Testing
- Software Architecture Modeling

## Development Context

This project was developed collaboratively during the fifth semester of the Computer Engineering degree at ISEP, in the 2025/2026 academic year.

The project integrates web development, software architecture, information systems, 3D visualization and systems administration into a common maritime logistics scenario.

## Source Code

The original project was developed in an academic group repository.

Source code access may be provided upon request, subject to authorization.

---

[Back to Portfolio](README.md)