# AI-First Test DNA

> Full source tree is included in `project-source.zip` at the repository root. Unpack it to restore the directories and files summarized below.

AI-assisted project and subproject management application with a FastAPI backend, MongoDB persistence, and a React/Vite frontend.

## Included files

- `Backend/`: FastAPI entry point, database connector, project routes and schemas, Python dependencies, and backend setup notes.
- `Frontend/`: React application source, Vite and TypeScript configuration, npm manifests, and frontend setup notes.

Generated environments, caches, and the standalone HTML demo are not included.

## Run locally

1. Start MongoDB locally, or set `MONGODB_URI` and `DB_NAME` in your local environment.
2. In `Backend/`, install dependencies with `pip install -r requirements.txt`, then start the API with `uvicorn main:app --reload`.
3. In `Frontend/`, run `npm install` and `npm run dev`.
