## **Backend Python Developer** building scalable APIs and robust backend systems.

---

## 🛠️ Tech Stack

**Backend**
- Python, SQL, FastAPI, SQLAlchemy, Alembic

**Database**
- PostgreSQL, asyncpg

**Authentication**
- OAuth2, JWT (Access + Refresh Token Rotation), RBAC

**Caching & Performance**
- Redis (Upstash), Cursor-based Pagination, Async I/O, asyncio.gather

**Infrastructure**
- Docker, Docker Compose, Fly.io

**Testing**
- Pytest, HTTPX (Async Integration Tests)

**Other**
- Pydantic v2, asyncio, Git, REST API Design, Logging

---

## 💡 What I Build

✅ RESTful APIs with clean layered architecture (Repository + Service Pattern)

✅ Secure authentication systems with dual-token JWT and refresh token rotation

✅ Role-based access control (RBAC) with granular permissions

✅ High-performance APIs with Redis caching and cursor-based pagination

✅ Real-time messaging and notification systems

✅ Concurrent data fetching using asyncio.gather for maximum API performance

✅ Dashboard APIs that aggregate multiple data sources in a single request

✅ Database schemas with proper relationships, soft deletes, and migrations

✅ Production-ready containerized applications with Docker

✅ Integration tested backends with Pytest and HTTPX

---

## 🚀 Featured Projects

### [CoreHub API](https://github.com/Menarddddd/corehub)

A production-ready **internal company portal API** — the backend engine for a
platform where companies manage employees, departments, tasks, announcements,
and internal communications all in one place.

Think of it as a lightweight internal **Slack + Asana + HR Portal**, all
powered by one clean backend API.

- 📖 **Swagger UI:** [Live API Docs](https://corehub-amber-acorn-510.fly.dev/docs)
- 🔐 **Dual-token JWT auth** with refresh token rotation and Redis blacklisting
- 👥 **User & Department Management** with role-based access (Admin, Manager, Member)
- ✅ **Task System** with assignment rules, priority levels, status tracking,
  and due date enforcement
- 💬 **Messaging System** — DMs and group conversations with real-time
  notifications, unread counts, and message history (like Messenger)
- 🔔 **Notification System** — auto-triggered on messages and task assignments
- 📢 **Announcements** — company-wide posts with priority levels and expiration dates
- 📊 **Dashboard API** — aggregates user profile, task summary, unread notifications,
  unread messages, and recent announcements in a single concurrent API call using `asyncio.gather`
- ⚡ **Redis Caching** on all read-heavy endpoints with automatic cache invalidation
- 📄 **Cursor-based Pagination** on all list endpoints (scalable, Facebook/Twitter style)
- 🏗️ **Clean Architecture** — Repository Pattern + Service Layer + Dependency Injection
- 🗄️ PostgreSQL (Neon Serverless) + SQLAlchemy Async ORM + Alembic migrations
- 🐳 **Dockerized** with Docker Compose and PostgreSQL health checks
- ⚙️ CI/CD pipeline with GitHub Actions
- ☁️ Deployed on Fly.io

**Tech:** FastAPI · PostgreSQL · SQLAlchemy (Async) · Redis · JWT · Docker · Alembic · GitHub Actions

---

### [Budget Tracker API](https://github.com/Menarddddd/budget_tracker)

A full-stack personal budget management system with a production-grade
REST API and React frontend.

- 🌐 **Live Demo:** [Budget Tracker](https://budget-tracker-liart-nu.vercel.app)
- 📖 **Swagger UI:** [Live API Docs](https://budget-tracker-api.fly.dev/docs)
- 🔐 OAuth2 + JWT authentication with email verification
  and refresh token rotation
- 💰 Automatic budget cycle management with PostgreSQL
- 🗄️ PostgreSQL (Neon Serverless) + SQLAlchemy ORM + Alembic migrations
- 📧 Async email processing with FastAPI Background Tasks
- ⚙️ CI/CD pipeline with GitHub Actions
- 🐳 Docker + Docker Compose
- ☁️ Backend deployed on Fly.io | Frontend on Vercel

**Tech:** FastAPI · PostgreSQL · SQLAlchemy · Alembic · React · Docker · GitHub Actions

---

## 📍 Status

🇵🇭 Philippines-based | 🌏 Open to remote work
🚀 Actively looking for backend developer opportunities

---

## 📫 Let's Connect

💼 [linkedin.com/in/menard-francisco-b21486353](https://www.linkedin.com/in/menard-francisco-b21486353/)
📧 menardddddd@gmail.com
