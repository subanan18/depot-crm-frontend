# Depot CRM Frontend

React/Vite frontend for the Depot storage and asset-tracking CRM.

## What it does

- Dashboard for storage operations
- Company and project views
- Item registration and tracking
- Retrieval workflow support
- Status and location visibility
- Connects to the FastAPI backend through `VITE_API_URL`

## Local setup

```bash
npm install
npm run dev
```

Create a local environment file:

```env
VITE_API_URL=http://localhost:8000
```

For production, set `VITE_API_URL` to the deployed API URL before building.

## Backend

The API lives in:

https://github.com/subanan18/storage-crm-backend

## Development priorities

- Improve loading and error states
- Add authentication/role-aware screens
- Add QR/barcode scanning flow
- Add item images and richer search
- Expand automated frontend tests
- Improve accessibility and keyboard navigation

## Engineering focus

This project demonstrates React UI development, API integration, environment-based configuration, responsive layouts, and real-world CRUD workflow design.
