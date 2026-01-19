# Python Backend Service

This service is a RESTful backend application developed using FastAPI
and designed to run as an independent microservice.

---

## Tech Stack

- Python 3.11
- FastAPI
- Uvicorn
- Docker
- Linux

---

## Features

- REST API endpoints
- Lightweight asynchronous framework
- Health check endpoint
- Containerized deployment
- Production-ready structure

---

## Endpoints

GET /
Returns service status.

---

## Run Locally

```bash
pip install -r requirements.txt
uvicorn main:app --reload
