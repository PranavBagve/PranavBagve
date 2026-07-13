# Hi, I'm Pranav 👋

### Backend Software Engineer · Python, FastAPI, AWS · 3.5+ Years

I build production backend systems — API architecture, distributed/event-driven processing, database security, and cloud infrastructure. Recently architected **RESTREAT**, a multi-tenant hospitality SaaS platform, and led backend development for **Jii**, a live e-commerce marketplace serving 1,000+ users.

---

## 🚀 Featured Work

### RESTREAT — Multi-Tenant Hospitality Operations SaaS
*Production B2B SaaS platform for restaurants, cafes, bars, and cloud kitchens. Codebase is private (client/production project) — happy to walk through architecture in an interview.*

**🔗 Live:** [restreat.com](https://www.restreat.com/)

- **Data-layer multi-tenancy:** Enforced tenant isolation via PostgreSQL Row-Level Security policies derived from JWT context, with a three-layer authorization model (role × outlet capability × subscription plan) enforced identically in Postgres RLS, Supabase Edge Functions, and the client.
- **Security hardening:** Audited and remediated SSRF (printer integration), JWT forgery, SQL injection, unauthenticated endpoints, and user-enumeration vulnerabilities.
- **Real-time backend infra:** Built event-driven sync (Supabase Realtime/WebSockets) powering live table maps and a Kitchen Display System with station-based order routing, at sub-500ms latency.
- **Audit & authorization workflows:** Implemented a manager-approval (PIN) system with outlet-scoped authority and immutable, insert-only audit triggers for sensitive actions (voids, discounts).
- **Offline resilience:** Built an async FIFO queue over IndexedDB to safely capture mutations during network loss and reconcile on reconnect.

**Stack:** PostgreSQL · Supabase (Auth, Realtime, Edge Functions/Deno) · React · TypeScript · Vite · Tailwind

---

### Jii — Serverless E-Commerce Marketplace (Live, iOS + Android)
*Production marketplace app serving 1,000+ users across web and mobile.*

**🔗 Live:** [Web](https://www.jiiapp.com/) · [iOS](https://apps.apple.com/in/app/jii/id6756066462) · [Android](https://play.google.com/store/apps/details?id=com.jii.app)

- **Backend architecture:** Designed serverless FastAPI microservices on AWS Lambda and API Gateway, unifying web, iOS, and Android on one backend.
- **Event-driven processing:** Built an SQS/SNS-based order pipeline, decoupling checkout from fulfillment and increasing throughput by ~45%.
- **Data & performance:** Optimized MongoDB schema design, cutting API latency by ~35% under production load.
- **Auth & security:** Implemented Cognito-based JWT authentication with phone-first OTP onboarding (MSG91).
- **Infra ownership:** IAM roles, CloudFront caching, CloudWatch observability, EventBridge scheduling.

**Stack:** Python · FastAPI · AWS (Lambda, API Gateway, SQS, SNS, Cognito, EventBridge, CloudFront) · MongoDB · React Native

---

## 🛠️ Core Skills

**Backend & Architecture**
Python · FastAPI · Microservices · Event-Driven Architecture · REST APIs · System Design

**Cloud (AWS)**
Lambda · API Gateway · SQS/SNS · Cognito · EventBridge · CloudFront · CloudWatch · S3 · IAM

**Databases**
PostgreSQL · Row-Level Security · MongoDB · Supabase

**Security**
JWT · OAuth 2.0 · RBAC · Vulnerability Remediation (SSRF, SQLi, Auth Bypass)

**Frontend / Mobile** *(supporting breadth)*
React · React Native · TypeScript · Vite · Tailwind CSS

**DevOps**
Docker · CI/CD (GitHub Actions, Jenkins) · Infrastructure as Code

<details>
<summary>Also experienced in: QA & Test Automation (Selenium, Playwright, ISTQB Certified)</summary>

Built modular test-automation frameworks (C#/.NET, Python), CI/CD pipelines, and API automation suites at Infuse — increased test execution speed by ~40%, expanded coverage to 85%, cut deployment cycle time by ~25%.
</details>

---

## 📊 GitHub Stats
![My GitHub Stats](images/userstats.svg)

---

## 📫 Let's Connect
- **LinkedIn:** [pranavbagve](https://www.linkedin.com/in/pranav-bagve)
- **Email:** pranavbagve3055@gmail.com
