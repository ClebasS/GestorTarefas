# Task Manager API

A task management web application built with **FastAPI**, featuring a RESTful API, a Single Page Application (SPA) frontend, SQLite persistence, and automated testing.

This project was developed to practice backend development with FastAPI while also implementing a modern frontend using HTML, CSS, JavaScript, and the Fetch API.

---

## Features

* ✅ Create tasks
* ✏️ Edit tasks
* 🗑️ Delete tasks
* ✔️ Mark tasks as completed
* 📋 List all tasks
* 🎨 Responsive SPA interface
* 📝 Request logging
* ⚠️ Exception handling
* 🧪 Unit and API tests
* 📚 Automatic API documentation

---

## Technologies

### Backend

* Python 3
* FastAPI
* SQLite
* Jinja2
* Pydantic

### Frontend

* HTML5
* CSS3
* JavaScript (Fetch API)

### Testing

* Pytest
* HTTPX
* Pytest Coverage

---

## Project Structure

```text
TaskManager/
│
├── main.py                     
├── gestor_tarefas.py           
├── logger_config.py            
├── cli.py
├── database.py
├── tarefa.py
├── tarefa.db
├── tarefa.json
├── app.log
├── README.md
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── app.js
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

## Installation

Clone the repository:

```bash
git clone https://github.com/ClebasS/TaskManager.git
cd TaskManager
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it.

### Windows

```bash
.venv\Scripts\activate
```

### Linux / macOS

```bash
source .venv/bin/activate
```

Upgrade pip:

```bash
python -m pip install --upgrade pip
```

Install all dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Application

Start the FastAPI development server:

```bash
uvicorn main:app --reload
```

The application will be available at:

```
http://127.0.0.1:8000
```

---

## API Documentation

FastAPI automatically generates interactive documentation.

### Swagger UI

```
http://127.0.0.1:8000/docs
```

### ReDoc

```
http://127.0.0.1:8000/redoc
```

---

## Running Tests

Run all tests:

```bash
pytest
```

Generate a coverage report:

```bash
pytest --cov
```

---

## API Endpoints

| Method | Endpoint        | Description    |
| ------ | --------------- | -------------- |
| GET    | `/`             | Web interface  |
| GET    | `/tarefas`      | List all tasks |
| POST   | `/tarefas`      | Create a task  |
| PUT    | `/tarefas/{id}` | Update a task  |
| DELETE | `/tarefas/{id}` | Delete a task  |

---

## Current Functionality

* Create tasks
* Edit tasks
* Delete tasks
* Mark tasks as completed
* Request logging
* Exception handling
* SPA frontend
* RESTful API
* SQLite persistence
* Automated testing

---

## Learning Objectives

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

## Future Improvements

Some ideas for future development include:

* Role-based authorization (Admin/User)
* Email verification
* Password recovery
* Dark mode
* Pagination
* Drag-and-drop task organization
* Due dates
* Categories and tags
* Notifications
* Calendar integration
* CI/CD with GitHub Actions
* Docker Compose
* PostgreSQL
* Redis caching

---

## License

This project is intended for educational purposes and as a portfolio project.
