Student Management System

A web application built using Spring Boot, Thymeleaf, and MySQL to manage student records efficiently. The system enables administrators to perform full CRUD operations — including adding, viewing, updating, and deleting student information — through a user-friendly web interface.

📌 Features

✔️ Add new student records
✔️ View all students
✔️ Update student details
✔️ Delete student entries
✔️ Form-based interface using Thymeleaf

🛠 Technologies Used

Java (Spring Boot & Spring MVC)

Thymeleaf – Frontend templating

Spring Data JPA (Hibernate) – ORM for MySQL

MySQL – Database

Maven – Build tool

🚀 Getting Started
Prerequisites

Make sure you have installed:
✔ Java JDK 17+
✔ Maven
✔ MySQL

Setup

Create a database named:

student_management


Update application.properties with your database credentials:

spring.datasource.url=jdbc:mysql://localhost:3306/student_management
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update


Build and run:

mvn spring-boot:run


Open in browser:

http://localhost:8080/students/list

📁 Folder Structure
src/
 └─ main/
    ├─ java/
    └─ resources/
       ├─ templates/
       └─ application.properties

📝 License

This project is open source — feel free to modify and enhance!
