# Project-CICD – Monorepo CI/CD pour Application Étudiante

Ce dépôt est le **projet principal** qui gère l'intégration continue et le déploiement continu de deux sous-modules :
- `studentmanagement` : Backend Node.js
- `projet-tp01` : Frontend React

## Structure du dépôt

```bash
project-cicd/
├── .github/workflows/
│   ├── ci-cd.yml        # Build et push Docker des sous-modules
│   ├── sync-submodules.yml       # Synchronise les sous-modules
│
├── docker-compose.yml           # Docker multi-conteneurs 
├── studentmanagement/           # Sous-module backend (Node.js)
├── projet-tp01_1_8_51_52_54/                 # Sous-module frontend (React)
