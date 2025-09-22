# Infrastructure Automation

This folder is intended for scripts/configurations that automate provisioning of backend resources.

## What to include

- Scripts, IaC configs (e.g., Terraform, shell, etc.) that provision:
  - Compute runtime (for the backend API)
  - Managed database (e.g., PostgreSQL)
  - Object storage (for assets/receipts)
  - Authentication provider (real or stubbed)
- Scripts/configs should demonstrate scalability, security, and extensibility, even if not fully production-ready.
- Document any commands, prerequisites, and teardown/reset steps as appropriate.

> **Note:**  
> Infrastructure automation is required, but you may use any approach and you may reorganize this directory as needed.
