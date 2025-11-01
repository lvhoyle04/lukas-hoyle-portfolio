# API Documentation Template

Use this template when documenting endpoints or API integrations.

## Endpoint
- Path: /api/v1/resource
- Method: GET

## Purpose
Short description of what this endpoint provides.

## Authentication
- Type: Bearer token (JWT) or OAuth2
- Required headers: Authorization: Bearer <token>

## Query / Path Parameters
- id (path, required) — unique resource identifier
- limit (query, optional) — number of items to return (default: 25)

## Request example
GET /api/v1/resource/123?limit=10 HTTP/1.1
Host: api.example.com
Authorization: Bearer <token>

## Response example
{
  "id": "123",
  "name": "Example resource",
  "created_at": "2025-01-01T12:00:00Z"
}

## Errors
- 400 Bad Request — invalid parameters
- 401 Unauthorized — missing or invalid token
- 404 Not Found — resource does not exist
- 429 Too Many Requests — rate limited

## Notes
- Pagination: Describe cursor or offset strategy if applicable.
- Rate limits: Describe per-minute or per-hour limits and recommended retry/backoff behavior.