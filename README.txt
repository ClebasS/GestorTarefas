# Task Manager API

A Task Manager web application built with **FastAPI**, featuring a REST API, a simple SPA frontend, SQLite persistence, and automated tests.

## Features

* Create tasks
* Edit tasks
* Delete tasks
* Mark tasks as completed
* List all tasks
* Responsive HTML/CSS frontend
* JavaScript SPA using the Fetch API
* SQLite database
* Logging middleware
* RESTful API
* Unit and API tests with Pytest

---

# Technologies

* Python 3
* FastAPI
* SQLite
* Jinja2 Templates
* HTML5
* CSS3
* JavaScript (Fetch API)
* Pytest

---

# Project Structure

```text
GestorTarefas/
│
├── main.py                    
├── gestor_tarefas.py           
├── logger_config.py            
├── cli.py
├── database.py
├── tarefas.py
├── tarefas.db
├── tarefas.json
├── README.md
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── scripts/
│       ├── app.js
│
├── templates/
│   ├── index.html
│
├── tests/
│   ├── test_api.py
│   ├── test_gestor_tarefas.py
│   └── test_tarefa.py
```

---

# Installation

Clone the repository:

```bash
git clone https://github.com/ClebasS/GestorTarefas.git
cd GestorTarefas
```

Create and activate a virtual environment.

### Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

Upgrade pip:

```bash
python -m pip install --upgrade pip
```

Install the required packages:

```bash
pip install fastapi uvicorn jinja2 httpx pytest pytest-cov
```

---

# Running the Application

Start the development server:

```bash
uvicorn main:app --reload
```

The application will be available at:

```
http://127.0.0.1:8000
```

Interactive API documentation:

```
http://127.0.0.1:8000/docs
```

Alternative ReDoc documentation:

```
http://127.0.0.1:8000/redoc
```

---

# API Documentation

FastAPI automatically generates interactive documentation.

```Swagger UI
http://127.0.0.1:8000/docs
```ReDoc
http://127.0.0.1:8000/redoc
```

---

# Running Tests

Run all tests:

pytest

Generate a coverage report:

pytest --cov
```

---

# API Endpoints
Method	Endpoint	Description
GET	/	Web interface
GET	/tarefas	List all tasks
POST	/tarefas	Create a task
PUT	/tarefas/{id}	Update a task
DELETE	/tarefas/{id}	Delete a task
```

---

# Current Functionality

* Create new tasks
* Edit existing tasks
* Delete tasks
* Mark tasks as completed
* View all tasks
* Logging of HTTP requests
* Exception handling
* REST API
* SPA frontend

---

# Learning Objectives

This project was created to practice:

* REST API development
* FastAPI
* Clean project architecture
* CRUD operations
* Database integration
* Frontend development
* Asynchronous JavaScript
* Unit testing
* API testing
* Logging
* Software engineering best practices

---

# Planned Improvements

The project is currently under active development. Planned features include:

* User authentication with JWT
* User registration and login
* Password hashing
* Task filtering
* Task searching
* Task sorting
* Dashboard with statistics
* User-specific tasks
* History of task changes
* File attachments
* Docker support
* PostgreSQL support
* Deployment to a cloud platform

---

# Testing

The project includes:

* Unit tests
* API endpoint tests
* Code coverage reports using Pytest Coverage

---

# License

This project is intended for educational and portfolio purposes.
