# Task Tracker

A simple task management web application built with **Spring Boot** for the backend and **HTML/JavaScript** for the frontend. The application allows users to add tasks, mark them as done, delete tasks, and filter tasks based on their status (Pending or Done). The tasks are stored in the browser's local storage to persist across page reloads.

## Features

- Add a task with a title and description.
- Mark tasks as "Done" or "Undo" the task status.
- Delete tasks.
- Filter tasks by status: All, Pending, or Completed.
- Tasks are stored in the browser’s local storage.

## Tech Stack

- **Backend**: Spring Boot (Java)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: In-memory H2 database (for API use)
- **API Documentation**: Swagger (OpenAPI)

## Backend

### Project Setup

1. **Clone this repository** or **download the zip file**.
2. **Open the project** in an IDE like IntelliJ or Eclipse.
3. **Build the project** using Maven (`mvn clean install`).
4. **Run the Spring Boot application**:  
   `mvn spring-boot:run`

The backend will be accessible on `http://localhost:8080`.

### API Endpoints

- `POST /tasks`: Create a new task.
- `GET /tasks`: Get all tasks.
- `PUT /tasks/{id}`: Update a task.
- `DELETE /tasks/{id}`: Delete a task.
- `GET /tasks/status/{status}`: Filter tasks by status (Pending or Done).

### API Documentation

You can view the API documentation using **Swagger UI** at:

- `http://localhost:8080/swagger-ui.html`

### Dependencies

- **Spring Web**
- **Spring Data JPA**
- **Spring Boot DevTools**
- **H2 Database**
- **Lombok**
- **Spring Validation**
- **Springdoc OpenAPI**

## Frontend

The frontend is a simple HTML page that provides an interactive interface to manage tasks. The tasks are stored in the browser's **localStorage**, so the data persists even after a page reload.

### Features in the Frontend:

- **Add Task**: Enter the title and description, then click the button to add a new task.
- **Mark as Done**: Tasks can be marked as "Done" and visually crossed out.
- **Delete Task**: Delete any task.
- **Filter**: Filter tasks by status—All, Pending, or Done.

### How to Use

1. Open the `index.html` file in any browser.
2. Use the form to add new tasks.
3. Mark tasks as done or delete them as needed.
4. Filter tasks by their status.

## How to Run Locally

1. **Backend**:
    - Ensure Java and Maven are installed.
    - Open the project in an IDE or terminal.
    - Run `mvn spring-boot:run` to start the backend.

2. **Frontend**:
    - Open the `index.html` file directly in a web browser.

## Future Enhancements

- Add authentication and user management.
- Integrate backend with the frontend to persist tasks in a real database.
- Deploy the application to a cloud service like AWS or Heroku.

## ScreenShots
![Screenshot (133)](https://github.com/user-attachments/assets/ea42597e-9ab4-4586-bbf6-cb4c3e13902c)

![Screenshot (134)](https://github.com/user-attachments/assets/810f57e8-c34f-42c1-ab9c-f8f8427b009c)

![Screenshot (135)](https://github.com/user-attachments/assets/0b5c866e-7091-4c07-b245-deef0f0c967d)

![Screenshot (136)](https://github.com/user-attachments/assets/cc49b611-7773-4457-bfa1-5c7e3c2f6caf)
