# The-Simple-Shop-GmbH
The Simple Shop GmbH is a local dealer for nearly every product available.

Initial Setup and Basic Configuration of the Online Store Project:

1. Environment Setup:
   - Established a Java development environment with Spring Boot and PostgreSQL.
   - Prepared the development tools and IDE necessary for Java development.

2. Spring Boot Project Creation:
   - Generated a new Spring Boot project using Spring Initializr with essential dependencies:
     - Spring Web
     - Spring Data JPA
     - PostgreSQL Driver
     - Spring Security
     - Validation
     - Lombok

3. Project Structuring:
   - Defined the project package structure following best practices and separation of concerns:
     - controller
     - service
     - repository
     - entity
   - Created basic entity classes for `Product`, `Order`, and `Customer`.

4. Database Configuration:
   - Added connection properties for PostgreSQL in `application.properties`.
   - Configured Spring Data JPA with basic repositories for entities.

5. Basic API Endpoints Development:
   - Implemented a health check endpoint (`/health`) to test the application's availability.
   - Created a basic POST endpoint (`/products`) for adding products to the catalog, with simulated functionality.

The initial commit establishes the foundation of the project for the online store system. It includes initial setup, package structure, and basic API endpoints for future expansions and database integrations.

