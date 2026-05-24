# 🛒 Order Management System

A robust enterprise-grade solution for managing dynamic product catalogs, inventory control, and customer orders. Built with **Java** and **Spring Boot**, this system handles complex business rules, user authentication, and automated notifications within a modular and testable architecture.

# 📍 Table of Contents
- [📝 Description](#-description)
  - [🧩 Key Features](#-key-features)
  - [🛠️ Technologies](#️-technologies)
- [🚀 Getting Started](#-getting-started)
  - [📋 Prerequisites](#-prerequisites)
  - [⚙️ Installation](#️-installation)
- [🏗️ Project Management](#️-project-management)
- [🤝 Contributing](#-contributing)
- [👥 Team](#-team)
- [📄 License](#-license)

# 📝 Description
Developed as a collaborative group assignment, this project implements a full lifecycle for e-commerce operations. From secure user registration with email verification to complex order state management, the system is designed to be reliable, secure, and extensible.

## 🧩 Key Features
- **Authentication & Security:** Secure user registration with mandatory email verification.
- **Dynamic Catalog:** Flexible management of products with customizable attributes and categories.
- **Order Engine:** Automated order processing with configurable business rules and state transitions.
- **Inventory Control:** Real-time stock monitoring and management to prevent overselling.
- **Automated Notifications:** Integrated email service for order confirmations and status updates.
- **Admin Backoffice:** A dedicated interface for administrators to manage the entire ecosystem.

## 🛠️ Technologies
- **Backend:** Java 17+ with **Spring Boot**
- **Testing:** Unit and Integration testing with **JUnit** and **Mockito**
- **Architecture:** RESTful API principles and Layered Architecture
- **Version Control:** GitLab (Enterprise workflow)
- **Project Management:** JIRA (Agile/Scrum)

# 🚀 Getting Started

## 📋 Prerequisites
* **Java JDK 17** or higher.
* **Maven 3.6+** for dependency management.
* A relational database (e.g., MySQL or PostgreSQL) as configured in `application.properties`.

## ⚙️ Installation
1. **Clone the repository:**
   ```bash
   git clone git@github.com:SebaB29/sistema-de-pedidos.git
   cd sistema-de-pedidos
   ```

2. Configure Environment:
Update the `src/main/resources/application.properties` file with your database credentials and SMTP settings for email notifications.

3. Build the project:
   ```bash
   mvn clean install
   ```

4. Run the application:
   ```bash
   mvn spring-boot:run
   ```

# 🏗️ Project Management
This project was developed using Agile practices. We utilized JIRA to manage our sprint backlog, track issues, and ensure a continuous delivery flow. The repository follows a strict branching strategy on GitLab to maintain code quality through Peer Reviews.

# 🤝 Contributing
1. Fork the project.
2. Create your Feature Branch (git checkout -b feature/AmazingFeature).
3. Commit your changes (git commit -m 'Add some AmazingFeature').
4. Push to the Branch (git push origin feature/AmazingFeature).
5. Open a Pull Request.

# 👥 Team

| Name              |
|-------------------|
| Sebastian Brizuela|
| Matias Rueda      |
| Julián Rando      |
| Agustín Vallcorba |
| Lucas Gimenez     |
| Nicolas Penedo    |
| Joaquín Czerwiak  |

# 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
