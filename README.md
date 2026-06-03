## Road Management System (RMS)



A **Spring Boot** application for managing road infrastructure for the Zambian Central and Local Government.



## Features

- **Spring Boot** framework with **Maven** build system.

- **MySQL** database integration.

- **Spring Security** for authentication and authorization.

- **Spring Data JPA** for database operations.

- Validation using **Spring Boot Starter Validation**.

- Development tools with **Spring Boot DevTools**.

- Unit and integration testing with **Spring Boot Starter Test** and **Spring Security Test**.

- **Lombok** for reducing boilerplate code.



## Requirements

- **Java 21** or higher.

- **Maven 3.8+**.

- **MySQL** database.



## Setup Instructions

1. Clone the repository:

   ```bash

   git clone <repository-url>

   cd rms

   ```



2. Configure the database:

   - Update the `application.properties` or `application.yml` file with your MySQL database credentials.



3. Build the project:

   ```bash

   mvn clean install

   ```



4. Run the application:

   ```bash

   mvn spring-boot:run

   ```



5. Access the application:

   - Default URL: `http://localhost:8080`



## Project Structure

- `src/main/java`: Contains the main application code.

- `src/main/resources`: Contains configuration files like `application.properties`.

- `src/test/java`: Contains test cases.



## Dependencies

- **Spring Boot Starter Web**: For building RESTful APIs.

- **Spring Boot Starter Data JPA**: For database operations.

- **Spring Boot Starter Security**: For security features.

- **Spring Boot Starter Validation**: For input validation.

- **MySQL Connector**: For MySQL database connectivity.

- **Lombok**: For reducing boilerplate code.

- **Spring Boot DevTools**: For development tools.

- **Spring Boot Starter Test**: For testing.



## License

This project is licensed under the **GNU Affero General Public License (AGPL)**. See the [AGPL License](https://www.gnu.org/licenses/agpl-3.0.html) for details.



## Contributor License Agreement

This project includes a `cla.md` file for contributors. Please review and sign the Contributor License Agreement before submitting any contributions.

