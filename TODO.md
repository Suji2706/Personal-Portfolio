# TODO - Inthula Database (MongoDB + optional SQL)

## Step 1: Fix runtime note
- Document that port 4000 must be free (EADDRINUSE) when running `npm run dev`.

## Step 2: Decide scope
- Keep MongoDB as-is since user confirmed “mongoDb ok”.
- Add optional SQL (MySQL/PostgreSQL) support only if asked later.

## Step 3: Improve project for submission
- Update README to clarify MongoDB setup and environment variables.
- Add `MONGODB_URI` usage docs.
- (Optional) Add basic API docs in README.

## Step 4: Verify
- Run `npm run dev` after ensuring port 4000 is free.
- Validate GET `/api/health` and GET/POST `/api/projects`.

