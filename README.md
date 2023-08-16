# Full Stack Blogging Website
The project consists of two separate applications that run in parallel to each other:

A Spring Boot API, which serves as the back-end of the application. It handles all of the data requests and interactions with the database. The API is built using the Spring Boot framework, which makes it easy to create stand-alone, production-grade Spring applications. The API is also RESTful, which means that it uses HTTP verbs to define the actions that can be performed on resources. This makes it easy for the front-end application to communicate with the API.

A React front-end app, which is responsible for displaying the content of the website and handling user interactions. The front-end app is built using the React framework, which is a JavaScript library for building user interfaces. React is a popular choice for front-end development because it is easy to learn and use, and it is very efficient.
The two applications communicate with each other using HTTP requests. The front-end app makes requests to the API to get data, and the API sends responses back to the front-end app. This allows the front-end app to display the latest data to the user.

The two applications are decoupled, which means that they are not tightly coupled together. This makes the application more flexible and scalable. If one application needs to be updated, the other application does not need to be updated as well.

This is a common architecture for building web applications. It is a good choice for applications that need to be scalable and flexible.

## Spring-Boot Application
To get started, the back-end is built with Spring Boot, a popular Java framework for creating web applications. The API is built on a RESTful architecture, which allows for simple and efficient communication between the front-end and back-end. Spring Boot provides a variety of features, such as dependency injection, security, and simple database integration.

## POSTGRE
For the database, I chose PostgreSQL. PostgreSQL is a powerful, open-source, relational database management system (RDBMS) known for its reliability, robustness, and advanced features, such as support for JSON data types and full-text search. In this project, PostgreSQL is used as the primary database for storing all blog data, such as blog posts and author information.

PostgreSQL can be installed and configured on a server, which can be the same server as the Spring Boot API or a different server. For this project, let's assume that PostgreSQL is installed on the same server as the Spring Boot API but on a different port. By default, PostgreSQL listens on port 5432, but we can configure it to listen on a different port, such as 5433.

## Integrating the API with React App
To integrate PostgreSQL with a Spring Boot API, we can use the Spring Data JPA library. This library provides an easy way to interact with relational databases using Java objects. Spring Data JPA uses Hibernate as its underlying ORM (Object-Relational Mapping) framework. Hibernate maps Java objects to database tables and vice versa.

React hooks provide a way to consume APIs and convert the returned data into JSON format. This data can then be used by the components to render the UI.


This allows for easy storage and retrieval of all the blog data.
# BloggerApp
# BloggerApp
