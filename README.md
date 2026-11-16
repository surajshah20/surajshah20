<p align="center">
  <img src="assets/hero.svg" alt="Suraj Kumar Sah — Full-Stack Software Engineer" width="100%"/>
</p>

<p align="center">
  <a href="https://readme-typing-svg.demolab.com"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2600&pause=800&color=00FF9C&center=true&vCenter=true&width=800&lines=React+%C2%B7+Node.js+%C2%B7+PostgreSQL+%C2%B7+AI;BSc+(Hons)+%E2%80%94+ISMT+%C3%97+University+of+Sunderland;Building+from+Kathmandu+%F0%9F%87%B3%F0%9F%87%B5;Let's+build+something+insane+%F0%9F%9A%80" alt="typing"/></a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/surajshahcs"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/surajshah20"><img src="https://img.shields.io/badge/GitHub-1A1A1A?style=for-the-badge&logo=github&logoColor=white"/></a>
  <a href="mailto:suraj27227@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://portfolio-ebon-six-74.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"/></a>
</p>

<img src="assets/divider.svg" width="100%"/>

<img src="assets/t-projects.svg" width="100%"/>

<p align="center">
  <a href="https://getblushbook.com"><img src="assets/card-blushbook.svg" width="49%"/></a>
  <a href="https://devguardai-gqng.onrender.com"><img src="assets/card-devguard.svg" width="49%"/></a>
  <a href="https://tender-mero.vercel.app/"><img src="assets/card-tendermero.svg" width="49%"/></a>
  <a href="https://explorehimalaya.vercel.app"><img src="assets/card-explorehimalaya.svg" width="49%"/></a>
  <a href="https://github.com/surajshah20/primetrade-backend"><img src="assets/card-primetrade.svg" width="49%"/></a>
  <a href="https://github.com/surajshah20/ai-solutions"><img src="assets/card-aisolutions.svg" width="49%"/></a>
  <a href="https://finance-dashboardui.netlify.app/"><img src="assets/card-ledger.svg" width="49%"/></a>
</p>

<p align="center"><sub>👆 click a card to open the project · 👇 expand for the full breakdown</sub></p>

<details>
<summary><b>🛡️ DevGuard AI — Autonomous Code Review & Security Analysis Agent</b></summary>

A full-stack security review agent combining deterministic AST static analysis with Google Gemini LLMs to detect vulnerabilities, explain root causes, and propose automated git patch fixes.

- **Hybrid Analysis Engine:** deterministic AST static analysis + Google Gemini LLMs to uncover vulnerabilities, evaluate root causes, and suggest actionable remediation.
- **In-Memory GitHub Inspection:** repository scanner over the GitHub REST API bounding file size/counts, redacting credentials (PATs, AWS keys, secret tokens), and mitigating prompt injection through strict isolation.
- **OWASP & Static Rules:** custom detector covering OWASP Top 10 and CWEs (command injection, SQLi, eval, path traversal, weak crypto) plus an in-memory ESLint engine with zero disk writes.
- **Automated Patch Delivery:** generates unified git diff patches (`.patch`) applied instantly via `git apply`.
- **CI & Automated Tests:** dark-theme dashboard with severity distribution bars, filtering and markdown reports, backed by **44 automated tests** and a GitHub Actions CI workflow.

