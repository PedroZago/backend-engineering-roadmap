# Atlas — Enterprise SaaS Backend Platform

Enterprise-grade backend platform built with **NestJS**, focused on **scalability, clean architecture, multi-tenancy, cloud-native design, and high-performance APIs**.

This project simulates a real-world SaaS backend, following industry best practices adopted by high-growth startups and big tech companies.

---

## 🚀 Tech Stack

- Node.js + TypeScript
- NestJS
- PostgreSQL + Prisma ORM
- Redis (cache + queues)
- JWT Authentication + RBAC
- Docker + Docker Compose
- AWS-ready (S3, ECS, RDS)
- OpenTelemetry, Prometheus, Grafana

---

## 🏗 Architecture Overview

- Clean Architecture
- Modular Monolith
- Domain-Driven Design (DDD - pragmatic)
- Event-driven internal communication
- Multi-tenant SaaS design

Controller → Application → Domain → Infrastructure

---

## 🧠 Core Features

- Multi-tenant workspace architecture
- JWT authentication + refresh tokens
- Role-based access control (RBAC)
- Project & task management system
- Domain events & audit logging
- High-performance data access with Prisma
- Redis caching strategy
- Observability (logs, metrics, tracing)
- Enterprise-ready folder structure

---

## 📁 Project Structure

src/
├── core/
│ ├── domain/
│ ├── application/
│ └── infra/
│
├── modules/
│ ├── auth/
│ ├── users/
│ ├── workspaces/
│ ├── projects/
│ └── tasks/
│
└── shared/

---

## 🛠 Setup

```bash
git clone https://github.com/PedroZago/atlas-enterprise-api
cd atlas-enterprise-api
cp .env.example .env
docker-compose up -d
npm install
npm run dev
```
