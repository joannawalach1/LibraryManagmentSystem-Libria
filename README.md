# Libria - Library Management System

Welcome to the Libria project repository! Libria is a Library Management System developed as a team project. This system is built using Java 20, Spring Boot, Hibernate, and various other technologies to provide efficient library management capabilities.

## Technologies Used

- **Java 20:** Utilizing the latest features of the Java programming language.
- **Spring Boot:** A powerful framework for building Java-based enterprise applications.
- **Hibernate:** An object-relational mapping framework for the Java programming language.
- **REST Controllers:** Used for building RESTful web services to handle HTTP requests.
- **JUnit and Mockito:** Employed for testing purposes, ensuring code reliability and functionality.
- **Mock MVC:** Used for testing Spring MVC controllers.
- **Basic SQL:** Fundamental SQL for database interactions.
- **Maven:** A build automation tool for managing the project's build lifecycle.
- **IntelliJ IDEA:** The integrated development environment used for coding and development.
- **Basic Authentication:** Implemented for enhanced security.
- **PostgreSQL:** Chosen as the primary relational database for robust data storage.
- **Liquibase:** Ensured version-controlled database schema updates and management.
- **Bitbucket:** The version control system utilized for source code management.
- **Pull Requests and Code Review:** Best practices for collaborative development and maintaining code quality.
- **GIT:** Version control system for tracking changes in the source code.

## Project Highlights

- **Swagger Documentation:** Integrated Swagger for clear and concise API documentation, facilitating easier integration and understanding.
- **Exception Handling:** Established a robust exception handling mechanism to enhance the application's fault tolerance.
- **Basic Authentication:** Implemented for enhanced security during user interactions.
- **Entity Relationships:** Managed relationships between entities to ensure data consistency and integrity.
- **PostgreSQL Database:** Utilized PostgreSQL as the relational database for robust data storage.
- **Liquibase Database Schema Management:** Applied Liquibase for efficient database schema management.

## Testing

Conducted thorough JUnit and Mockito tests to validate the application's functionality and error-handling capabilities.

## Bitbucket Repository

The source code for this project is hosted on Bitbucket. You can access it [here](https://bitbucket.org/goreit1/libria1/src/develop/).

## Getting Started

To set up and run Libria on your local machine, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://bitbucket.org/goreit1/libria1.git
    ```

2. **Navigate to the project directory:**
    ```bash
    cd libria1
    ```

3. **Build the project using Maven:**
    ```bash
    mvn clean install
    ```

4. **Create a PostgreSQL database:**
    - Create a PostgreSQL database named `libria_db`.
    - Update the database configuration in the `application.properties` file if needed.

5. **Run Liquibase for database migrations:**
    ```bash
    mvn liquibase:update
    ```

6. **Run the application:**
    ```bash
    mvn spring-boot:run
    ```

7. **Access the application:**
    Open your web browser and go to [http://localhost:8080](http://localhost:8080) to start using the Libria Library Management System.

These steps ensure that the project is built, dependencies are resolved, the database is set up, and the application is running locally. Customize the database configuration and other properties as needed for your environment.
