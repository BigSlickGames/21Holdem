
# My Game Project (Monorepo)

This repo contains 4 modules:
- `admin-frontend` (React UI for admin)
- `admin-backend` (Node/Express API for admin)
- `game-frontend` (React UI for players)
- `game-backend` (Node/Express API for game logic)

## Local Dev (per app)
```bash
cd <folder>               # e.g., game-frontend
npm install
# Frontends:
npm run dev               # Vite dev server
# Backends:
npm start                 # Node server on PORT (default 4000)
```

## Bolt Instructions
- To run the **player UI**: set Bolt root to `game-frontend`, and command `npm run dev` (or `npm run preview` after build).
- To run the **game API**: set Bolt root to `game-backend`, command `npm start`.
- Do the same for `admin-frontend` and `admin-backend` when needed.

## Ports
- Backends default to `PORT` env var or 4000.
- Frontends default to Vite dev server port (5173). Configure proxy to your API as needed.

## Notes
- This is a simple, clean starting template. Add routes, pages, auth, DB, etc. as you go.
