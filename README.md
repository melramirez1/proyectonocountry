# 🚀 CMS Testimonials Platform - NoCountry Simulation

## 📋 Overview
This project is a specialized Content Management System (CMS) designed for managing, moderating, and publishing testimonials via an external API.

## 🛡️ DevOps & Infrastructure
Implemented with a **DevSecOps** mindset to ensure scalability, security, and developer productivity.

### Key Infrastructure Features:
- **Containerization:** Full development environment orchestrated with **Docker Compose**.
- **Database:** PostgreSQL 16 instance integrated into the local workflow.
- **CI/CD:** Automated pipelines via **GitHub Actions** (In progress).
- **Security:** Secrets management handled via environment variables and **Azure Key Vault**.

## 🛠️ Quick Start (Local Setup)

### 💻 Frontend Development
The frontend is built with **Next.js 15** and **Tailwind CSS**.

To run it locally:
1. `cd frontend`
2. `npm install`
3. `npm run dev`
4. Open [http://localhost:3000](http://localhost:3000)

### 🐳 Database & Infrastructure
The project uses **PostgreSQL 16** managed via Docker Compose.

**Prerequisites:**
- [Docker Desktop](https://www.docker.com/products/docker-desktop/) installed and running.

**Steps to start the DB:**

1. From the project root, run this command:
```bash
docker compose up -d
```

2. The database will be available at `localhost:5432`.
3. Connection details can be found in the `.env.example` file.

## 📂 Project Architecture
- `/.github/workflows`: CI/CD automation logic.
- `/infra`: Cloud infrastructure and Docker configuration.
- `/docs`: Architecture diagrams and Security audit reports.
- `/scripts`: Python/Bash automation scripts.
```