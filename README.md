# Student Management System - Testing Readme

This GitHub repository contains test code for a Student Management System, part of a larger project built using the Spring Boot framework. The system manages student data and employs various key technologies, including:

- **Spring Boot**: The core framework for building the application, providing features for data access, security, and RESTful web services.

- **JPA (Java Persistence API)**: Used for data modeling and interaction with a relational database.

- **JUnit 5**: Utilized for creating and running unit tests to ensure the robustness of the system.

- **Mockito**: Employed for mocking dependencies in unit testing, enhancing the testability of the system.

## Project Structure

The project structure is organized as follows:

- `src/main/`: Contains the main source code for the Student Management System, including the Student entity, repository, and service.

- `src/test/`: Contains test code used to verify the system's functionality. The two main test classes are:

  - `StudentRepositoryTest`: Tests the `StudentRepository` component for data access, with JUnit 5 being instrumental in executing these tests.

  - `StudentServiceTest`: Tests the `StudentService` component for managing student data and relies on JUnit 5 for running the tests.

The tests cover essential functionality such as checking email existence, adding students, and handling email duplicates. This repository serves as a valuable resource for ensuring the reliability and correctness of the Student Management System through the combined use of Spring Boot, JPA, JUnit 5, and Mockito.
