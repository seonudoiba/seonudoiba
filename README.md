<h1 align="center">Abiodun Igbehinadun</h1>

<p align="center">
  <b>Full-Stack Engineer</b> · Laravel · Node.js · React · TypeScript · Elixir<br>
  I build multi-tenant SaaS, payment systems, IoT pipelines and AI agents that hold up in production.
</p>

<p align="center">
  <a href="https://abiodunstarr.online"><img src="https://img.shields.io/badge/Portfolio-abiodunstarr.online-0A66C2?style=flat&logo=googlechrome&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/abiostarr"><img src="https://img.shields.io/badge/LinkedIn-abiostarr-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:biodunrahman1@gmail.com"><img src="https://img.shields.io/badge/Email-biodunrahman1@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://twitter.com/Aigbehinadun"><img src="https://img.shields.io/badge/X-@Aigbehinadun-000000?style=flat&logo=x&logoColor=white" alt="X"></a>
  <a href="https://gitlab.com/biodunrahman1"><img src="https://img.shields.io/badge/GitLab-biodunrahman1-FC6D26?style=flat&logo=gitlab&logoColor=white" alt="GitLab"></a>
</p>

---

### About me

- 🏫 **Now:** lead engineer on **[EduSYS](https://edusys.ng)** for HyperCom, a multi-school SaaS platform for Nigerian schools
- 🤖 **Also now:** building the agent orchestrator for **Gentflo**, an AI sales agent, and the station management system for **Rekaz Petroleum**
- 🔧 **On the side:** **[ForgeFlow](https://github.com/seonudoiba/forgeflow)**, a durable workflow engine in Elixir/OTP and PostgreSQL
- 📍 Lagos, Nigeria · 5+ years · B.Sc. Computer Science, FUNAAB
- 💬 I write about AI developer tooling and agentic coding at [abiodunstarr.online/blog](https://abiodunstarr.online/blog)

---

### Featured work

#### 🔁 [ForgeFlow](https://github.com/seonudoiba/forgeflow): durable workflow orchestration
Temporal-style reliability on infrastructure you already run. Workflows are declarative, every step is persisted to Postgres, and in-flight work survives worker and node crashes.
- Elixir/OTP umbrella; Postgres is both the queue and the source of truth (`SKIP LOCKED`, atomic commits); coordinator elected through advisory locks
- **Tested against failure:** a deterministic simulation suite (N workers dying across 1,000 seeds), plus a real-cluster chaos test where killing 2 of 5 workers mid-run still gives **200/200 executions completed, 100% recovery**
- Phoenix REST API with OpenAPI spec, CLI, observability console, generated Grafana dashboards and SLO alerts, and ADRs for every major decision

`Elixir` `OTP` `Phoenix` `PostgreSQL` `Docker` `Grafana`

#### 🏫 [EduSYS](https://edusys.ng): multi-school SaaS
Turned a one-copy-per-school ERP into a single multi-tenant platform. It went live two days after work started.
- A subdomain per school, and a tenant-aware database driver that adds the school's filter to every query (234 tables). Every raw SQL query was audited, and a CI lint stops new ones from skipping the filter
- Self-serve registration and setup in about 2.5 seconds; Paystack, Flutterwave, Monnify, Interswitch and Remita confirmed by the gateway's server
- Drag-and-drop website builder with 16 themes; CI that installs from an empty database and crawls every page, then deploys with automatic rollback

`PHP 8.3` `MySQL` `GitHub Actions` `Cloudflare` *(private, client-owned)*

#### ⛽ [Rekaz Petroleum](https://rakaz-fe.vercel.app): station management
Multi-station fuel operations: tanks, pumps and dips, sales settlement pools, deliveries tracked on a map, daily closing, and live alerts per station and region over Socket.io.

`Node.js` `TypeScript` `Prisma` `PostgreSQL` `Socket.io` `React 19` `TanStack Query`

#### ✈️ [Expaq](https://expaq.tours): travel marketplace (founder)
Spring Boot backend with 30+ tables, commission and subscription billing, and Stripe/Paystack failover. Next.js frontend.
→ [`expaq`](https://github.com/seonudoiba/expaq) · [`expaq-backend`](https://github.com/seonudoiba/expaq-backend)

`Java` `Spring Boot` `Next.js` `TypeScript` `Stripe` `Paystack`

#### More, from client and employer work (not public)

| Project | What it does | Stack |
|---|---|---|
| **Gentflo** | AI agent that generates and publishes sales funnels to Ycode over MCP. Retry-safe Horizon jobs, LLM output checked against the database, ~90% less manual build time | Laravel · Horizon · Redis · OpenAI · Claude · MCP |
| **Galileosky telemetry server** | TCP ingestion for unmanned fuel stations: binary frames, CRC16 validation, Redis-buffered batched writes | Node.js · TCP · MySQL · Redis |
| **Marine.ng** | Maritime marketplace: one Laravel API for React web and React Native, PostGIS location search, WebSocket chat | Laravel · PostGIS · React Native |
| **ClientFocus** | Multi-tenant SaaS with roles enforced in Firestore rules, Stripe Connect split payments and Gemini summaries | Next.js · Firestore · Stripe · Genkit |
| **Moniwave** | Multi-tenant finance ERP serving 50+ businesses, with tenant-scoped queries and payment failover | Laravel · MySQL · Stripe · Paystack |
| **HoteSoft / FillyTutor** | Hotel management with Amadeus/OpenTripMap integrations; e-learning with a quiz engine | Laravel · Redis · Paystack |

---

### Tech I work with

**Languages and frameworks**<br>
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white)
![Elixir](https://img.shields.io/badge/Elixir-4B275F?style=flat&logo=elixir&logoColor=white)
![Phoenix](https://img.shields.io/badge/Phoenix-FD4F00?style=flat&logo=phoenixframework&logoColor=white)
![Java](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)

**Frontend and mobile**<br>
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat&logo=expo&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=flat&logo=vuedotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)

**Data and messaging**<br>
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Firebase](https://img.shields.io/badge/Firestore-FFCA28?style=flat&logo=firebase&logoColor=black)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat&logo=socketdotio&logoColor=white)

**AI**<br>
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat&logo=googlegemini&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=flat&logo=modelcontextprotocol&logoColor=white)

**Infrastructure and testing**<br>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?style=flat&logo=digitalocean&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![PHPUnit](https://img.shields.io/badge/PHPUnit-3776AB?style=flat&logo=php&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat&logo=jest&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)

---

<p align="center">
  <img height="165" src="https://github-readme-stats-three-eta-77.vercel.app/api?username=seonudoiba&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=github_dark&rank_icon=github" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats-three-eta-77.vercel.app/api/top-langs/?username=seonudoiba&layout=compact&hide_border=true&langs_count=8&theme=github_dark&card_width=320" alt="Top languages" />
</p>

<p align="center">
  <b>Open to full-stack and backend roles, remote or in Lagos, and to contract work.</b><br>
  <a href="mailto:biodunrahman1@gmail.com">biodunrahman1@gmail.com</a> · <a href="https://www.linkedin.com/in/abiostarr">LinkedIn</a>
</p>
