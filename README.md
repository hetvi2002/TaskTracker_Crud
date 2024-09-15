# Task Management System

## Overview

The Task Management System is a full-stack application designed for managing tasks efficiently. It features a backend API built with Go and a frontend interface developed using React. Users can create, view, update, and delete tasks with ease.

## Purpose

This project aims to provide a robust platform for organizing and tracking tasks. The system includes a user-friendly interface and a powerful backend to handle task management operations.

## Structure

- **Backend (Go):** Handles API requests, manages data interactions, and performs CRUD operations.
- **Frontend (React):** Provides an interactive user interface for managing tasks.

## Key Components

### Backend

- **Main Files:**
  - `main.go`: Entry point of the application, initializes the server and routes.
  - `controllers/`: Contains logic for handling API requests and responses.
  - `models/`: Defines data structures and interacts with the database.
  - `routes/`: Manages API routes and request routing.

- **Features:**
  - RESTful API for task management.
  - CRUD operations for tasks.
  - Database integration (e.g., PostgreSQL).

### Frontend

- **Main Files:**
  - `App.js`: Main React component that sets up routing and state management.
  - `components/TaskForm.js`: Component for adding and editing tasks.
  - `components/TaskList.js`: Component for displaying the list of tasks.
  - `services/api.js`: Axios configuration for making API requests.
  - `App.css` and `TaskList.css`: CSS files for styling components.

- **Features:**
  - User interface for task management with forms and lists.
  - Form validation and error handling.
  - Responsive design for various devices.

## Setup Instructions

### Backend

1. **Install Go:**
   - Follow the [official Go installation guide](https://golang.org/doc/install) to install Go on your machine.

2. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/task-management-system.git
   cd task-management-system/backend

3. **Install dependencies:**
   - go mod tidy

4. **Run the application:**
   - go run main.go

### Frontend

1. **Install Node:**
   - Follow the official Node.js installation guide to install Node.js and npm.

2. **Navigate to frontend directory:**
   ```bash
   cd task-management-system/frontend

3. **Install dependencies:**
   - npm install

4. **Run the application:**
   - npm start

### Usage

1. **Open the Application:**

  - Navigate to http://localhost:3000 in your browser to access the task management system.

2. **Create Tasks:**
  - Use the form to add new tasks.
    
3. **Edit Tasks:**
  - Click the "Edit" button next to a task to update it.

4. **Delete Tasks:**
  - Click the "Delete" button next to a task to remove it
