# Dev Template

A reusable development environment template for PHP projects.

## Goals

- Reproducible development environment
- Docker-based development
- VS Code Dev Containers
- Git + GitHub
- AI-friendly project structure
- Clean documentation
- Easy onboarding on a new machine

## Technologies

- Docker Desktop
- Dev Containers
- PHP
- SQLite (default)
- Git
- VS Code

## Philosophy

The application should not depend on Docker.

Docker exists only for development.

The production environment can be any standard PHP hosting.

## Project Structure

.devcontainer/
docs/
.vscode/

README.md
AGENTS.md
TASKS.md

## Workflow

1. Clone repository
2. Open in VS Code
3. Reopen in Dev Container
4. Start developing