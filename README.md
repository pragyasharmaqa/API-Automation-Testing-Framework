# API-Automation-Testing-Framework-EdTech-Sample-Project

![Java](https://img.shields.io/badge/Java-1.7-orange)
![Selenium](https://img.shields.io/badge/Selenium-WebDriver-blue)
![Maven](https://img.shields.io/badge/Maven-DependencyManagement-brightgreen)

## Overview

This repository contains a **REST API Automation Framework** built using **Java, Selenium, and Maven** in Eclipse IDE. 

It demonstrates a scalable, maintainable, and reusable API automation testing framework inspired by real-world work in the EdTech domain. Using public Swagger APIs for confidentiality, this project reflects best practices in API automation, including architecture, coding standards, and test strategies. 

The framework showcases automation of CRUD operations for API endpoints and emphasizes **reusability, modularity, and detailed reporting**.

## Project Structure
src/test/java
│
├── base
│ └── BaseTest.java # Base class for initializing test configurations
│
├── endpoints
│ ├── PetEndpoints.java # API calls related to Pet entity
│ └── UserEndpoints.java # API calls related to User entity
│
├── models
│ ├── PetPayload.java # POJO for Pet payload
│ └── UserPayload.java # POJO for User payload
│
├── reporter
│ ├── ExtentManager.java # ExtentReports configuration
│ ├── ExtentReportListenerClass.java # Listener for report generation
│ └── MyListener.java # Custom listener for test execution
│
├── tests
│ ├── CreatePet.java
│ ├── UpdatePet.java
│ ├── DeletePet.java
│ ├── GetPetById.java
│ ├── GetPetByStatus.java
│ ├── CreateUser.java
│ ├── UpdateUser.java
│ ├── DeleteUser.java
│ ├── GetUser.java
│ ├── LoginUser.java
│ └── LogoutUser.java
│
└── utils
└── TestDataLoader.java # Utility for loading test data

src/test/resources # Configuration and resource files

pom.xml # Maven dependencies



## Key Features

- **Modular Framework:** Separate packages for base classes, endpoints, payload models, reporters, and tests.  
- **Swagger API Integration:** Demonstrates CRUD operations for `User` and `Pet` endpoints.  
- **Data-Driven Testing:** Utilities to load test data dynamically.  
- **Detailed Reporting:** Integrated **ExtentReports** for detailed test execution reports.  
- **Reusable Components:** Base test class, endpoints, and payloads designed for maximum reusability.  
- **Selenium Integration:** Supports UI automation alongside API testing if needed.  

---

## Prerequisites

- Java SE 1.7 or higher  
- Maven  
- Eclipse IDE (or any Java IDE)  
- Internet connection for API access  

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/yourusername/api-automation-framework.git

2. Import the project into Eclipse as a Maven project.

3. Update test data if needed in src/test/resources.

4. Run tests via JUnit/TestNG or Maven:
mvn clean test

5. Check the generated ExtentReports in target/reports for detailed test execution results.


## Technologies Used

Java 1.7

Selenium WebDriver

Maven

JUnit / TestNG (depending on your configuration)

REST Assured (for API requests)

ExtentReports (for reporting)

Swagger (for API endpoints reference)


## Contribution

This repository is intended to showcase learning and understanding of API automation. Contributions, feedback, and improvements are welcome.


## License

This project is open for learning purposes and can be shared with proper attribution.


## Future Enhancements

Integrate CI/CD pipeline (GitHub Actions or Jenkins) to automate test execution on push.

Add environment configuration files for multiple API environments.

Include more comprehensive test scenarios and negative testing.

Integrate logging framework (e.g., Log4j) for better traceability.

Implement advanced data-driven testing using Excel/CSV/JSON.  


## Author
Pragya Sharma
Email: sharmapragya312@gmail.com 
GitHub: [pragyasharmaqa](https://github.com/pragyasharmaqa)

