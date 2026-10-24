# Frontend guidance

Follow the repository root `AGENTS.md` as well as this file. This directory is reserved for a React + TypeScript frontend; no application has been scaffolded yet.

- Scaffold with Vite and npm when implementation is requested. Use TypeScript strict mode.
- Use function components and hooks. Keep components focused; place shared behavior in hooks or plain modules when it is reused.
- Keep API calls behind a small client layer. Define request and response types from the actual backend contract; do not guess response shapes.
- Handle loading, empty, error, and success states for data-driven views. Give controls accessible names, use semantic HTML, and support keyboard use.
- Keep secrets and server-only logic out of browser code. Use environment variables only for values safe to expose to users.
- Keep styling consistent with the project's chosen approach. Do not add a UI framework or state library without a concrete need.
- Add meaningful tests for behavior with the test tools configured in this app. Run the available typecheck, lint, test, and build commands before reporting completion.
