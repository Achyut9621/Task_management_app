# Task Management App

A RESTful backend application built with FastAPI and PostgreSQL to manage tasks efficiently. The application supports task CRUD operations, database integration, and JWT-based authentication and authorization.

## Tech Stack

| Technology | Purpose |
|---|---|
| Python | Programming language |
| FastAPI | Backend framework for building REST APIs |
| PostgreSQL | Relational database for persistent data storage |
| SQLAlchemy | ORM for database operations |
| JWT | Authentication and authorization |
| Postman | API testing and validation |

## Features

- Create, retrieve, update, and delete tasks (CRUD operations).
- JWT-based authentication and authorization.
- PostgreSQL database integration using SQLAlchemy.
- Modular project structure for maintainability.
- API testing using Postman.

## Project Structure

```text
Task_management_app/
├── main.py
├── requirement.txt
├── src/
│   ├── tasks/
│   ├── user/
│   └── utils/
└── .gitignore
```

*Update the folder structure above to match your actual project.*

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/Achyut9621/Task_management_app.git
cd Task_management_app
```

### 2. Create and activate a virtual environment

```bash
python -m venv env
```

Windows PowerShell:

```powershell
.\env\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
pip install -r requirement.txt
```

### 4. Configure environment variables

Create a `.env` file in the project root and configure the required database credentials and JWT settings. Refer to your application configuration for the exact variable names.

### 5. Run the application

```bash
uvicorn main:app --reload
```

## API Testing

Use Postman to test API endpoints, including authentication and task management operations.

## Future Enhancements

- Develop a frontend interface.
- Deploy the application to a cloud platform.

---

**Developed by Achyut9621**
