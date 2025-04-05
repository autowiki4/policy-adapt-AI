# App

This folder contains the core backend logic for the PolicyAdapt AI platform.

## Structure

- `main.py` – Entry point for the FastAPI application.
- `api/` – Route definitions (e.g., endpoints for user input, recommendation, health check).
- `services/` – Core logic like RAG pipelines, model loading, embedding, user profiling, etc.
- `config/` – Environment-based settings, keys, and other config logic.
- `__init__.py` – Allows this folder to be treated as a Python module.

## Goals

- Serve a live API (e.g., via FastAPI or another framework).
- Integrate AI/ML components with user profile and policy data.
- Ready for deployment and easy integration with frontend and external services.
