# azure-function-cicd

# CodeGen Pipeline (Local)

This repository demonstrates a basic CI/CD workflow for code execution using GitHub Actions and Docker.

## Structure
- `.github/workflows/ci-cd.yml`: GitHub Actions pipeline.
- `Dockerfile.exec-image`: Docker build instructions.
- `exec/run.js`: Sample code executed in the container.

## How to Use
1. Push to `main` branch.
2. GitHub Actions will build and run the container.
