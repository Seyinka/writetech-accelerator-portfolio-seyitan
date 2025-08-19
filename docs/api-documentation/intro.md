# API Documentation
# Documentation Tooling Project
This project involved auditing and restructuring documentation for [FastAPI](https://github.com/tiangolo/fastapi) using Docusaurus.

## Live Site
[View Site](#)

## What I Improved
- Reorganized information architecture with clear sections (Intro, Getting Started, Reference) and a consistent sidebar structure.
- Streamlined installation/setup with step-by-step commands, prerequisites, and verification via Swagger UI/ReDoc.
- Wrote focused API reference pages (e.g., `GET /users/{user_id}`, `POST /items/`) with parameters, example requests, and response schemas.

## Challenges
- Translating FastAPI’s auto-generated OpenAPI docs into concise, static pages without losing essential context.
- Avoiding duplication with upstream docs while keeping this mini-site coherent and beginner-friendly.

## What I Learnt
- Docs-as-Code workflows (version control, PR reviews, linters) make doc changes traceable and collaborative.
- Docusaurus conventions (frontmatter, sidebar categories, MDX features) help enforce consistency and improve navigation.

