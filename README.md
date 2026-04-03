# DevOps Production-Ready Backend Project

## Overview
A production-style backend system built using FastAPI and PostgreSQL, fully containerized and orchestrated using Docker Compose with CI/CD automation.

## Tech Stack
- FastAPI (Backend)
- PostgreSQL (Database)
- Docker (Containerization)
- Docker Compose (Orchestration)
- GitHub Actions (CI/CD)

## Key Features
- Multi-container architecture (App + DB)
- Docker networking for service communication
- Environment variable management using `.env`
- Health check-based service readiness
- Automated CI pipeline with GitHub Actions
- Production-like setup and debugging

## How to Run

```bash
docker-compose up --build