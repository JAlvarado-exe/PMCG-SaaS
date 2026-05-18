# PMCG SaaS Platform

> **P**roject Management & **C**onsulting **G**roup — Cloud-based SaaS infrastructure.

---

## Overview

PMCG SaaS is a cloud-native platform designed to [brief description of the product's core value proposition].

---

## Tech Stack

| Layer        | Technology          |
|--------------|---------------------|
| Frontend     | TBD                 |
| Backend      | TBD                 |
| Database     | TBD                 |
| Auth         | TBD                 |
| Infra / CI   | TBD                 |
| Hosting      | TBD                 |

---

## Repository Structure

```
PMCG-SaaS/
├── apps/               # Applications (frontend, backend, workers)
├── packages/           # Shared libraries and utilities
├── infra/              # Infrastructure-as-code (IaC)
├── docs/               # Architecture decisions and documentation
├── scripts/            # Dev/CI helper scripts
├── .github/            # GitHub Actions workflows
├── .gitignore
└── README.md
```

---

## Getting Started

### Prerequisites

- Node.js >= 20.x
- Git >= 2.40
- [Any other prerequisites]

### Local Setup

```bash
# 1. Clone the repository
git clone <repository-url>
cd PMCG-SaaS

# 2. Install dependencies
npm install

# 3. Copy environment variables
cp .env.example .env
# Fill in the required values in .env

# 4. Start development server
npm run dev
```

---

## Environment Variables

| Variable         | Description                  | Required |
|------------------|------------------------------|----------|
| `DATABASE_URL`   | Connection string for the DB | Yes      |
| `JWT_SECRET`     | Secret key for JWT tokens    | Yes      |
| `PORT`           | Server listening port        | No       |

> Never commit `.env` files. See `.gitignore`.

---

## Scripts

| Command           | Description                        |
|-------------------|------------------------------------|
| `npm run dev`     | Start development server           |
| `npm run build`   | Build for production               |
| `npm run test`    | Run test suite                     |
| `npm run lint`    | Lint source files                  |
| `npm run migrate` | Run database migrations            |

---

## Contributing

1. Branch off `main` using the convention `feat/`, `fix/`, `chore/` prefixes.
2. Open a Pull Request — all PRs require at least one review.
3. Keep commits atomic and descriptive.

---

## License

[License TBD] — © 2026 PMCG. All rights reserved.
