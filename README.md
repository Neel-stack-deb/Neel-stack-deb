# Neel (Neel-stack-deb)
Full‑stack Developer · Real‑time Systems · Open‑Source Enthusiast


Hi, I’m Neel. I build low‑latency real‑time backends and delightful frontends that make collaboration feel instant. I focus on performance, great developer experience, and shipping production‑ready systems.

---

##  Current Focus
- Real‑time systems: presence, live events, and collaborative sync
- Full‑stack product features end‑to‑end
- Open-source tooling and developer ergonomics

---

##  Core Tech
- Languages: JavaScript, TypeScript, Go, Java, C/C++
- Frontend: React, Next.js, Vite
- Backend: Node.js, Express, WebSockets, WebRTC
- Databases & Cache: PostgreSQL, Redis, Mongo DB, pinecone
- Infra & CI: Docker, GitHub Actions, AWS
- Testing & Quality: Jest, Playwright, ESLint, Prettier

---

##  Featured Projects

##  Mini CRM Backend — Production-Grade REST API

A **scalable CRM backend** built with **NestJS, PostgreSQL, and Prisma**, featuring **JWT authentication, role-based access control, and clean domain separation**. Designed like a real-world backend, not a tutorial app.

**Key Capabilities**
-  JWT authentication + role-based authorization (ADMIN / EMPLOYEE)
-  User, Customer & Task management (full CRUD)
-  Task assignment with strict ownership rules
-  Pagination, search, and validation
-  Swagger / OpenAPI documentation with JWT support

**Tech Stack**
- NestJS (TypeScript)
- PostgreSQL + Prisma ORM
- Passport JWT, bcrypt
- class-validator, Swagger

**Why It Matters**
- Real RBAC enforcement (not route-level hacks)
- Clean modular architecture (auth, users, customers, tasks)
- Production-ready patterns: validation, error handling, security

> A backend that could actually survive first contact with real users.

---

### Vidthread
A modern platform for threaded video discussions, collaborative annotations, and time‑linked comments.
- Highlights:
  - Threaded, time‑anchored comments on videos
  - Real‑time updates for collaborators
  - Rich playback + annotation UI
- Tech: React, Node.js, MongoDB
- Repo: https://github.com/Neel-stack-deb/vidthread 

Quickstart
```bash
git clone https://github.com/Neel-stack-deb/vidthread.git
cd vidthread
npm install
npm run dev
```

---

### Zoogy
A product focused on [marketplace / media / subscriptions] 
- Highlights:
  - Clean UX for [buyers/sellers/media consumers]
  - Payment/subscription integrations
  - Dashboard + analytics
- Tech: React, Tailwind, Node.js, MongoDB
- Repo: https://github.com/Neel-stack-deb/zoogy

Quickstart
```bash
git clone https://github.com/Neel-stack-deb/zoogy.git
cd zoogy
npm install
npm run dev
```

---

##  ClaimAgent — Autonomous Healthcare Claims AI

**Turns 90-minute insurance authorizations into 3 minutes. No APIs. Real portals.**

ClaimAgent is a **production-grade AI system** that automates medical insurance prior authorizations using **agentic AI, RAG, vector search, and real browser automation**. Built in **24 hours** to attack a **$31B healthcare admin problem**.

**Repo**: https://github.com/Neel-stack-deb/ClaimAgent

**Live Demo:** https://claimagent-1.onrender.com

**Tech Highlights**
- Medical AI (RAG) with regulatory context  
- Agentic AI for medical necessity & fraud checks  
- Pinecone vector search for procedure matching  
- Playwright automation with human-like interaction  
- Node.js backend, real-time execution  

**Impact**
- 97% time reduction (90 min → 3 min)  
- ~$250 saved per claim  
- Works on real insurer portals (no APIs)

> AI that doesn’t just think — it *executes*.

---

##  Gravity Sandbox — Real-Time Multiplayer Physics Simulator 🏆

**🏆 WINNER — SimVerse’25 Hackathon**

Gravity Sandbox is a **real-time collaborative gravity simulation** where multiple users build and manipulate a shared universe live across devices. Think **Google Docs for Astrophysics**.

🔗 **Live Demo:** https://orbiting-canvas-3.onrender.com/

**What Makes It Cool**
-  Real-time multiplayer sync using **Socket.io**
-  Custom **N-Body physics engine** (no physics libraries)
-  Stable orbits via symplectic integration
-  Cinematic black holes, trails & spacetime grid
-  Runs at 60 FPS with optimistic UI

**Tech Stack**
- React + React Three Fiber + Three.js  
- Node.js + Express + Socket.io  
- Custom physics engine (Newtonian gravity)

Built in **24 hours** at **SimVerse’25**, organized by **ACS & ACM (VIT-AP)** — and **won the hackathon**.

> Turning equations into something you can *play with*.

---

### Realtime Backend Project
A high‑throughput realtime backend that powers live collaboration, presence, and event streaming.
- Highlights:
  - Scalable pub/sub and presence
  - Low‑latency fan‑out (WebSockets / server‑sent events)
  - Redis / message queue backing and horizontal scaling
- Tech: Node.js, Redis, Docker, Kubernetes (confirm your stack)
- Repo: https://github.com/Neel-stack-deb/realtime-backend 

Quickstart
```bash
git clone https://github.com/Neel-stack-deb/realtime-backend.git
cd realtime-backend
docker-compose up --build
```

---

##  How I Work
- Prioritize fast developer feedback loops and observability
- Prefer small, well‑tested increments with clear rollback
- Automate deployments with CI and infra as code

---

