# Forage JPM Midas Flow Project

This project was completed as part of the JPMorgan Chase Forage program. It demonstrates key software engineering skills through the implementation of multiple tasks, automated testing, and Kafka integration.

## Description

The project is a Spring Boot application that verifies five individual tasks using JUnit tests. Each task demonstrates different aspects of backend development, including REST API handling, data persistence, and message streaming using Kafka. I implemented both the application logic and the test infrastructure, ensuring that all functionality is fully verified.

## What I Did

I developed the project from start to finish including:

- Implemented task logic and verification using Spring Boot
- Configured and tested Kafka producers and consumers with embedded Kafka
- Set up JPA repositories and integrated with an H2 in memory database for testing
- Created automated test cases using JUnit 5 for each task
- Configured Maven for project build, dependency management, and running tests

## Technologies Used

- Java 17  
- Spring Boot 3.2.5  
- Spring Data JPA  
- Spring Kafka  
- H2 in-memory database  
- JUnit 5  
- Maven  

## Running the Project

Ensure Java 17 and Maven are installed. From the project root, run:

```bash
mvn clean install
mvn spring-boot:run
