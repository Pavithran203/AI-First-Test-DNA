# AI-First Test DNA

A project workspace manager built with a FastAPI backend, MongoDB persistence, and a React/Vite interface. It organizes projects, subprojects, categories, tags, and environment URLs.

## Example project

Create a workspace called **Retail Web Portal**, tag it e-commerce, then add a **Checkout** subproject. Attach Dev, Staging, and Production URLs to the subproject so the team can find the environment for each test cycle. This is an illustrative workflow; use the interface and API behavior in the source as the implementation guide.

## Included
- Backend/: FastAPI entry point, database connector, project routes and schemas, Python dependencies, and backend setup notes.
- Frontend/: React application source, Vite and TypeScript configuration, npm manifests, and frontend setup notes.
- Full source tree: project-source.zip at the repository root. Download and extract it before setup.

Generated environments, caches, and the standalone HTML demo are excluded.

## Run locally

1. Extract project-source.zip.
2. Start MongoDB locally, or set MONGODB_URI and DB_NAME in your local environment.
3. In Backend/, run pip install -r requirements.txt and uvicorn main:app --reload.
4. In Frontend/, run npm install and npm run dev.

Do not commit local credentials or environment files.
