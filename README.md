# Hospital-Management-system
# Hospital Management System

A basic Hospital Management System built with Java (Servlets), HTML, CSS, and MySQL.

#Project Structure

- `frontend/`: Contains HTML, CSS, and JS files.
- `backend/`: Contains Java Servlet code, deployment descriptors, and Maven configuration.
- `sql/`: Database schema for MySQL.
- `README.md`: Project overview and setup instructions.

#How to Run

#1. Backend (Java)

- Install JDK and Apache Tomcat
- Open the project in an IDE (e.g., IntelliJ, Eclipse)
- Run with Apache Tomcat or build WAR and deploy to `/webapps`
- Or use Spring Boot with `mvn spring-boot:run` (if Spring)

#2. Frontend

- Open `frontend/index.html` in a browser
- Forms POST to backend servlet endpoints

#3. Database

- Use `sql/schema.sql` to set up MySQL database:
  ```sql
  CREATE DATABASE hospital_db;

HMS
