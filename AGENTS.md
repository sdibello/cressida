# AI project guidance

This repository is the starting point for a React frontend and a .NET 10 ASP.NET Core backend. Product requirements have not been defined. Do not invent features, data models, authentication, or deployment infrastructure.

## Intended layout

- `frontend/`: React and TypeScript application. Read `frontend/AGENTS.md` before changing files there.
- `backend/`: .NET 10 ASP.NET Core API. Read `backend/AGENTS.md` before changing files there.
- `docs/spec.md`: product goals, requirements, and acceptance criteria.
- `docs/decisions/`: dated records of significant technical decisions.
- `AGENTS.md`: shared guidance for the whole repository.

These directories currently contain guidance only. When scaffolding the applications, keep their source and tests within the corresponding directory. Prefer npm for the frontend and the .NET SDK for the backend. Record actual setup and run commands in a root `README.md` once runnable applications exist.

## Working agreements

- Inspect existing code, conventions, and tests before editing. Make the smallest coherent change that satisfies the request.
- Use `docs/spec.md` for product intent and `docs/decisions/` for architectural choices. Update the relevant document when an agreed requirement or decision changes. If guidance conflicts with the spec, surface the conflict instead of silently choosing one.
- Keep the frontend and backend independently buildable. Communicate through an explicit HTTP/JSON API contract; do not share runtime types or reach into the other app's internals.
- Put configuration in environment-specific settings. Never commit secrets, credentials, or local machine paths. Document required variables using safe examples.
- Add or update tests for behavior changes. Run the relevant available checks and report what passed, failed, or could not run. Do not claim checks that were not run.
- Preserve accessibility, error handling, and input validation when implementing user-facing flows.
- If a task requires an unspecified product decision, ask for that decision or state a narrow assumption. Keep speculative architecture out of the codebase.

## Stack baseline

- Frontend: React, TypeScript, and Vite when the app is scaffolded.
- Backend: .NET 10 and ASP.NET Core Web API when the API is scaffolded.
- Use each ecosystem's formatter and linter once configured. Keep dependency versions and commands in their package or project files rather than copying them into AI guidance.

More specific instructions in a nested `AGENTS.md` apply to that directory. Keep this file and the tool-specific entry files consistent when project conventions change.