**Stack:** Node.js · Express · React · Vite · Google Gemini API · ESLint API · Zod · Octokit
👉 [Live Demo](https://devguardai-gqng.onrender.com)

</details>

<details>
<summary><b>📚 BlushBook — Commercial Web-to-Print Photobook SaaS</b></summary>

A live production web-to-print platform enabling customers across Nepal to design, customize, and order physical photobooks, fulfilling **30+ custom print orders**.

- **Canvas Architecture:** interactive HTML5 Konva.js canvas engine with real-time element transformations, photo pan/zoom cropping geometry, and dynamic snap-alignment guides.
- **300 DPI Print Pipeline:** in-browser PDF compilation with **jsPDF** producing 300 DPI production-ready PDFs with automated bleed margins and dynamic spine-width calculations.
- **State & Draft Recovery:** **Zustand** state management with multi-step undo/redo history snapshots and automated draft recovery to prevent data loss in long design sessions.
- **Cold-Start Elimination:** template loading cut from **~15s to near-instant** by resolving PostgreSQL cold starts through in-memory route caching and pre-bundled static snapshots.
- **Backend & RBAC:** REST APIs with role-based access control (Admin/User), PostgreSQL data management, and Cloudinary media pipelines.

**Stack:** React · Node.js · Express · PostgreSQL · Konva.js · Zustand · Cloudinary · jsPDF
👉 [getblushbook.com](https://getblushbook.com)

</details>

<details>
<summary><b>🏛️ TenderMero — Centralized Procurement & Tender Intelligence Platform</b></summary>

An institutional-grade tender aggregation platform for Nepal, collecting, standardizing, and indexing public procurement notices from PPMO and e-GP portals into a searchable full-stack marketplace.

- **AI Ingestion Pipeline:** asynchronous crawler using Firecrawl and Claude AI schema extraction, transforming heterogeneous public notices into typed JSON records with automated deadline tracking.
- **PostgreSQL GIN Full-Text Search:** database-level search via `tsvector` and GIN indexing with automated triggers, plus SHA-256 cryptographic deduplication and exponential backoff retry safeguards.
- **Transactional Integrity:** relational PostgreSQL schema on Neon with `node-pg-migrate` migrations and ACID transaction rollbacks for multi-record ingestion.
- **Server-State Caching:** React 18 dashboard with **TanStack Query v5** for intelligent caching, background revalidation, instant sector filtering, and personal watchlist tracking.
- **Production Security:** hybrid authentication (JWT + rotating `httpOnly` refresh cookies with cross-site `SameSite=None`), rate limiting, and role-based access control (Admin/Bidder).

**Stack:** React 18 · Node.js · Express · PostgreSQL · TanStack Query · Firecrawl · Claude AI · Neon · Vite
👉 [Live Demo](https://tender-mero.vercel.app/) · [GitHub](https://github.com/surajshah20/TenderMero)

</details>

<details>
<summary><b>🏔️ ExploreHimalaya — Trekking Booking Platform</b></summary>

End-to-end trekking booking application with destination pages, interactive booking workflows, and payment integration for multi-tier packages.

- **Booking Workflows:** destination browsing, itinerary selection, and multi-tier package reservation workflows.
- **REST Architecture:** RESTful endpoints handling package details, user inquiries, and booking transactions backed by PostgreSQL.

**Stack:** React · Node.js · Express · PostgreSQL · REST APIs
👉 [Live Demo](https://explorehimalaya.vercel.app) · [GitHub](https://github.com/surajshah20/explorehimalaya)

</details>

<details>
<summary><b>💹 PrimeTrade — Full-Stack Trading Platform</b></summary>

Trading platform backend and React dashboard with JWT authentication, role-based access control, and protected PostgreSQL-backed routes.

- **Authentication & RBAC:** secure token signing, bcrypt password encryption, and middleware guards safeguarding trader and admin operations.
- **Transactional Reliability:** protected RESTful endpoints backed by PostgreSQL with transactional integrity.

**Stack:** React · Node.js · Express · PostgreSQL · JWT
👉 [GitHub](https://github.com/surajshah20/primetrade-backend)

</details>

<details>
<summary><b>🤖 AI-Solutions — AI Startup Platform & CMS (Capstone)</b></summary>

Full-stack academic capstone project featuring a custom content management system, bcrypt-secured admin dashboard, and an integrated AI assistant.

- **Admin CMS:** secure CMS with full CRUD capabilities, bcrypt password encryption, and session authentication.
- **Rigorous Verification:** validated reliability and edge-case resilience through **58 documented black-box test cases**.

**Stack:** Node.js · Express · PostgreSQL · EJS · bcrypt
👉 [GitHub](https://github.com/surajshah20/ai-solutions)

</details>

<details>
<summary><b>💰 Ledger — Finance & Expense Analytics Dashboard</b></summary>

A responsive personal finance dashboard featuring balance analytics, transaction CRUD, simulated role-based access, and light/dark themes.

- **Reactive State Engine:** lightweight reactive state store in vanilla JS with localStorage, keeping UI and data in sync without a third-party framework.
- **Data Visualization:** Chart.js to visualize cash-flow dynamics, spending distribution, and real-time balance trends.

**Stack:** Vanilla JavaScript (ES6+) · HTML5 · CSS3 · Chart.js
👉 [Live Demo](https://finance-dashboardui.netlify.app/) · [GitHub](https://github.com/surajshah20/finance-dashboard)

</details>

<img src="assets/divider.svg" width="100%"/>

<img src="assets/t-stack.svg" width="100%"/>

<p align="center">
  <img src="https://skillicons.dev/icons?i=js,ts,react,vite,html,css,tailwind,nodejs,express,nextjs,postgresql,prisma,mongodb,vercel,githubactions,git,github,postman,figma&perline=10" />
</p>

<img src="assets/divider.svg" width="100%"/>

<img src="assets/t-roadmap.svg" width="100%"/>

```diff
+ [DONE] BlushBook live in production — 30+ physical photobook orders delivered
+ [DONE] DevGuard AI — AST + Gemini LLM security agent
+ [DONE] TenderMero — Firecrawl + Claude AI procurement platform
! [NOW]  Playwright E2E testing & CI/CD pipelines
! [NOW]  PostgreSQL tuning, indexing & connection pooling
- [NEXT] Land a Full-Stack / Frontend / QA Engineering role  ← you could be the commit
```

<img src="assets/divider.svg" width="100%"/>

<img src="assets/t-stats.svg" width="100%"/>

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=surajshah20&show_icons=true&theme=tokyonight&hide_border=true&bg_color=00000000"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=surajshah20&layout=compact&theme=tokyonight&hide_border=true&bg_color=00000000"/>
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com?user=surajshah20&theme=tokyonight&hide_border=true&background=00000000"/>
</p>
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=surajshah20&theme=onedark&no-frame=true&margin-w=15"/>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=surajshah20&style=for-the-badge&color=00ff9c&label=VISITORS" alt="views"/>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ff9c,50:302b63,100:0f0c29&height=130&section=footer&text=Clean%20Architecture%20%C2%B7%20Production%20Reliability&fontSize=22&fontColor=ffffff&fontAlignY=70" width="100%"/>
