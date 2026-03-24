# Family Council AI

A private family coordination app that lets members submit issues with evidence (text, audio, video), uses AI to summarize them, and runs a weekly structured "Family Council" meeting process.

**Portfolio focus:** FastAPI · PostgreSQL · Groq LLM · MinIO · Docker · AWS SES · React

---

## Quick Start (Docker)

> Prerequisites: [Docker Desktop](https://www.docker.com/products/docker-desktop/) installed and running.

```bash
# Clone the repo
git clone https://github.com/n5hossai/family-council-ai.git
cd family-council-ai

# Start all services
docker compose up --build
```

API will be available at `http://localhost:8000`.

---

## Project Structure

```
family-council-ai/
├── backend/          # FastAPI application
├── frontend/         # React web app
├── docs/
│   ├── project_context.md   # Master spec (immutable)
│   └── backend.md           # Backend progress log
├── infra/            # Docker Compose, future K8s manifests
├── docker-compose.yml
└── README.md
```

---

## Docs

- [Master Spec](docs/project_context.md) — what we're building and why
- [Backend Progress](docs/backend.md) — chronological development log
