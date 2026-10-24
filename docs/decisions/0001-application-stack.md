# 0001: Application stack

Date: 2026-10-22
Status: Accepted

## Context

The project is starting with a specified frontend and backend stack. Product requirements and deployment needs have not yet been defined.

## Decision

Use React for the frontend and .NET 10 ASP.NET Core for the backend.

## Consequences

The frontend and backend can be developed and built as separate applications. Their interactions need an explicit API contract. Choices such as persistence, authentication, hosting, and product features remain open until requirements are known.
