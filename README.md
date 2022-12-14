# Cinema App
This is a web application that allows you to purchase tickets for available movies, define user roles and provide access to cinema resources according to the role. Written using Spring and Hibernate frameworks.
## Features
- User registration and authentication (user/admin roles)

- Adding movies and cinema halls

- Searching for available movie sessions

- Adding tickets to shopping cart and making orders

- Information handling

## Technologies
- Spring MVC

- Spring Security

- MySQL

- Hibernate

- Tomcat (9.0.50)

- REST

- SOLID principles

## Project Structure
- Controller - accept http requests from users and display information

- Service - is responsible for the business logic of the application

- DAO - all the work with the database takes place at this level

## How launch the project:

- Fork this repository

- Clone this repository

- Configure resources -> "db.properties" file
  ```
    db.driver=YOUR_DRIVER
    db.url=YOUR_DATABASE_URL
    db.user=YOUR_LOGIN
    db.password=YOUR_PASSWORD
  ``` 
- Install Tomcat (9.0.50)

- Add Tomcat server to configuration

- Run the project