auth-microservice/
│── app/
│   ├── __init__.py
│   ├── main.py          # FastAPI entry point
│   ├── models.py        # SQLAlchemy models
│   ├── schemas.py       # Pydantic schemas
│   ├── database.py      # DB connection
│   ├── auth.py          # Authentication logic (JWT, hashing)
│── requirements.txt
│── Dockerfile
│── .env


dependeis


fastapi
uvicorn
sqlalchemy
psycopg2-binary
python-jose[cryptography]
passlib[bcrypt]
python-dotenv
