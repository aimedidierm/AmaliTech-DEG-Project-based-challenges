# DEG Project Challenges

This repository contains the DEG training project challenges across multiple tracks:

- Backend
- Data Engineering
- Fullstack
- QA
- **DevOps** ← solutions by [@aimedidierm](https://github.com/aimedidierm)

Each challenge is self-contained inside its folder and includes its own README with task details.

---

## DevOps Track — Solutions

All three DevOps challenges have been completed and are in the [`dev-ops/`](./dev-ops/) directory.

| # | Challenge | Description | Status |
|---|-----------|-------------|--------|
| 1 | [DeployReady](./dev-ops/DeployReady/) | Containerisation, CI/CD pipeline, cloud deployment | ✅ Done |
| 2 | [InfraBlueprint](./dev-ops/InfraBlueprint/) | Infrastructure as Code with Terraform | ✅ Done |
| 3 | [WatchTower](./dev-ops/WatchTower/) | Observability stack with Prometheus & Grafana | ✅ Done |

### Stack used

| Area | Tools |
|------|-------|
| Containerisation | Docker, Docker Compose |
| CI/CD | GitHub Actions |
| Container Registry | GitHub Container Registry (GHCR) |
| Cloud | DigitalOcean (Droplet) |
| IaC | Terraform (AWS provider) |
| Observability | Prometheus, Grafana |

### Development workflow

Solutions were first developed and tested in a standalone repository —
[`aimedidierm/amalitech-devops-challenges`](https://github.com/aimedidierm/amalitech-devops-challenges)
— where each challenge was built, verified locally with `docker compose up --build`,
and confirmed working (pipeline green, endpoints responding) before being migrated here
into the correct `dev-ops/` structure for submission.

---

## Applicant Guide

If you are applying, start by choosing the challenge folder that matches your track or assigned task. Then open the README inside that folder.

The challenge-specific README files include:

- Challenge description and requirements
- Expected deliverables
- Submission guidelines and deadlines (where applicable)
- Any setup instructions or constraints

## Where To Start

1. Open the relevant track folder (for example, `backend/`, `data-engineering/`, or `fullstack/`).
2. Enter the challenge project folder.
3. Read that project's `README.md` completely before starting work.
4. Follow the listed deliverables and submission instructions exactly.

If instructions differ between this root README and a challenge README, treat the challenge README as the source of truth.
