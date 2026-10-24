# Backend guidance

Follow the repository root `AGENTS.md` as well as this file. This directory is reserved for a .NET 10 ASP.NET Core Web API; no application has been scaffolded yet.

- Target `net10.0`. Enable nullable reference types and implicit usings in new C# projects.
- Keep HTTP endpoints thin. Put business rules in focused services or feature modules, and keep persistence behind clear interfaces only when persistence exists.
- Define explicit request and response contracts. Validate untrusted input at the API boundary and return consistent HTTP status codes and problem details for errors.
- Use dependency injection and asynchronous I/O. Pass `CancellationToken` through operations that support cancellation.
- Keep secrets out of source control. Use configuration and environment variables; document required settings with safe example values.
- Restrict CORS to configured frontend origins when cross-origin access is needed. Add authentication and authorization only after their requirements are defined.
- Add tests for business behavior and API contracts as appropriate. Run the available restore, build, and test commands before reporting completion.
