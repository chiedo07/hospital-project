# Hospital Project

A multi-service hospital management project that combines backend APIs, a frontend application, containerised development, and CI/CD automation.

## Overview
This repository contains a hospital platform built as a collection of services and supporting infrastructure files. The project includes:
- frontend code for the hospital user interface
- backend APIs for appointments and patients
- Docker Compose for local orchestration
- Azure Pipelines configuration for automated delivery
- Kubernetes or deployment manifests for application rollout

## Repository Structure
- `appointment-api/` – appointment service
- `patient-api/` – patient service
- `hospital-frontend/` – frontend application
- `docker-compose.yaml` – local multi-service orchestration
- `azure-pipelines.yml` – CI/CD pipeline definition
- `hospital-api.yml` – deployment or environment configuration

## Features
- Multi-service architecture
- Container-based local development
- CI/CD integration
- Environment configuration for deployment workflows

## Tech Stack
- TypeScript
- Python
- HTML/CSS/JavaScript
- Docker / Docker Compose
- Azure DevOps Pipelines

## Getting Started
### Prerequisites
- Docker and Docker Compose
- Node.js and npm
- Python
- Azure DevOps access if using the pipeline

### Run locally
```bash
git clone https://github.com/chiedo07/hospital-project.git
cd hospital-project
docker compose up --build
```

### Alternative local setup
Start the frontend and API services individually from their respective folders if you prefer not to use Docker Compose.

## CI/CD
The repository includes an Azure Pipelines configuration to support automated builds and deployments.

## What I Learned
This project helped me strengthen my skills in multi-service application design, containerisation, CI/CD, and service orchestration.

## Future Improvements
- Add architecture diagrams
- Add environment variable examples
- Add API documentation
- Add test instructions for each service

## Author
Louis Chiedozie Nlemadim
