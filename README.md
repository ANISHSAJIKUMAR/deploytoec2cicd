# Deploy to EC2 CI/CD

This repository contains a simple deployment pipeline that builds and ships an application to an EC2 host.

## What it demonstrates

- GitHub Actions based deployment flow
- Remote execution against an EC2 instance
- Basic rollout steps that can be adapted for other applications

## Repository structure

- `README.md`: project overview and setup notes
- `.github/workflows/deploy.yml`: deployment workflow
- `a.txt` and `aa`: sample repo files used by the project

## Recommended improvements

- Replace placeholder shell commands with the real deployment script.
- Add validation before the EC2 step runs.
- Keep the README aligned with the workflow and secrets used by the pipeline.
