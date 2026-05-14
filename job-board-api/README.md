# Job Board REST API

Production-grade Spring Boot 3 REST API for a job board platform with JWT authentication, employer job management, public job search, candidate applications, and role-specific profiles.

## Tech Stack

- Java 17
- Spring Boot 3
- Spring Security 6 with JWT
- Spring Data JPA
- PostgreSQL
- Redis for token blacklist support
- Maven
- Docker Compose
- Swagger/OpenAPI 3

## Local Setup

```bash
cp .env.example .env
docker compose up --build
```

The API runs on `http://localhost:8080` by default.

Swagger UI will be available at `http://localhost:8080/swagger-ui.html` after the OpenAPI configuration and controllers are added.
