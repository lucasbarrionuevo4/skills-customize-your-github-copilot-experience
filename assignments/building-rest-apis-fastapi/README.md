# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Implement a simple RESTful API using the FastAPI framework to practice request handling, data validation with Pydantic, and designing CRUD endpoints.

## 📝 Tasks

### 🛠️	Design and implement a REST API with FastAPI

#### Description
Create a small REST API for managing `items`. The API should expose endpoints to create, read, update, and delete items. Use Pydantic models for input validation and keep data in-memory for simplicity.

#### Requirements
Completed program should:

- Use FastAPI and Pydantic for models and validation.
- Implement endpoints: `GET /items`, `GET /items/{item_id}`, `POST /items`, `PUT /items/{item_id}`, `DELETE /items/{item_id}`.
- Return appropriate HTTP status codes (e.g., 201 for created, 404 for not found).
- Validate request bodies and return clear error messages for invalid input.
- Keep data in-memory (dictionary or list) — no external database required.
- Prevent duplicate item IDs and handle concurrency best-effort for the in-memory store.
- Include a simple `starter-code.py` in the assignment folder to help students get started.
