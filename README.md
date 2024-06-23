# Task Management Application

## Introduction
This is a Full Stack Task Management application developed as an assignment for the Full Stack Developer position at PedalStart. The application allows users to create, view, update, and delete tasks with due dates and priority levels.

## Technologies Used
- **Frontend**: React.js, Axios, React Icons
- **Backend**: Node.js, Express.js, MongoDB
- **Styling**: CSS

## Features
- **User Authentication**: Secure user login and registration to manage access.
- **Add New Task**: Allows users to create new tasks with details like name, description, due date, and priority level.
- **View All Tasks**: Displays all tasks in a structured format with options to filter or sort.
- **Update Task**: Enables users to edit existing tasks to update information or status.
- **Delete Task**: Provides functionality to remove tasks from the task list.
- **Responsive Design**: Ensures the application works well on various devices, including desktops, tablets, and mobile phones.

## Prerequisites
- Node.js
- npm (Node Package Manager)
- MongoDB (local or Atlas)

## Installation

### Backend
1. Clone the repository:
   ```sh
   git clone https://github.com/Rishavvatsa/Taskify.git
   cd Client
2. Install the required dependencies:
 ```sh
   npm install
```
## API Endpoints
- Authentication
- POST /api/auth/register: Register a new user
- POST /api/auth/login: Log in an existing user
### Tasks
- GET /api/tasks: Get all tasks
- POST /api/tasks: Create a new task
- PUT /api/tasks/:id: Update a task
- DELETE /api/tasks/:id: Delete a task
