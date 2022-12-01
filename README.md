# Taxi-service
It is a web application. You can register, and then you have access to CRUD operations with drivers, cars and manufacturers.
It supports authentication so it's safe. Based on SOLID.

# Features:
- Create new driver
- Create new manufacturer
- Create new car
- Add driver to the car
- Display all my cars
- Display all drivers
- Display all cars
- Display all manufacturers

# Architecture:
3-tire architecture: 
- Presentation layer
- Services layer
- DAO layer.

# Technologies:
- JDK 11
- Tomcat 9.0.50
- JSP
- Servlet
- JSTL
- Dependency injection
- MySql
- HTML/CSS

# Instructions:

1. Clone the project from GitHub
2. Use [init_db.sql](https://github.com/HryhorashPavlo/taxi-service/blob/f559328ab4b0e4d5e874bfeead9a1ce0408296cd/src/main/resources/init_db.sql) file to create schema and tables
3. Install Apache Tomcat 9.0.50
4. Edit [ConnectionUtil.java](https://github.com/HryhorashPavlo/taxi-service/blob/f559328ab4b0e4d5e874bfeead9a1ce0408296cd/src/main/java/taxi/util/ConnectionUtil.java#L9) file for access to your DB 
5. Edit run configurations with local Tomcat server

# UML Diagram:

![Image](https://github.com/HryhorashPavlo/taxi-service/blob/59e3b64f5dc41236ac1b6ce4022f8abbf645d62f/img/uml.png)


