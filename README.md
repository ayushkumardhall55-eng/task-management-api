# FastAPI CRUD Task Management API

A beginner-friendly REST API built with Python and FastAPI to demonstrate CRUD operations with SQLite. The project uses SQLAlchemy for database interaction and Pydantic for data validation.

## Overview

This project is a simple Task Management REST API that allows users to create, retrieve, update, and delete task records.

It demonstrates the basic structure of a backend application using FastAPI, SQLAlchemy, SQLite, and Pydantic.

## Features

- Create new tasks
- Retrieve task records
- Update existing tasks
- Delete tasks
- SQLite database integration
- SQLAlchemy ORM
- Pydantic data validation
- Interactive Swagger API documentation

## Tech Stack

| Technology | Purpose |
|---|---|
| Python | Backend programming |
| FastAPI | REST API framework |
| SQLAlchemy | Database ORM |
| SQLite | Database |
| Pydantic | Data validation |
| Uvicorn | Application server |

## Project Structure

## Project Structure

task-management-api/
│
├── database/
├── models/
├── routers/
├── schemas/
├── main.py
├── requirements.txt
├── README.md
└── LICENSE

## Getting Started

### 1. Clone the repository

git clone https://github.com/ayushkumardhall55-eng/task-management-api.git

cd task-management-api

### 2. Create a virtual environment

python -m venv venv

### 3. Activate the virtual environment

Windows:

venv\Scripts\activate

macOS/Linux:

source venv/bin/activate

### 4. Install dependencies

pip install -r requirements.txt

### 5. Run the application

uvicorn app.main:app --reload

The API will be available at:

http://127.0.0.1:8000

## API Documentation

FastAPI provides interactive API documentation through Swagger UI.

Open:

http://127.0.0.1:8000/docs

You can use Swagger UI to test the available API endpoints directly from your browser.

## CRUD Operations

| HTTP Method | Operation | Purpose |
|---|---|---|
| POST | Create | Add a new task |
| GET | Read | Retrieve task records |
| PUT | Update | Modify an existing task |
| DELETE | Delete | Remove a task |

## Learning Objectives

This project was used to practice:

- REST API development
- FastAPI application structure
- CRUD operations
- Database integration
- SQLAlchemy ORM
- Pydantic validation
- API testing using Swagger UI

## Attribution

This project is adapted from an open-source FastAPI CRUD Todo project by lymanny.

Original project:

https://github.com/lymanny/FastAPI-CRUD-Todo

The original MIT License and copyright notice are retained in this repository.

## License

This project is licensed under the MIT License.

See the LICENSE file for details.
