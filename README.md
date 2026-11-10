# REST API for a Notes App

A RESTful Notes API built using **Python, Django REST Framework, and PostgreSQL**. This project allows users to create, read, update, and delete notes through REST API endpoints.

## Features

- Create new notes.
- Retrieve all notes.
- Retrieve a single note by ID.
- Update existing notes.
- Partially update notes.
- Delete notes.
- Input validation using DRF serializers.
- PostgreSQL database integration.
- Proper HTTP status codes.
- JSON-based API responses.

## Tech Stack

- Python
- Django
- Django REST Framework
- PostgreSQL
- psycopg
- Postman
- Git & GitHub

## Project Structure

```text
NotesApp/
│
├── config/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── notes/
│   ├── migrations/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── serializers.py
│   ├── views.py
│   ├── urls.py
│   └── tests.py
│
├── .env.example
├── .gitignore
├── manage.py
└── requirements.txt
```


## API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| POST | `/api/notes/` | Create a note |
| GET | `/api/notes/` | Get all notes |
| GET | `/api/notes/<id>/` | Get a single note |
| PUT | `/api/notes/<id>/` | Update a note |
| PATCH | `/api/notes/<id>/` | Partially update a note |
| DELETE | `/api/notes/<id>/` | Delete a note |

## Request Examples

## API Testing

All API endpoints were tested using **Postman** to verify CRUD operations, input validation, and HTTP responses.

## Learning Outcomes

- Understanding RESTful API architecture.
- Implementing CRUD operations using Django REST Framework.
- Working with PostgreSQL databases.
- Implementing serializer-based validation.
- Understanding HTTP methods and status codes.
- Testing APIs using Postman.

---

⭐ If you find this project useful, feel free to star the repository!
