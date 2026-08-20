# Contributing Guide (Solo Workflow)

Even working solo, following a proper workflow strengthens the project for evaluation.

## Branching Strategy
- `main` — always deployable, protected
- `dev` — integration branch
- `feature/<name>` — one branch per feature/task

## Commit Convention
Use [Conventional Commits](https://www.conventionalcommits.org/):
- `feat: add air quality ingestion job`
- `fix: correct timezone bug in scheduler`
- `docs: update setup guide`
- `chore: update dependencies`

## Workflow
1. Create a feature branch from `dev`
2. Commit small, logical changes
3. Open a PR into `dev` (even solo — use GitHub UI, self-review, then merge)
4. Periodically merge `dev` -> `main` via PR when stable
5. Use GitHub Issues + Projects board to track tasks
