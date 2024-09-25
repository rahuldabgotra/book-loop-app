# Book Loop App

A full-stack social platform where users can list, borrow, and return books within a secure, community-driven environment. Built with Spring Boot and Angular, the app offers an intuitive interface for managing book collections and enabling peer-to-peer lending.

## Project Description

Book Loop is designed to bring book enthusiasts together by allowing them to share their personal libraries.
- **Core Features**: Users can list books, borrow available ones, and return borrowed books with approval workflows.
- **Technology Stack**: The app leverages Spring Boot for the backend, Angular for the frontend, and Docker for containerization.
- **Security**: Secure JWT-based authentication, user registration, and role-based authorization powered by Keycloak ensure a protected user experience.
- **Challenges & Future Plans**: Key challenges included implementing secure authentication and managing large datasets efficiently. Planned features include advanced search using Elasticsearch.

## Table of Contents

- [Installation and Setup](#installation-and-setup)
- [How to Use](#how-to-use)
- [Features](#features)
- [How to Contribute](#how-to-contribute)
- [Badges](#badges)
- [License](#license)

## Installation and Setup

### Prerequisites
- **Java 21**
- **Node.js (16+)**
- **Angular CLI**
- **Docker**

### Backend Setup (SpringBoot: book-loop-api)
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/rahuldabgotra/book-loop-app.git
   cd book-loop-app/book-loop-api
   ```

[//]: # (2. **Configure MySQL Database**:)

[//]: # (    - Set up a MySQL database and update `application.properties` with your database details.)

[//]: # ()
[//]: # (3. **Run the Application**:)

[//]: # (   ```bash)

[//]: # (   ./mvnw spring-boot:run)

[//]: # (   ```)

[//]: # (4. **API Documentation**:  )

[//]: # (   Access Swagger documentation at `http://localhost:8080/swagger-ui.html`.)

[//]: # (### Frontend Setup &#40;Angular: book-loop-ui&#41;)

[//]: # (1. Navigate to the frontend directory:)

[//]: # (   ```bash)

[//]: # (   cd ../book-loop-angular)

[//]: # (   ```)

[//]: # (2. Install dependencies:)

[//]: # (   ```bash)

[//]: # (   npm install)

[//]: # (   ```)

[//]: # (3. Run the Angular app:)

[//]: # (   ```bash)

[//]: # (   ng serve)

[//]: # (   ```)

[//]: # (   Access the app at `http://localhost:4200`.)

### Docker Setup
To run the full application with Docker:
```bash
docker-compose up
```

## How to Use

Once the project is running:
- **User Registration**: Sign up for a new account to manage your books and borrow from others.
- **Book Management**: Add books to your personal collection, update details, and archive books when necessary.
- **Borrowing and Returning**: Browse the available books, borrow them, and return them when finished. The owner can approve the return request.

## Features

### Backend (Spring Boot)
- **User Authentication & Authorization**: Implemented using Spring Security 6 and JWT tokens.
- **CRUD Operations**: Manage books with Create, Read, Update, and Delete functionalities.
- **Borrow/Return System**: Users can borrow books and the owner approves returns.
- **Keycloak Integration**: Used for role-based access control.

### Frontend (Angular)
- **Responsive UI**: Built with Angular and Bootstrap, the UI adapts across devices.
- **Lazy Loading**: Optimized performance by loading components only when required.
- **OpenAPI Integration**: Automatically generates Angular client for interacting with REST APIs.

## How to Contribute

We welcome contributions to improve the application or add new features.
1. **Fork the repository**.
2. **Create a feature branch**:
   ```bash
   git checkout -b feature/your-feature
   ```
3. **Make your changes** and commit them.
4. **Submit a pull request**.

### Contribution Guidelines
- Follow the code style guidelines of the respective frameworks.
- Document your code properly.

## Badges

![Java](https://img.shields.io/badge/Java-21-blue.svg) ![SpringBoot](https://img.shields.io/badge/Spring%20Boot-3.3.4-green.svg) ![Angular](https://img.shields.io/badge/Angular-18-red.svg)

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.

---

This README is clear and structured, offering a step-by-step guide for installation, usage, and contribution, making it easy for users and contributors to engage with the project. Let me know if you need additional adjustments!