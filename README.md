# 📈 My Next.js 16 App (Stock Market Monitoring)

A modern app to help you keep up with the current trends in the stock market. Built with Next.js 16, fully Dockerized for development and production, with hot reload enabled via Docker's new Compose Watch feature. This setup enables a hands-off developer workflow: edit code locally, see changes instantly in the container — no rebuilds required.

[Use Compose Watch Documentation](https://docs.docker.com/compose/how-tos/file-watch)

## 🌟 Features

- Real-time stock market trend visualization
- Next.js 16 with server-side rendering (SSR) and API routes
- Dockerized dev/prod workflows
- Hot reload with **Docker Compose Watch**
- Optimized incremental builds and container development
- Environment-ready: works locally, in Docker, or deployed

## 🔨 Tech Stack

| Layer          | Technology                             |
|----------------|----------------------------------------|
| Frontend       | Next.js 16, React 18, Tailwind CSS, Shadcn     |
| Backend        | Node.js 20, Next.js API routes         |
| Containerization | Docker         |
| Security         | Better Auth (TypeScript authentication framework) |
| Automation       | Inngest (serverless workflows)         |

## 🚀 Quick Start

### Prerequisites

- [Node.js 20+](https://nodejs.org)
- [Docker](https://www.docker.com/get-started)

### 🧑‍💻 Get Started Developing

```bash
git clone https://github.com/cheyroseflammer/stonks-app.git
cd stonks-app
docker compose up --watch
```

### ⚡ Production Build (Optional)

If you want to run a production-ready container instead of the development setup:

```bash
git clone https://github.com/cheyroseflammer/stonks-app.git
cd stonks-app
docker build -t stonks-app:prod .
docker run -p 3000:3000 stonks-app:prod
```
