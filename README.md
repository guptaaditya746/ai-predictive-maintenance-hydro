# AI Predictive Maintenance Hydro

A full stack predictive-maintenance prototype combining Python model-training scripts, Node-RED flows, a Next.js dashboard, and Docker services for an IoT-style data pipeline.

## Run the dashboard

```bash
cd frontend
npm ci
npm run dev
```

## Run the service stack

From the repository root, review `docker-compose.yml` and the configuration under `config/`, then start the services with:

```bash
docker compose up -d
```

The Python model scripts use the requirements files under `requirements/`. The local training CSV is not included; provide your own permitted dataset before training. `PROJECT_GUIDE.md` contains the longer original setup notes.
