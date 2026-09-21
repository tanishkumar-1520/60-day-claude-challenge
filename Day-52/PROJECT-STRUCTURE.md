# Day 52 — Project Structure

```text
project-root/
├── docs/
│   ├── ARCHITECTURE.md
│   ├── SCHEMA.md
│   ├── API.md
│   ├── UI-WIREFRAMES.md
│   ├── PROJECT-STRUCTURE.md
│   └── IMPLEMENTATION-BLUEPRINT.md
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── layouts/
│   │   ├── hooks/
│   │   ├── services/
│   │   └── utils/
│   └── public/
├── backend/
│   └── src/
│       ├── routes/
│       ├── controllers/
│       ├── services/
│       ├── middleware/
│       ├── models/
│       ├── validators/
│       └── utils/
├── database/
│   ├── migrations/
│   └── seeds/
├── tests/
├── .env.example
├── README.md
└── .gitignore
```

## Responsibilities
- `frontend/`: browser application and UI.
- `backend/`: REST API and business logic.
- `database/`: schema migrations and seed data.
- `docs/`: approved technical documentation.
- `tests/`: automated tests.
- `services/`: integrations such as AI and job providers.
- `middleware/`: authentication, validation, logging, and error handling.

The structure separates UI, API, persistence, integrations, and documentation so future implementation can proceed without restructuring the project.
