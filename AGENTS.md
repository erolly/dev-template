# AI Development Rules

Before making changes, always read this file.

## General

- Prefer simple solutions.
- Avoid unnecessary dependencies.
- Explain important architectural decisions.
- Never change project structure without explaining why.

## Coding

- English variable names.
- English function names.
- PSR-12 coding style.
- Small functions.
- Self-explanatory code.

## UI

- User interface in Hungarian.
- Mobile-first approach.
- Accessibility should be considered.

## Development

- Docker is for development only.
- Production should work on standard PHP hosting.
- SQLite by default unless stated otherwise.

## Documentation

Whenever a major decision is made:

- update README if necessary
- update TASKS
- create an ADR when architecture changes