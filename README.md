# :oncoming_taxi: my-taxi-service :oncoming_taxi:
___

### Project description:

``` 
A simple web-application that supports authentication, registration and other CRUD operations.
```

## Features:
___
* registration like a driver;
* authentication like a driver;
* create/update/remove a manufacturer;
* create/update/remove a car;
* create/update/remove a driver;
* display list of all manufacturers;
* display list of all cars;
* display list of all drivers;
* display list of all cars by current driver;
* add driver to car.

## Project structure (3-layer architecture):
___
* DAO - Data access layer
* Service - Application logic layer
* Controllers - Presentation layer

## Used technologies and libraries:
___
* Java 11
* Git
* Apache Maven
* Apache Tomcat
* Apache Log4j 2
* MySQL
* JDBC
* Javax Servlet
* JSP
* JSTL
* HTML/CSS
* Checkstyle plugin
* Project Lombok

## Steps to run the program on your computer:
___
* Clone the repo: [link to the repository](https://github.com/IDMFokin/my-taxi-service)
* Install MySQL;
* Configure Apache Tomcat version (IMPORTANT): 9.0.xx;
* Copy and run SQL script [follow this link](/src/main/resources/init_db.sql) to creating a schema and tables for the project;
* Configure [connection](/src/main/java/taxi/util/ConnectionUtil.java) with your URL, USERNAME, PASSWORD, JDBC_DRIVER;
* Configure [log4j2.xml](/src/main/resources/log4j2.xml) at line 7 with your ABSOLUTE_PATH to this project;
* Done. Now just try to use it.