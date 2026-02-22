# FastAPI Note Management System with AWS RDS

A professional CRUD (Create, Read, Update, Delete) API built with FastAPI, using AWS RDS (PostgreSQL) as the cloud database.

## 🚀 Features

- **Cloud Database:** Integrated with Amazon RDS (PostgreSQL).
- **CRUD Operations:** Full support for creating, reading, updating, and deleting notes.
- **ORM:** Structured using SQLAlchemy for database interactions.
- **Schema Validation:** Data integrity ensured by Pydantic models.
- **Auto-generated Documentation:** Interactive API docs via Swagger UI.

## 🛠️ Tech Stack

- **Backend:** FastAPI (Python)
- **Database:** PostgreSQL (AWS RDS)
- **ORM:** SQLAlchemy
- **Server:** Uvicorn

## 📋 API Endpoints

| Method   | Endpoint      | Description                   |
| :------- | :------------ | :---------------------------- |
| `GET`    | `/notes`      | Fetch all notes from AWS RDS  |
| `POST`   | `/notes`      | Create a new note             |
| `PUT`    | `/notes/{id}` | Update an existing note by ID |
| `DELETE` | `/notes/{id}` | Delete a note by ID           |

## ⚙️ Setup & Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/BozgunBer-2506/RDS_demo.git](https://github.com/BozgunBer-2506/RDS_demo.git)
   cd RDS_demo
   ```
