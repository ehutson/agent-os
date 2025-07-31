# Tech Stack

> Version: 1.0.0
> Last Updated: 2025-07-23

## Context

Global tech stack defaults for Agent OS projects, overridable in project-specific `.agent-os/product/tech-stack.md`.

- App Framework: Spring Boot 3.5+
- Language: Java 24
- Primary Database: PostgreSQL 16+
- Secondary Database: MongoDB latest stable
- ORM: Spring Data JPA
- JavaScript Framework: React latest stable
- Build Tool: Vite
- Import Strategy: Node.js modules
- Package Manager: npm
- Node Version: 22 LTS
- CSS Framework: TailwindCSS 4.0+
- UI Components: shadcn/ui latest
- UI Installation: npx shadcn@latest init
- Icons: Lucide React components
- Application Hosting: Internal using docker containers
- Database Hosting: Internal using docker containers
- CI/CD Platform: GitHub Actions
- CI/CD Trigger: Push to main/staging branches
- Tests: Run before deployment
- Production Environment: main branch
