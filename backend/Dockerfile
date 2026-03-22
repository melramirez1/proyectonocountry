# Aligned with project-wide Node.js standards
FROM node:20-alpine

# Prepare pnpm for the backend engineering team
RUN corepack enable && corepack prepare pnpm@latest --activate

WORKDIR /app

# Infrastructure notice: Keeps the service running for network testing
CMD ["echo", "DevOps Notification: Backend environment ready. Waiting for application code."]