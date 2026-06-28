# Artisan Sahayak

This repository is now organized into:

- backend: Express API server and database logic
- frontend: Vite + React UI

## Run locally

1. Install dependencies from the workspace root:
   npm install
2. Start the backend:
   npm run dev:backend
3. Start the frontend in a second terminal:
   npm run dev:frontend

The frontend proxies `/api/*` requests to `http://localhost:3001`.
