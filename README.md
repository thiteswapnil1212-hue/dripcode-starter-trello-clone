# Trello Clone — DripCode Starter

Build a Trello-style kanban board with React and Strapi. This is the
starter code for the [DripCode Build Projects](https://skill-grid-weld.vercel.app/projects/trello-clone) Trello Clone project.

## What you will build

- Boards, lists and cards (Strapi backend)
- Drag-and-drop cards between lists, saved through the API

## Run it

Frontend:

```bash
cd frontend
npm install
npm run dev
```

Backend (Strapi — separate setup, see the tutorial):

```bash
npx create-strapi-app@latest backend
```

Then create Board, List and Card collections in the Strapi admin, with
relations: Board has many Lists, List has many Cards. Set the Strapi URL
in `frontend/src/api.js`.

## Files

- `frontend/` — Vite + React app (board UI is a stub — `TODO` marks the spots)
- `frontend/src/api.js` — Strapi base URL + fetch helpers

## Steps

Follow the steps on the [project page](https://skill-grid-weld.vercel.app/projects/trello-clone). Tutorial: Strapi blog.

No solution code is included — you write it.
