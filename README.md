Features:
-Full CRUD Operations (Create, Read, Update, Delete)
-Database Integration with PostgreSQL and SQLAlchemy ORM
-Data Validation using Pydantic models with custom rules
-Structured Error Handling (HTTP 404, 500, etc.)
-Partial Updates (PATCH) & Full Updates (PUT)
-Nested JSON Models (Student + Address)

Project Structure
student-api/
├── models.py           # Database models
├── schemas.py          # Pydantic schemas
├── database.py         # DB connection
├── main.py             # API routes
├── requirements.txt    # Dependencies
└── README.md
