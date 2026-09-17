#  RescueAI: Disaster-Response & Risk-Analysis Platform

[![CI Pipeline](https://github.com/YOUR-USERNAME/rescue-ai/actions/workflows/ci.yml/badge.svg)](https://github.com/YOUR-USERNAME/rescue-ai/actions)
[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=flat&logo=python&logoColor=white)](https://www.python.org/)
[![Code Style](https://img.shields.io/badge/code%20style-ruff-000000.svg)](https://github.com/astral-sh/ruff)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

RescueAI is a 60-day AI-powered disaster-response platform that ingests and analyzes multi-modal data—incident logs, satellite/drone images, unstructured text reports, sensor telemetry, and emergency documents—to calculate real-time risk scores, detect structural damage, answer grounded emergency queries, and optimize resource routing.



# Architecture & Project Structure

```text
rescue-ai/
├── .github/workflows/    # CI/CD pipelines (Automated linting & testing)
├── src/
│   ├── ml/              # Model architectures, training scripts, & inference pipelines
│   ├── backend/         # FastAPI REST APIs, route optimization, & database services
│   └── shared/          # Pydantic schemas & shared utilities
├── frontend/            # React / Next.js dashboard & interactive mapping
├── database/            # Database schemas, PostGIS spatial queries, & migrations
├── deploy/              # Docker Compose & container orchestration
├── docs/                # Architecture diagrams & API documentation
└── tests/               # Unit and integration test suites
