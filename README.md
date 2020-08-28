"# Onlineshop" 
   
This is a simple representation of online store
 
## Description

The store model has role based authorization and authentication with USER and ADMIN roles. <br />

Registration, log in/log out options are also implemented. 
Password storing securely in DB as hash-password (SHA-512 + salt).

USER can look through the list of products, add chosen product to a cart, delete items from cart 
and complete an order. 
USER also can review all completed orders. <br />
ADMIN can add/delete products to/from a list of products and overview the list of all users.

## Prerequisites

To run this project you need to install next software: 
* [Java 13](https://www.oracle.com/technetwork/java/javase/downloads/jdk11-downloads-5066655.html) - 
Development environment 
* [Maven](https://maven.apache.org/) - Dependency Management
* [Tomcat](http://tomcat.apache.org/) - Web Server
* [MySQL](https://www.mysql.com/) - Database

## Technologies used

*  MavenCheckstylePlugin 3.1.0
*  javax.servlet 3.1.0
*  javax.jstl 1.2
*  mysql-connector-java 8.0.18
*  log4j 1.2.17

## Deployment

Add this project to your IDE as Maven project.

Add Java SDK 13 in project structure.

Configure Tomcat:
- Add artifact
- Add Java SDK 13
 
To work with MySQL you need to:
- Create schema and tables (use sql requests in **src/main/resources/init_db.sql** )
- Use your user and password from MySql DB.

## Author
 [Setrina Olesia](setrina527@gmail.com)
If you have questions - feel free to write me.


