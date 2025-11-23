# TODO

- Add automated tests (FastAPI TestClient + httpx.AsyncClient) for `/query` happy/error paths, planner fallback, and debug payload shape.
- Replace simulated agent outputs with real HTTP/CLI integrations; update `load_registry()` endpoints/commands and tune timeouts per agent.
- Add `.env.example` with required vars (e.g., `OPENAI_API_KEY`) and document local setup.
- Introduce lint/format tooling (black/ruff) and wire into a simple `make lint` target.
- Containerize (Dockerfile + optional docker-compose) and document run commands.
- Add CI (GitHub Actions) to run tests and lint on push/PR.
- Implement health checks for agents and surface registry health status on the UI.
- Improve logging/observability (structured logs, timing per step) and add minimal metrics hooks.
- Expand UI: loading states per agent call, collapsible intermediate results, and copy-to-clipboard for answers.
- Write onboarding docs/README covering architecture, registry edits, and deployment steps.
