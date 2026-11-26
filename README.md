# Disaster Response Coordination Platform

An incremental MERN-stack course project for coordinating residents, volunteers,
and response managers during emergencies.

## Milestone 1: app foundation

This first step includes a responsive coordination dashboard shell and an Express
API health endpoint. Dashboard counts and activity are illustrative demo data;
the app is not connected to emergency services and must not be used for real
emergency reporting.

## Run locally

Requirements: Node.js 20.19+ and npm.

From this folder, install dependencies and start both development servers:

```powershell
npm install
npm run dev
```

Open the frontend URL printed by Vite (usually `http://localhost:5173`). The
backend runs on `http://localhost:3000`; its health endpoint is
`http://localhost:3000/api/health`.

Useful checks:

```powershell
npm run lint
npm run build
```

## Project structure

```text
backend/
  src/
    controllers/
    routes/
    app.js
    server.js
frontend/
  src/
```

Next milestones can add validated incident reporting, then authentication and
role-based access, volunteer task management, resource tracking, and connected
dashboard/search data.
