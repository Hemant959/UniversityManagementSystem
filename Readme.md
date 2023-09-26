# <h2 align = "center"> University Management System</h2>
___ 
<p align="center">
<a href="Java url">
    <img alt="Java" src="https://img.shields.io/badge/Java->=8-darkblue.svg" />
</a>
<a href="Maven url" >
    <img alt="Maven" src="https://img.shields.io/badge/maven-3.1.3-brightgreen.svg" />
</a>
<a href="Spring Boot url" >
    <img alt="Spring Boot" src="https://img.shields.io/badge/Spring Boot-3.0.6-brightgreen.svg" />
</a>
</p>

---

<p align="left">

<!-- Project Description -->
## Overview
<p align="center">This project, named "University Management System," is a robust Spring Boot application designed for managing University data efficiently. It provides a set of API endpoints that allow you to perform various operations on user records, such as adding, retrieving, updating, and deleting Event and Student information. 
</p>

<!-- Table of Contents -->
## Table of Contents
1. [Technologies Used](#technologies-used)
2. [Key Features](#key-features)
3. [Usage](#usage)
4. [API reference](#api-reference)
5. [License](#license)
6. [Acknowledgments](#acknowledgments)
7. [Contact](#contact)

<!-- Technologies Used -->
## Technologies Used
- Java 8
- Spring Boot
- Spring Web Initializer
- Maven
- Spring Web Dependency
- Validation
- MYSQL
- Swagger
- H2 Database




<!-- Key Features -->
## Key Features
- Add Student 
- Update Student Department
- Delete Student
- Get all Student
- Get All Student By Id
- Add Event
- Update Event
- Delete Event
- Get All Event By Date

<!-- Usage -->
## Usage
- Access the application at `http://localhost:8080`.
- Use the provided API endpoints to CRUD Operation.

### Controller:
- It consists of a class named APIController which basically controls the flow of data.
- @RestController annotation is used to make the APIController as a controller layer.
- We perform the CRUD operations such as @PostMapping , @GetMapping , @PutMapping , @DeleteMapping.

### API Reference
    we are using Swagger to perform crud Operation and H2 data base to see the data into databse;
#### Add Users :
PostMethod :  http://localhost:8080/gets
### UPdate User:
PutMapping : http://localhost:8080/update/Student/id

### Update Event:
PutMapping: http://localhost:8080/update/Event/id
### Get all Student By Id:
GetMapping:http://localhost:8080/get/Student/id

#### Get All Student :
 - GET Method : http://localhost:8080/get/student

 ### Get Event By Date:
 PutMapping: http//:localhost:8080/get/date

 <!-- Acknowledgments -->
## Acknowledgments
- Thank you to the Spring Boot and Java communities for providing excellent tools and resources.

<!-- Contact -->
## Contact
For questions or feedback, please contact : Hemant Patel   -
- Maild Id : hemant959singh@gmail.com

<h1 align="center">Thank You...<h1>
<h3 align = "center"> ***********************************************************<h3>
*  Job Search Portal
