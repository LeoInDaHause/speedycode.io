# Speedy Code (Project for OOP at the National University of Colombia)

This is a small project about a web page that helps you improve your programming skills and become faster at typing. If you want to contribute to this project, don’t be shy—feel free to make a pull request! :D

## Dependencies

This project is a web app. For the backend, we use Java. While Java may not be the most common choice for web development, we are learning Java and Object-Oriented Programming, so we decided it is the best fit for this project. For the frontend, we use HTML, CSS, and JavaScript. 

The dependencies are:

1. Java 22 JDK (either OpenJDK or Oracle JDK)
2. Maven for managing library dependencies
3. [Spring Boot framework](https://spring.io/projects/spring-boot) with the following additional libraries:
    * Spring Web
    * Spring Data JPA
    * Spring H2 Database
    * Thymeleaf
    * Spring Boot DevTools

## How to Run the Project

We recommend using an IDE like IntelliJ IDEA or Eclipse, but you can use any IDE you prefer. One of the developers uses VSCode with the Java Extension Pack and the Spring Boot Extension Pack.

1. Clone the repository:
    ```bash
    git clone https://github.com/LeoInDaHause/speedycode.git
    ```
2. Open the project in your IDE.
3. Run the project.
4. Open your browser and go to [http://localhost:8080](http://localhost:8080).
5. Open the Database Console at [http://localhost:8080/h2](http://localhost:8080/h2-console). The Dtabase has a default configuration:
    * JDBC URL: jdbc:h2:mem:testdb
    * User Name: sa (default can [custom] in the property "spring.datasource.username = sa"(https://github.com/LeoInDaHause/speedycode/blob/main/target/classes/application.properties) at application.properties)
    * Password: (Default has none password but you can [custom](https://github.com/LeoInDaHause/speedycode/blob/main/target/classes/application.properties)() in the property "spring.datasource.username = sa")


