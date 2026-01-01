## Project Objective
This project provides a backend service that collects Bitcoin historical price data, identifies significant market events, and exposes contextual analysis through a REST API.

## Technology Stack
- **Python 3.12** — Core programming language used for its readability, ecosystem, and strong support for data processing.
- **FastAPI** — High-performance web framework for building REST APIs with automatic validation and documentation.
- **PostgreSQL** — Relational database used for reliable and consistent persistence of historical market data.
- **SQLAlchemy 2.0** — ORM for database interaction, enabling clean data access and maintainable models.
- **Alembic** — Database migration tool to manage schema changes in a controlled and versioned manner.
- **Docker & Docker Compose** — Containerization tools used to ensure consistent and reproducible development environments.
- **HTTPX** — HTTP client for consuming external cryptocurrency market APIs.
- **Pydantic** — Data validation and serialization library used across API schemas and services.
