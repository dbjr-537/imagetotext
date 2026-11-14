# Security

## Environment configuration

Do not commit `.env` files. Copy `backend/.env.example` to `backend/.env` and set
deployment-specific values locally.

Historical note: `backend/.env` was previously tracked in this public fork. It
contained only `FRONTEND_ORIGIN`, not an API key or credential. The file was
removed from the current tree and added to `.gitignore`; older commits still
contain the historical value.

## Reporting

Report suspected vulnerabilities privately to the repository owner rather than
opening a public issue.
