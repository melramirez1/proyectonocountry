# 🚀 CMS Testimonials Platform - NoCountry Simulation

## 📋 Overview
This project is a specialized Content Management System (CMS) designed for managing, moderating, and publishing testimonials via an external API.

## 🛡️ DevOps & Infrastructure
- **Containerization:** Development environment managed with Docker Compose.
- **Database:** PostgreSQL.
- **Standards:** ISO 13485-inspired quality and documentation mindset.

## 🛠️ Project Structure
- `/infra`: Cloud and Docker configuration.
- `/docs`: Technical documentation and Security reports.
- `/scripts`: Python automation scripts.
```
### 💻 Frontend Development
The frontend is built with **Next.js 15** and **Tailwind CSS**.

To run it locally:
1. `cd frontend`
2. `npm install`
3. `npm run dev`
4. Open [http://localhost:3000](http://localhost:3000)

### 🐳 Database & Infrastructure (Local)
The project uses **PostgreSQL 16** managed via Docker Compose to ensure all team members work with the same environment.

**Prerequisites:**
- [Docker Desktop](https://www.docker.com/products/docker-desktop/) installed and running.

**Steps to start the DB:**
1. From the project root, run:
   ```bash
   docker compose up -d
   ```
2. The database will be available at `localhost:5432`.
3. Connection details can be found in the `.env.example` file.