# Student Management System

A beginner-friendly Student Management System built using Java, JDBC, and MySQL. The application allows users to perform basic CRUD operations on student records through a menu-driven console interface.

## Features

* Add a new student
* View all student records
* Update student details
* Delete a student
* MySQL database integration
* JDBC connectivity
* Menu-driven console interface
* PreparedStatement for database operations

## Technologies Used

* **Java 21**
* **JDBC**
* **MySQL**
* **Maven**
* **IntelliJ IDEA**

## Database

**Database:** `student_management`

**Table:** `students`

| Column | Data Type    | Description                     |
| ------ | ------------ | ------------------------------- |
| id     | INT          | Primary key with auto-increment |
| name   | VARCHAR(100) | Student name                    |
| email  | VARCHAR(100) | Student email                   |
| course | VARCHAR(100) | Student course                  |
| age    | INT          | Student age                     |

## CRUD Operations

The application demonstrates the four basic database operations:

* **Create** — Add a new student
* **Read** — View all students
* **Update** — Update existing student information
* **Delete** — Delete a student record

## Project Structure

```text
Student-Management-System-Java
│
├── src
│   └── main
│       └── java
│           └── com.harsh.studentmanagement
│               ├── DatabaseConnection.java
│               ├── Student.java
│               ├── StudentDAO.java
│               └── StudentManagementSystem.java
│
├── .gitignore
├── pom.xml
└── README.md
```

## How to Run

1. Install **JDK 21**.
2. Install **MySQL Server** and **MySQL Workbench**.
3. Create the `student_management` database.
4. Create the `students` table.
5. Configure the MySQL password using the `MYSQL_PASSWORD` environment variable.
6. Open the project in IntelliJ IDEA.
7. Allow Maven to download the MySQL Connector/J dependency.
8. Run `StudentManagementSystem.java`.

## Security

The MySQL password is not stored directly in the source code. The application reads it from the `MYSQL_PASSWORD` environment variable.

## Learning Objectives

This project was created to practice:

* Java programming
* Object-oriented programming
* JDBC database connectivity
* SQL
* MySQL
* CRUD operations
* Maven project management
* Git and GitHub

## Author

**HARSH WASNIK**

B.Sc. Computer Science Student
