---
name: 🐛 Bug report
about: Create a report to help us improve Order Management System
title: '[BUG] '
labels: 'bug'
assignees: ''

---

## 📝 Description

Briefly describe the problem. Is it a failure in the order logic, a database connection issue, or a problem with email notifications?

## 👣 How to Reproduce

Steps to reproduce the behavior:
1. Run the application with `mvn spring-boot:run`
2. Access the endpoint: `POST /api/orders` (or via the Backoffice)
3. Perform the action: '...' (e.g., attempt to buy a product with zero stock)
4. See error: '...' (e.g., the system returns a 500 Internal Server Error instead of a validation message)

## 🎯 Expected Behavior

A clear and concise description of what you expected to happen (e.g., the system should return a 400 Bad Request explaining the stock insufficiency).

## 📸 Screenshots or API Logs (if applicable)

Add screenshots of the Backoffice or paste the JSON response from Postman/Swagger to help explain the problem.

## 💻 Environment

- **OS:** (e.g. Windows 11, macOS, Ubuntu)
- **Java Version:** (e.g. JDK 17)
- **Database:** (e.g. MySQL 8.0, PostgreSQL, H2)
- **Other relevant data:** (e.g., specific `application.properties` settings or if the SMTP server for emails is active)

## 🔍 Additional Context

Add any other context about the problem here. If the console showed a **Stacktrace** or a Hibernate error, please paste it here:



```text
[Paste your Spring Boot / Maven error log here]
