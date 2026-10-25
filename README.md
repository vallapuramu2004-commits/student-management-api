
# Student Management REST API

A RESTful API built using Java, Spring Boot, and MySQL to manage student records.

## Technologies Used

- Java 21
- Spring Boot
- Spring Data JPA
- MySQL
- Maven
- Swagger UI / OpenAPI

## Features

- Create a student
- Retrieve all students
- Retrieve a student by ID
- Update student details
- Delete a student
- Validate required fields and email format
- Handle API errors
- Test endpoints using Swagger UI

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/students` | Get all students |
| GET | `/api/students/{id}` | Get a student by ID |
| POST | `/api/students` | Create a student |
| PUT | `/api/students/{id}` | Update a student |
| DELETE | `/api/students/{id}` | Delete a student |

## Database Configuration

Create a MySQL database named `student_management`.

Configure these environment variables before running the application:

- `DB_USERNAME` — your MySQL username
- `DB_PASSWORD` — your MySQL password

Never commit real database passwords or other secrets to GitHub.

## Run Locally

1. Install Java 21 and MySQL.
2. Configure the database credentials as environment variables.
3. Open a terminal in the project directory.
4. Run the application:

   ```powershell
   .\mvnw.cmd spring-boot:run
   ```

5. Open Swagger UI:

   http://localhost:8080/swagger-ui/index.html

## Project Structure

- `src/main/java` — application source code
- `src/main/resources` — application configuration
- `src/test/java` — test source code
- `pom.xml` — Maven dependencies and build configuration

## Author

Ramu Vallepu
