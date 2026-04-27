# testing-app

A simple FastAPI application with basic endpoints.

## Endpoints

- `GET /` - Returns a hello message
- `GET /health` - Returns health status

## Setup

```bash
pip install -r requirements.txt
```

## Running Locally

```bash
uvicorn app:app --reload
```

## Running with Docker

```bash
docker build -t testing-app .
docker run -p 8000:8000 testing-app
```