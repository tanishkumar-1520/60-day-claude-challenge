# Day 53 — Project Structure

```text
project-root/
├── docs/
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
├── .gitignore
└── README.md
```

## Responsibilities
- `frontend/`: browser UI and client-side logic.
- `backend/`: REST API and business logic.
- `database/`: migrations and seed data.
- `docs/`: technical documentation.
- `tests/`: automated tests.
- `services/`: external integrations.
- `middleware/`: authentication, validation, logging, and errors.

Day 3 should add only the foundation required by the approved Day 2 design.
