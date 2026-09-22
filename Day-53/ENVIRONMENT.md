# Day 53 — Environment

## Tools

| Tool | Purpose |
|---|---|
| Node.js LTS | JavaScript runtime |
| npm | Package management |
| Git | Version control |
| VS Code | Development |
| GitHub | Remote repository |

## Environment Variables

Use `.env.example` as the template. Keep real values only in local `.env`.

```env
NODE_ENV=development
PORT=5000
DATABASE_URL=
SUPABASE_URL=
SUPABASE_ANON_KEY=
CLAUDE_API_KEY=
CLIENT_URL=http://localhost:5173
```

Only variables actually required by the implemented project should be populated.

## Security
- Do not commit `.env`.
- Do not expose server-side AI keys in frontend code.
- Do not commit real credentials.
- Use environment variables for secrets.

## Verification
- [ ] Node.js installed
- [ ] npm available
- [ ] Git available
- [ ] VS Code configured
- [ ] Dependencies installed
- [ ] Environment configured
- [ ] Local server runs
- [ ] Database connected if required
- [ ] Auth scaffold verified if required
- [ ] Build succeeds
