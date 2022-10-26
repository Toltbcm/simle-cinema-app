# **Simple-cinema-app**

## Description:

***This application is a simplified version of the cinema. It supports user registration,
authentication, authorization and CRUD operations over HTTP request***

## Features:

> - User registration and authentication
> - Possibility to be in the role of admin / user
> - Possibility to login / logout
> - Admin rights:
>   - add / see cinema halls
>   - add new / see available movies
>   - create / change / delete / see movie sessions
>   - find users by-email
> - User rights:
>   - see all the cinema halls
>   - see all the movies
>   - see available movie sessions
>   - add tickets to shopping cart
>   - complete the order

## Structure:

***The application has an N-Tier Architecture.***

> - Controllers layer - allows this application to communicate with users by receiving requests and
    sending responses
> - Service layer - responsible for the business logic of the application
> - Dao layer - responsible for performing database operations (CRUD operations)

## Used technologies:

> - Java 11
> - Maven
> - MySQL
> - Hibernate
> - Spring
> - TomCat 9.0.50

## Instruction for launching:

> - Fork this repository
> - Clone the repository to your PC
> - Edit db.properties to set the necessary parameters:
> ```
> db.driver=YOUR_DRIVER
> db.url=YOUR_URL
> db.user=YOUR_USERNAME
> db.password=YOUR_PASSWORD
>   ```
> - Install Tomcat
> - Edit configurations your local Tomcat server
> - Run the project
