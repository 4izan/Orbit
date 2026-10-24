# Orbit — focus workspace concept

Orbit is a standalone Next.js focus timer and task workspace. Tasks sit around a dimensional orbital scene; selecting a task brings it into the focus timer. The interface adapts to mobile and honors reduced-motion preferences.

## Run locally

Run `npm install`, then `npm run dev`, and open `http://localhost:3000`.

## Editing the concept

- Change the starter tasks in `data/tasks.ts`.
- Edit the orbital scene in `components/OrbitStage.tsx`.
- Adjust the workspace and visual styling in `app/page.tsx` and `app/globals.css`.
- User tasks are stored in browser local storage under `orbit-focus-tasks-v1`.

The profile name and sample task names are illustrative. Task data remains on the current browser; there is no account sync.
