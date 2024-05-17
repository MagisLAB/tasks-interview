# Task Management Application

## Overview

This is a simple task management application built with Django for the backend and React for the frontend. The application allows users to manage a list of tasks with titles, descriptions, and completion statuses.

## Features

- Django backend with REST API for managing tasks
- React frontend to fetch and display tasks
- Unit tests for Django models
- Integration tests for React components

## Setup Instructions

### Backend (Django)

1. **Clone the repository**:
   ```bash
   git clone https://github.com/MagisLAB/tasks-interview.git
   cd tasks-interview
   ```

2. **Create a virtual environment and activate it**:
   ```bash
   python3 -m venv env
   source env/bin/activate
   ```

3. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the migrations**:
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser** (optional, for accessing Django admin):
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server**:
   ```bash
   python manage.py runserver
   ```

### Frontend (React)

1. **Navigate to the frontend directory**:
   ```bash
   cd frontend
   ```

2. **Install the required dependencies**:
   ```bash
   npm install
   ```

3. **Start the React development server**:
   ```bash
   npm start
   ```

## Interview Steps

### Theory-Based Questions

1. Explain the Model-View-Controller (MVC) architecture and how Django fits into this architecture.
2. What are Django’s key features and why is it popular for web development?
3. What is the difference between unit testing and integration testing?
4. Explain the role of middleware in a Django application.
5. Describe the lifecycle of a React component.

### Coding Exercise (30 Minutes)

#### Part 1: Django Backend

1. Create a Django model for the task.
2. Create a serializer for the task.
3. Create a view to handle the API requests.
4. Add the API endpoint to the URL configuration.
5. Write a unit test for the Task model.

#### Part 2: React Frontend

1. Create a React component to fetch and display the tasks.
2. Write a test for the React component using Jest and React Testing Library.

## Testing

### Backend (Django)

To run the Django unit tests:
```bash
python manage.py test
```

### Frontend (React)

To run the React tests:
```bash
npm test
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
