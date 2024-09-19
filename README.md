# Online Examination System
An Online Examination System built using Java, JSP, Servlets, JDBC, and MySQL. This project aims to provide a platform for conducting online exams with features like user registration, login, exam creation, question management, and result evaluation.

### Table of Contents
* Features
* Technologies Used
* Installation
* Database Setup
* Usage
* Project Structure
* Contributing
### Features
* User Authentication (Registration, Login, Logout)
* Role-based access (Admin and Student)
* Admin can create, update, and delete exams and questions
* Students can attempt exams and view results
* Timer functionality for exams
* Real-time score calculation and result display
### Technologies Used
* Frontend: HTML, CSS, JavaScript, JSP
* Backend: Java Servlets
* Database: MySQL
* Server: Apache Tomcat
* JDBC: Database connectivity
* IDE: Eclipse/IntelliJ IDEA/NetBeans
### Installation
* Prerequisites
* Java JDK 8 or above (preferably JDK 20)
* Apache Tomcat Server (version 9 or above)
* MySQL Server
* IDE (Eclipse/IntelliJ IDEA/NetBeans)
### Steps
* 1.Clone the repository
* git clone https://github.com/your-username/online-examination-system.git
* 2.Open the project in your preferred IDE.

* 3.Configure Apache Tomcat in your IDE.

* 4.Set up the MySQL database as described below.

* 5.Build the project and deploy it on the Tomcat server.

### Database Setup
* 1.Create a MySQL Database

* CREATE DATABASE online_exam;
* 2.Create tables required for the system using the provided SQL scripts in the /sql folder of the project.

* 3.Update the database configuration in dbConfig.java (or equivalent configuration file):

* private static final String URL = "jdbc:mysql://localhost:3306/online_exam";
* private static final String USER = "your-username";
* private static final String PASSWORD = "your-password";
### Usage
* Start the Apache Tomcat server.

* Open your web browser and navigate to http://localhost:8080/online-examination-system.

* Use the admin credentials to log in as an administrator or register as a new student to attempt exams.

### Project Structure
* online-examination-system/
* │
* ├── src/
* │   ├── main/
* │   │   ├── java/
* │   │   │   ├── com.exam.controller/  # Servlets
* │   │   │   ├── com.exam.dao/         # Data Access Objects (JDBC)
* │   │   │   └── com.exam.model/       # Models
* │   │   ├── webapp/
* │   │   │   ├── WEB-INF/
* │   │   │   │   └── web.xml           # Deployment Descriptor
* │   │   │   ├── jsp/                  # JSP pages
* │   │   │   └── assets/               # CSS, JS, images
* │   └── test/                         # Test cases (if any)
* │
* ├── sql/
* │   └── db_schema.sql                 # SQL scripts for database setup
* │
*├── README.md
* └── pom.xml (if using Maven)
### Contributing
* Contributions are welcome!
*  Please fork the repository and submit a pull request for any improvements.
