# API Notes

- Auth: JWT, expiry 24h
- Rate limit: 100 req/min per token
- Error format: `{ error: { code, message } }`
- Webhook retries: 3 attempts, exponential backoff

## Endpoints to revisit

- `POST /v2/export` – add date range filter
- `GET /v1/health` – include DB status