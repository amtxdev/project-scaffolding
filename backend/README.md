# Backend

This folder is intended for your backend/API server.

## What to include

- Project manifest (e.g., `package.json`, `go.mod`, etc.)
- API endpoints (stubs or minimal implementations) for:
  - Authentication
  - Event listing
  - Ticket purchase
  - User management (CRUD)
- Middleware for authentication/authorization, with example role checks (`user` vs `admin`).  
  Stubbing `req.user` or equivalent is fine.
- Clear separation between routing, business logic, and data access (even if only as placeholders/stubs).
- Sample environment configuration: `.env.example`

## Replicability & Provisioning

- Ensure the backend and any dependencies (e.g., database) can be run locally by a new developer, with no manual global setup required.
- Use any orchestration or packaging approach you prefer (e.g., Dockerfile, Compose, etc.).
- Infrastructure automation scripts/configs (see `../infra/`) should provision all core backend resources.

> **Note:**  
> You may restructure, replace, or remove anything in this directory.
