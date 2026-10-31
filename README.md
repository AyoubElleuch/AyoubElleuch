```text
+--[ ayoub@github:~ ]--------------------------------------------------+
| MOHAMED AYOUB ELEUCH                                                 |
| SOFTWARE & CLOUD ENGINEER  //  AWS SOLUTIONS ARCHITECT (SAA-C03)     |
| TYPESCRIPT / NEXT.JS / NODE.JS / POSTGRESQL / AWS / TERRAFORM / C++  |
+----------------------------------------------------------------------+
```

Software and cloud engineer building production web systems, real-time collaborative applications, and serverless AWS infrastructure provisioned with Terraform. Backed by a strong algorithmic foundation (**National Olympiad in Informatics finalist**), strict database-layer security (**PostgreSQL RLS / RBAC**), and automated **GitHub Actions OIDC** delivery pipelines.

`$ status` **Available immediately for remote software & cloud engineering roles and B2B contracts · Open to sponsored relocation · CET-aligned.**

[**Portfolio**](https://www.mohamedayoubeleuch.com/) · [**LinkedIn**](https://www.linkedin.com/in/ayoub-eleuch/) · [**LeetCode**](https://leetcode.com/u/ayoubelleuch/) · [**Email**](mailto:mmdayoub3@gmail.com)

---

## 01 / Featured Systems

### [AWS Task Manager](https://github.com/AyoubElleuch/aws-task-manager) · [Live app](https://taskmanager.mohamedayoubeleuch.com/) · [Architecture case study](https://www.mohamedayoubeleuch.com/work/aws-task-manager)

Serverless cloud platform provisioned end-to-end with **Terraform** (isolated bootstrap and locked, versioned S3 state) and deployed through **GitHub Actions OIDC** using short-lived IAM role credentials instead of static secrets.

- **Edge Delivery & Zero-Trust API:** React SPA served from private **S3** via **CloudFront Origin Access Control (OAC)**; **API Gateway** JWT verification with **Cognito**, hierarchical tenant ownership checks in **Node.js 22 Lambda** handlers, **DynamoDB** conditional writes, and **42 automated Vitest checks** across UI, API, and IaC.

`AWS (Lambda, API Gateway, DynamoDB, Cognito, CloudFront, S3)` `Terraform` `GitHub OIDC` `React` `TypeScript` `Node.js 22` `Vitest`

### Barnicoat Branding CRM & Commercial Platform · [Case study](https://www.mohamedayoubeleuch.com/work/barnicoat-branding-crm) · [Live CRM sandbox](https://barnicoat-branding-crm.vercel.app/login) · [Production site](https://barnicoatbranding.com/)

Proprietary agency operations CRM architected, shipped, and maintained under an ongoing commercial retainer.

- **Relational Security & Financial Reporting:** Engineered **10 PostgreSQL tables** enforced by **11 Row-Level Security (RLS) policies**, configurable **RBAC**, server-verified lead ownership, and SQL aggregation engines calculating renewals, operating costs, and tiered sales commissions.
- **Verification & Companion Web Platform:** Hardened with **26 Vitest** service/auth tests, **Playwright** E2E suites, an **Artillery** load profile, and CI security gates. Also built the agency's production web platform ([barnicoatbranding.com](https://barnicoatbranding.com/)) with **Three.js/OGL WebGL** shaders, **PostHog** funnel telemetry, and an automated **Python/FFmpeg** H.264 `faststart` media pipeline.

`Next.js 16` `TypeScript` `PostgreSQL (RLS)` `Supabase Auth` `Vitest` `Playwright` `Artillery` `Three.js / WebGL` `PostHog`

### [NovaStage](https://github.com/AyoubElleuch/NovaStage) · [Live platform](https://novastage.app) · [Architecture case study](https://www.mohamedayoubeleuch.com/work/novastage)

Real-time collaborative canvas for engineering roadmaps and AWS architecture diagrams, built around deterministic graph validation and conflict-free multi-user editing.

- **Distributed Concurrency & Access Control:** Exclusive node locking via PostgreSQL `SELECT FOR UPDATE` paired with **Upstash Redis** TTL heartbeat leases and live ownership handoff; 60fps `requestAnimationFrame` cursor interpolation over **Supabase Broadcast** and database-enforced **Row-Level Security**.
- **AI Graph Pipeline & Routing Engine:** Multi-stage **Gemini** orchestration with DFS cycle repair, Kahn's topological critical-path engine (*Release Pulse*), inside-out **Dagre** nested VPC layout, and visibility-graph orthogonal obstacle routing (*selected for the XERJ Corpus Hub*).

`Next.js 16` `React 19` `TypeScript` `PostgreSQL (RLS)` `Supabase Realtime` `Upstash Redis` `Dagre` `Gemini` `Vitest`

### [Algorithms & Competitive Programming](https://github.com/AyoubElleuch/Competitive-Programming-Solutions) · [Write-ups archive](https://www.mohamedayoubeleuch.com/cpp-solutions) · [Crossword Genetic Engine](https://github.com/AyoubElleuch/Crossword-Genetic-Algorithm)

**70+ C++ competitive solutions and reference algorithm implementations** (IOI, CCC, LeetCode), each documented with formal proofs of approach and time/space complexity, alongside a zero-dependency Python evolutionary layout engine using 2,000-candidate populations, DFS connectivity scoring, and generational crossover.

`C++` `Graph Theory` `Dynamic Programming` `Disjoint Set Union` `Segment Trees` `Genetic Algorithms` `Python`

---

## 02 / Experience

- **Software Engineer Intern · GBI Logistics** *(Remote, US · Sep 2025 – Feb 2026)*  
  Engineered production **Next.js** and **SQL** e-commerce product-customization and CMS catalog workflows; automated build, test, and containerized **Docker** deployment pipelines via **GitHub Actions** to Linux VPS infrastructure.
- **Part-Time Front-End Developer · Innopolis University (Advanced Engineering School)** *(Aug 2023 – May 2024)*  
  Built **Vue.js** operational interfaces integrated with **Python / FastAPI** services for machine-learning researchers to trigger model inference pipelines and inspect live evaluation telemetry.
- **Contract Software Engineer · Independent Client Delivery** *(Remote · 2024 – Present)*  
  Architect, deliver, and maintain commercial **Next.js / TypeScript / PostgreSQL** platforms under client retainer—owning schema design, **RLS/RBAC** security boundaries, automated unit/E2E testing, and analytics pipelines. [Full timeline →](https://www.mohamedayoubeleuch.com/experience)

---

## 03 / Open Source & Recognition

[![XERJ Corpus Hub contributor](https://hub.xerj.org/contributors/AyoubElleuch/badge.svg)](https://hub.xerj.org/contributors/AyoubElleuch)

- **[XERJ Corpus Hub](https://hub.xerj.org/contributors/AyoubElleuch):** NovaStage's nested AWS topology normalizer and visibility-graph obstacle-aware orthogonal routing engine were selected for the public open-source code index.
- **[Reverse Engineer Anything (REA)](https://github.com/morluto/rea)** — Merged upstream systems & diagnostics contributions ([all PRs](https://github.com/morluto/rea/pulls?q=is%3Apr+author%3AAyoubElleuch)):
  - [**#3776 — Exact UTF-8 frame-boundary byte accounting in the Cutter bridge**](https://github.com/morluto/rea/pull/3776): Replaced conservative character heuristics with exact UTF-8 byte counting to preserve mixed-script output within protocol frame limits without relaxing auth guards.
  - [**#6361 — Field-level nested artifact validation diagnostics**](https://github.com/morluto/rea/pull/6361): Preserved structured error paths and root validation causes across nested evidence schemas with regression coverage.

---

## 04 / Architecture & Stack

- **Cloud & Infrastructure:** `AWS (SAA-C03)` `Lambda` `API Gateway` `DynamoDB` `Cognito` `S3` `CloudFront` `CloudWatch` `Terraform` `Docker` `Kubernetes` `GitHub Actions (OIDC)`
- **Backend & Data:** `TypeScript` `Node.js` `PostgreSQL (RLS, SQL Functions)` `Supabase` `Prisma` `Upstash Redis` `REST APIs`
- **Frontend & Systems:** `Next.js` `React` `Vue.js` `Tailwind CSS` `C++` `Python` `SQL` `Vitest` `Playwright`

---

## 05 / Credentials & Academic Honors

**AWS Certifications (CertMetrics Verified):**  
[**Solutions Architect – Associate**](https://cp.certmetrics.com/amazon/en/public/verify/credential/1d97eb72b7df404e9c5d21cbe2d38e58) · [**AI Practitioner**](https://cp.certmetrics.com/amazon/en/public/verify/credential/bf28a394350a4fa78cddb8074385b3aa) · [**Cloud Practitioner**](https://cp.certmetrics.com/amazon/en/public/verify/credential/48bd846c58b24187bf0c52a1f8f6d26e)

**Distinctions & Education:**
- **National Finalist** — Tunisian Olympiad in Informatics (2022)
- **Full-Tuition Merit Scholarship** — Innopolis University *(2022 – 2024 · Four semesters completed: Algorithms & Data Structures, Operating Systems, Computer Architecture, Systems Design, Linear Algebra, Probability & Optimization)*
- **B.S. in Computer Science** — University of the People *(In progress · Expected June 2027, continuing undergraduate studies)*
