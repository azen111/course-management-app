# Course Management App

A simple Course Management web application built using Spring Boot, Spring Data JPA, MySQL, and Thymeleaf.

## Features

- Add new courses
- View all courses
- Update course details
- Delete courses

## Tech Stack

- Java
- Spring Boot
- Spring Data JPA / Hibernate
- MySQL
- Thymeleaf
- Maven

## Getting Started

1. Clone this repository.
2. Create a MySQL database named `course_management_db`.
3. Configure your database connection in `application.properties` or set the required environment variables.
4. Run the application from Eclipse or using Maven:

   ```bash
   mvn spring-boot:run
   ```

5. Open `http://localhost:8484` in your browser.

## Configuration

Set the following environment variables for your MySQL connection:

- `DB_URL` — JDBC URL of your database (optional if using the default URL)
- `DB_USERNAME` — MySQL username (optional if using the default username)
- `DB_PASSWORD` — MySQL password

## Purpose

This project was built as a learning project to practise Spring Boot, database integration, MVC architecture, and CRUD operations.
