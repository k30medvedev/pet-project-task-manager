# pet-project-task-manager
task-manager
Here is a brief technical specification for a simple REST project using Java, Spring, PostgreSQL, and Docker:

    Functional Requirements

    Develop a REST API for creating, reading, updating, and deleting "User" and "Task" entities.
    Each user can create multiple tasks.
    Each task is associated with one user.
    A task has a title, description, and due date.
    Users should be able to view their tasks, as well as create, update, and delete them.

    Technical Requirements

    The project should be implemented in Java 8 or above.
    Use Spring Boot to create the REST API.
    Use PostgreSQL for data storage.
    Each request should be processed in a separate thread.
    Package the project into a Docker container and launch it using docker-compose.

    Project Structure

    Organize the code into packages and classes following SOLID principles.
    Classes should be covered with unit tests.
    Use Maven or Gradle for dependency management and project build.

    Documentation

    Create documentation for the REST API using Swagger or similar tools.
    The description of the REST API should be accessible via the "/api-docs" URL.

    Deployment

    Use docker-compose for deploying the project.
    The docker-compose.yml file should contain configurations for PostgreSQL and the application.
    The application should be accessible at "http://localhost:8080".
