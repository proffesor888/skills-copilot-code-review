---
applyTo: "backend/**/*,*.py"
---

## Backend Guidelines

- All API endpoints must be defined in the `routers` folder.
- Load example database content from the `database.py` file.
- Sanitize error messages before sending to the frontend. Log detailed errors only on the server. Send appropriate HTTP status codes and generic error messages to the frontend to handle failures gracefully.
- Ensure all APIs are explained in the documentation.
- Verify changes in the backend are reflected in the frontend (`src/static/**`). If possible breaking changes are found, mention them to the developer.