# FastAPI Social Network

A RESTful social network API built with FastAPI — users, posts, photos, and comments. No frontend, API-only.

## Features
- User registration and authentication (JWT)
- Create and browse posts
- Photo upload and management
- Comment system
- Auto-generated interactive docs (Swagger UI at `/`)

## Tech Stack
- Python 3.11+
- FastAPI
- SQLAlchemy
- SQLite

## Setup
```bash
pip install -r requirements.txt
uvicorn main:app --reload
```

API docs available at [http://localhost:8000](http://localhost:8000)