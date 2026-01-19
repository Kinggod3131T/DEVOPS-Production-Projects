# Go Backend Service

This service is a lightweight REST API written in Go and designed to run as an
independent microservice in a containerized environment.

---

## Tech Stack

- Go 1.22
- net/http
- Docker
- Linux

---

## Features

- High-performance HTTP server
- Concurrent request handling using goroutines
- Minimal runtime dependencies
- Fast startup and low memory usage
- Containerized deployment

---

## API Endpoint

GET /
Returns service running status.

---

## Run Locally

```bash
go run main.go
