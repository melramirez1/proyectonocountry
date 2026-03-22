# Use Node.js 20 Alpine for optimization and security
FROM node:20-alpine

# Enable Corepack to manage pnpm versions without global installation
RUN corepack enable && corepack prepare pnpm@latest --activate

WORKDIR /app

# Dependency Management: Copy manifests first to leverage Docker layer caching
COPY package.json pnpm-lock.yaml ./

# Install dependencies using pnpm
RUN pnpm install

# Build Stage: Copy the rest of the application source code
COPY . .

# Environment: Expose the default application port
EXPOSE 3000

# Runtime: Start the application in development mode
CMD ["pnpm", "dev"]