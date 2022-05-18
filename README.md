# Taxi Service Web Application
It's a simple taxi service web application, which simulates the work of a taxi service and supports authentication and interaction with the database.

### Functional:
- Display all Drivers
- Display all Cars
- Display all Manufacturers
- Create new Driver
- Create new Car
- Create new Manufacturer
- Add driver to car

### 3-layer architecture:
- DAO - Data access layer
- Service - Application layer
- Controllers - Presentation layer

### Technologies:
- Java 11
- Apache Tomcat - version 9.0.50
- MySQL
- JDBC
- Servlet
- JSTL
- JSP
- HTML, CSS

### How to run this application
1. Install MySQL
2. Install Tomcat 9.0.50 version
3. Fork this project to your repository
4. Clone it using one of the "Code" options, which is more suitable for you
5. In resources directory you can find init_db.sql file. Use it to initialize you database
6. Add some data to DB
7. Go to the ConnectionUtil class located in src/main/java/taxi/util and add your url to DB, login, password and JDBC driver there.
   (Be careful with adding URL. You should add a Timezone to it too)
8. Configure your Tomcat. (P.S. Your application context needs to be as "/")
9. Run this project using Tomcat's local server



