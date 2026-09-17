# FastAPI CRUD Task Management API

A beginner-friendly REST API built with **Python and FastAPI** to demonstrate CRUD operations with a SQLite database. The project follows a modular backend structure and uses SQLAlchemy for database interaction and Pydantic for data validation.

## Overview

This project demonstrates the fundamentals of building a RESTful API using FastAPI. It provides endpoints to create, retrieve, update, and delete task records stored in a SQLite database.

The API can be tested and explored through FastAPI's automatically generated **Swagger UI**.

## Features

* Create task records
* Retrieve task records
* Update existing task records
* Delete task records
* SQLite database integration
* SQLAlchemy ORM for database operations
* Pydantic-based data validation
* Interactive Swagger API documentation
* Modular application structure

## Tech Stack

| Technology | Purpose             |
| ---------- | ------------------- |
| Python     | Backend programming |
| FastAPI    | REST API framework  |
| SQLAlchemy | Database ORM        |
| SQLite     | Database            |
| Pydantic   | Data validation     |
| Uvicorn    | Application server  |

## Project Structure

```text
task-management-api/
│
├── database/
│   └── ...
├── models/
│   └── ...
├── routers/
│   └── ...
├── schemas/
│   └── ...
├── main.py
├── requirements.txt
├── LICENSE
└── README.md
```

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/ayushkumardhall55-eng/task-management-api.git
cd task-management-api
```

### 2. Create a virtual environment

```bash
python -m venv env
```

### 3. Activate the environment

**Windows:**

```bash
.\env\Scripts\activate
```

**macOS/Linux:**

```bash
source env/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the application

```bash
uvicorn main:app --reload
```

The API will be available at:

```text
http://127.0.0.1:8000
```

## API Documentation

FastAPI automatically provides interactive API documentation.

Open:

```text
http://127.0.0.1:8000/docs
```

From Swagger UI, you can view the available endpoints and send requests directly to the API.

## CRUD Operations

The application demonstrates the following REST operations:

| HTTP Method | Operation | Purpose                 |
| ----------- | --------- | ----------------------- |
| POST        | Create    | Add a new task          |
| GET         | Read      | Retrieve task records   |
| PUT         | Update    | Modify an existing task |
| DELETE      | Delete    | Remove a task           |

## Learning Objectives

This project was used to practice:

* Designing REST API endpoints
* Working with FastAPI routes
* Connecting an API to a relational database
* Performing CRUD operations
* Using SQLAlchemy for database interaction
* Validating API request data with Pydantic
* Testing endpoints using Swagger UI
* Organizing a Python backend application into separate modules

## Attribution

This repository is a fork and learning adaptation of an open-source FastAPI CRUD project.

The original project was created by **lymanny** and is licensed under the **MIT License**. The original license and attribution have been retained in this repository.

## License

This project is distributed under the **MIT License**. See the `LICENSE` file for details.
