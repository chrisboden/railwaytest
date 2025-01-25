# FastAPI Railway Test App

A minimal FastAPI application for testing Railway deployment.

## Local Development

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Run the application:
```bash
uvicorn main:app --reload
```

The API will be available at http://localhost:8000

## Endpoints

- GET `/`: Returns a hello message 