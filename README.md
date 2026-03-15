# Student Backend

A Spring Boot REST API for managing students.

## Features

- Add, retrieve, update, and delete students
- CORS enabled for frontend at http://localhost:3000

## Prerequisites

- Java 21
- Maven 3.6+

## Installation

1. Clone the repository
2. Navigate to the project directory
3. Run `mvn clean install`

## Running the Application

`mvn spring-boot:run`

The application will start on port 8080.

## API Endpoints

- `POST /students` - Create a new student
- `GET /students` - Get all students
- `PUT /students/{id}` - Update a student by ID
- `DELETE /students/{id}` - Delete a student by ID

## Student Model

```json
{
  "id": 1,
  "name": "John Doe",
  "email": "john@example.com",
  "course": "Computer Science"
}
```