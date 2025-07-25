# Tech Stack

> Version: 1.0.0
> Last Updated: 2025-07-23

## Context

This file is part of the Agent OS standards system. These global tech stack defaults are referenced by all product codebases when initializing new projects. Individual projects may override these choices in their `.agent-os/product/tech-stack.md` file.

## Core Technologies

### Application Framework

- **Framework:** Spring Boot
- **Version:** 3.5+
- **Language:** Java 24
- **Build System:** Gradle-Kotlin

### Database

- **Primary:** PostgreSQL
- **Version:** 16+
- **ORM:** Spring Data JPA
- **Migrations:** Flyway
- **APIs:** GraphQL (DGS with DGS Codegen)

## Frontend Stack

### Typescript Framework

- **Framework:** React
- **Version:** Latest stable
- **Build Tool:** Vite

### Import Strategy

- **Strategy:** Node.js modules
- **Package Manager:** npm
- **Node Version:** 22 LTS

### CSS Framework

- **Framework:** TailwindCSS
- **Version:** 4.0+
- **PostCSS:** Yes

### UI Components

- **Library:** shadcn/ui
- **Version:** Latest
- **Installation:** npx shadcn@latest init

### API

- **Library:** apollo graphql client
- **Version:** latest

## Assets & Media

### Icons

- **Library:** Lucide
- **Implementation:** React components

## Infrastructure

### Application Hosting

- **Platform:** Internal
- **Service:** Docker

### Database Hosting

- **Provider:** Internal
- **Service:** PostgreSQL running in a docker container

## Deployment

### CI/CD Pipeline

- **Platform:** GitHub Actions
- **Trigger:** Push to main/staging branches
- **Tests:** Run before deployment

### Environments

- **Production:** main branch
- **Review Apps:** PR-based (optional)
