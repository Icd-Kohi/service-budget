# Goal
Project goal:
``` 
    Make a web platform, that have users, and let the same users:
        1. Manage their company profiles (name, address, logo),
        2. Define predefined "Services" or products that the user company disposes.
        3. Create, manage and download as PDF budgets of services you're planning to send to clients, informing: client information, services to be done, discount (from 0% to 100%), and further observations.
```
Learning goal:

```
    1. Understand more about Full-stack web engineering:
    Auto SSL certificate generation and Reverse proxy with Caddy, 
    Authentication with OAuth2.0 + Google APIs and JWT,
    TODO... 
    


```
# Dividing and conquering

```
Backend:
    1. Think about and model the system flow.
    2. Think about and model the Database entities relationships.
    3. Implement all the models created as code.
    4. Wrap the project in a docker container.

Database: 
    1. Create the PostgreSQL database following the modeled entities and relationships.
    2. Wrap the database in a docker container.

Frontend:
    1. Think about and model the UI/UX design
        Why Angular is a good framework for this project?
        A: For the user perspective, it's better to navigate in a system that deliver pages instantly.
        A2: Wanted put in practice the use of a good, enterprise-grade frontend framework.
    2. Study a viable project structure in Angular.
    3. Implement the UI following the defined structure.
    4. Integrate the frontend with the backend APIs.
    5. Wrap the frontend in a docker container.

    ?. HTTPS certificate server with Caddy or Nginx.

COMPOSE THE WHOLE PROJECT WITH DOCKER COMPOSE.


```

# Stack

Frontend:
```
    Angular
        TODO ...
    Packages
        TODO...

Docker compose support
``` 
Backend:
```
    Java 21
        Lombok
        JDBC API
        Postgres Driver
        Java Mail Sender
        CycloneDX SBOM support
        
    Springboot 4.0.1
        Spring Web
        Data JPA
        Security
        Actuator

    PostgreSQL 16
    H2 (mocking, testing...)
    Docker compose support

    PDF Generation:
        Open-pdf 1.3.39
```
Others: HTTPS SSL certificate generation (Caddy, Nginx).

# System Architecture Modeling


# "Project File Tree" information


