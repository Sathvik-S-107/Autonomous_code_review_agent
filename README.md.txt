# Autonomous Code Review Agent

An autonomous code review agent that analyzes GitHub pull requests using AI.

## Features
- FastAPI REST API
- Background analysis using Celery
- Redis backend for results
- AI agent using OpenAI/Ollama
- Docker setup
- Tests with pytest

## Run locally
docker-compose up --build

## Endpoints
POST /api/analyze-pr
GET /api/status/{task_id}
GET /api/results/{task_id}

