# Lab 5 – Postman and APIs

A Flask REST API for managing users in an SQLite database. The API supports CRUD operations and is tested using Postman.

## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | `/api/users` | Get all users |
| GET | `/api/users/<user_id>` | Get a user by ID |
| POST | `/api/users/add` | Add a new user |
| PUT | `/api/users/update` | Update a user |
| DELETE | `/api/users/delete/<user_id>` | Delete a user |

## Technologies

- Python
- Flask
- SQLite
- Postman
- Git & GitHub

## Run

Install the required packages:

```bash
pip install flask db-sqlite3 flask-cors