# FastAPI CRUD Task Management API

## Overview

A beginner-friendly REST API built with **Python and FastAPI** demonstrating CRUD (Create, Read, Update, Delete) operations with a SQLite database.

The project uses **SQLAlchemy** for database interaction and **Pydantic** for request validation. FastAPI's automatically generated Swagger documentation is used to test and explore the API.

> **Note:** This repository is a fork and learning adaptation of an open-source FastAPI CRUD project. The original MIT License and attribution have been retained.

## Features

* Create, read, update, and delete records
* RESTful API endpoints
* SQLite database
* SQLAlchemy ORM
* Pydantic validation
* Interactive Swagger API documentation
* Modular project structure using routers, models, and schemas

## Technologies

* Python
* FastAPI
* SQLAlchemy
* SQLite
* Pydantic
* Uvicorn

## Installation

Clone the repository:

```bash
git clone https://github.com/ayushkumardhall55-eng/task-management-api.git
cd task-management-api
```

Create and activate a virtual environment:

```bash
python -m venv env
```

On Windows:

```bash
.\env\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Run the Application

Start the FastAPI server:

```bash
uvicorn main:app --reload
```

Open the following URL in your browser:

```text
http://127.0.0.1:8000/docs
```

This opens the interactive Swagger API documentation.

## Project Structure

```text
task-management-api/
├── database/
├── models/
├── routers/
├── schemas/
├── main.py
├── requirements.txt
├── LICENSE
└── README.md
```

## API Operations

The API demonstrates the basic CRUD workflow:

| Method | Operation        |
| ------ | ---------------- |
| POST   | Create a record  |
| GET    | Retrieve records |
| PUT    | Update a record  |
| DELETE | Delete a record  |

## Attribution

This project is based on the open-source repository:

**FastAPI CRUD Todo with SQLite**
Original author: **lymanny**

Original repository:
https://github.com/lymanny/FastAPI-CRUD-Todo

The original project is licensed under the **MIT License**. The license and attribution have been retained in this repository.

## Purpose

This repository is maintained as a backend development learning project to practice **Python, FastAPI, REST APIs, CRUD operations, SQLAlchemy, SQLite, and API testing**.

