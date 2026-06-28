# Personal Portfolio

A simple full-stack personal portfolio website built with Node.js, Express, MongoDB, and plain HTML/CSS/JavaScript.

## Features

- Frontend: responsive HTML, CSS, and client-side JavaScript
- Backend: Express.js REST API
- Database: MongoDB with Mongoose models
- Project showcase and add-project form
- API endpoints:
  - `GET /api/projects` (list)
  - `POST /api/projects` (create)
  - `GET /api/projects/:id` (details)

## Setup

1. Install dependencies:
   ```bash
   npm install
   ```
2. Start MongoDB locally (or configure `MONGODB_URI` in `.env`).
3. Run the app:
   ```bash
   npm run dev
   ```
4. Open `http://localhost:4000`

## Deploy

- Use a service like Vercel or Heroku.
- Make sure `MONGODB_URI` is set in production environment variables.
- Static frontend is served from `public/` and API routes are under `/api/projects`.
