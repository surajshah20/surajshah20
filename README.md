<img align="center" alt="Banner" src="https://user-images.githubusercontent.com/22107794/139580686-887df369-edb8-4bc8-b607-4fbf6d7e4866.gif"/>

<h1 align="left">
  <img src="https://user-images.githubusercontent.com/18350557/176309783-0785949b-9127-417c-8b55-ab5a4333674e.gif" width="28" />
  Hi, I'm <strong>Suraj Kumar Sah</strong>
</h1>

<h3>🚀 Full-Stack Software Engineer | React · Node.js · PostgreSQL · Zustand · Gemini AI | Nepal 🇳🇵</h3>

<div align="left">
  <img align="right" width="350" src="https://user-images.githubusercontent.com/74038190/221352989-518609ab-b4d1-459e-929f-a08cd2bd9b3c.gif" />

  <p>
    <strong>BSc (Hons) Computer Systems Engineering</strong> graduate from <strong>ISMT College</strong> (Affiliated with the <strong>University of Sunderland, UK</strong>) with final-year results published and immediate full-time availability for junior software engineering roles.
  </p>

  <p>
    Full-Stack Software Engineer with hands-on experience architecting and shipping production React, Node.js, and PostgreSQL web platforms. Creator of <strong>BlushBook</strong>, a live commercial web-to-print SaaS with 30+ physical print orders fulfilled across Nepal, and <strong>DevGuard AI</strong>, an autonomous LLM-powered security code-review agent.
  </p>

  <p>
    Strong foundations in deterministic static analysis (ESLint API / AST), complex client-side canvas state (Konva.js / Zustand), high-DPI client-side print pipelines (jsPDF 300 DPI), and resilient REST API design.
  </p>

  <p>
    <img src="https://img.shields.io/badge/🌍_Kathmandu,_Nepal-1e1e2e?style=for-the-badge" />
    <img src="https://img.shields.io/badge/💼_Available_for_Full--Time_Roles-1e1e2e?style=for-the-badge" />
    <img src="https://img.shields.io/badge/🚀_Shipping_Production_SaaS-1e1e2e?style=for-the-badge" />
  </p>

  <h3>🌐 Connect With Me</h3>

  <p align="left">
    <a href="https://www.linkedin.com/in/surajshahcs">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
    </a>
    <a href="https://github.com/surajshah20">
      <img src="https://img.shields.io/badge/GitHub-1A1A1A?style=for-the-badge&logo=github&logoColor=white" />
    </a>
    <a href="mailto:suraj27227@gmail.com">
      <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
    </a>
    <a href="https://portfolio-ebon-six-74.vercel.app/">
      <img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" />
    </a>
  </p>

  <img src="https://komarev.com/ghpvc/?username=surajshah20&style=flat-square&color=blue" alt="Profile Views"/>
</div>

<br clear="all" />

---

# 🚀 Featured Projects & Engineering Highlights

### 🛡️ DevGuard AI: Autonomous Code Review & Security Analysis Agent
A full-stack security review agent combining deterministic AST static analysis with Google Gemini LLMs to detect vulnerabilities, explain root causes, and propose automated git patch fixes.

* **Hybrid Analysis Engine:** Combined deterministic AST static analysis with Google Gemini LLMs to uncover security vulnerabilities, evaluate root causes, and suggest actionable remediation.
* **In-Memory GitHub Inspection:** Built an in-memory repository scanner over the GitHub REST API bounding file size/counts, redacting credentials (PATs, AWS keys, secret tokens), and mitigating prompt injection through strict isolation.
* **OWASP & Static Rules:** Built a custom vulnerability detector covering OWASP Top 10 and CWEs (command injection, SQLi, eval, path traversal, weak crypto) alongside an in-memory ESLint engine with zero disk writes.
* **Automated Patch Delivery:** Generates unified git diff patches (`.patch`) enabling instant application via `git apply`.
* **CI & Automated Tests:** Dark-theme dashboard with severity distribution bars, filtering, and markdown reports, backed by **44 automated tests** and a GitHub Actions CI workflow.
* **Tech Stack:** Node.js · Express · React · Vite · Google Gemini API · ESLint API · Zod · Octokit  
👉 [Live Demo](https://devguardai-gqng.onrender.com)

---

### 📚 BlushBook: Commercial Web-to-Print Photobook SaaS
A live production web-to-print platform enabling customers across Nepal to design, customize, and order physical photobooks, fulfilling **30+ custom print orders**.

* **Canvas Architecture:** Architected an interactive HTML5 Konva.js canvas engine with real-time element transformations, photo pan/zoom cropping geometry, and dynamic snap-alignment guides.
* **300 DPI Print Pipeline:** Built an in-browser PDF compilation pipeline using **jsPDF** that generates 300 DPI production-ready PDFs with automated bleed margins and dynamic spine-width calculations.
* **State & Draft Recovery:** Implemented **Zustand** state management with multi-step undo/redo history snapshots and automated draft recovery to prevent data loss in long design sessions.
* **Cold-Start Elimination:** Optimized initial template loading from **~15s to near-instant** by resolving PostgreSQL cold starts through in-memory route caching and pre-bundled static snapshots.
* **Backend & RBAC:** Built REST APIs with role-based access control (Admin/User), PostgreSQL data management, and Cloudinary media pipelines.
* **Tech Stack:** React · Node.js · Express · PostgreSQL · Konva.js · Zustand · Cloudinary · jsPDF  
👉 [getblushbook.com](https://getblushbook.com)

---

### 💰 Ledger: Finance & Expense Analytics Dashboard
A responsive personal finance dashboard featuring balance analytics, transaction CRUD, simulated role-based access, and light/dark themes.

* **Reactive State Engine:** Engineered a lightweight reactive state store in vanilla JS with localStorage, keeping UI and data in sync without a third-party framework.
* **Data Visualization:** Integrated Chart.js to visualize cash-flow dynamics, spending distribution, and real-time balance trends.
* **Tech Stack:** Vanilla JavaScript (ES6+) · HTML5 · CSS3 · Chart.js  
👉 [Live Demo](https://finance-dashboardui.netlify.app/) · [GitHub Repository](https://github.com/surajshah20/finance-dashboard)

---

### 🏔️ ExploreHimalaya: Trekking Booking Platform
End-to-end trekking booking application with destination pages, interactive booking workflows, and payment integration for multi-tier packages.

* **Booking Workflows:** Destination browsing, itinerary selection, and multi-tier package reservation workflows.
* **REST Architecture:** RESTful endpoints handling package details, user inquiries, and booking transactions backed by PostgreSQL.
* **Tech Stack:** React · Node.js · Express · PostgreSQL · REST APIs  
👉 [Live Demo](https://explorehimalaya.vercel.app) · [GitHub Repository](https://github.com/surajshah20/explorehimalaya)

---

### 💹 PrimeTrade: Full-Stack Trading Platform
Trading platform backend and React dashboard with JWT authentication, role-based access control, and protected PostgreSQL-backed routes.

* **Authentication & RBAC:** Secure token signing, bcrypt password encryption, and middleware guards safeguarding trader and admin operations.
* **Transactional Reliability:** Protected RESTful endpoints backed by PostgreSQL with transactional integrity.
* **Tech Stack:** React · Node.js · Express · PostgreSQL · JWT  
👉 [GitHub Repository](https://github.com/surajshah20/primetrade-backend)

---

### 🤖 AI-Solutions: AI Startup Platform & CMS (Capstone)
Full-stack academic capstone project featuring a custom content management system, bcrypt-secured admin dashboard, and an integrated AI assistant.

* **Admin CMS:** Secure CMS with full CRUD capabilities, bcrypt password encryption, and session authentication.
* **Rigorous Verification:** Validated system reliability and edge-case resilience through **58 documented black-box test cases**.
* **Tech Stack:** Node.js · Express · PostgreSQL · EJS · bcrypt  
👉 [GitHub Repository](https://github.com/surajshah20/ai-solutions)

---

# 🛠️ Tech Stack & Arsenal

<p align="center">
<table>
<tr>
<td width="50%" align="center">

### 💻 Languages & Frontend
<img src="https://skillicons.dev/icons?i=js,ts,react,vite,html,css,tailwind" />

</td>
<td width="50%" align="center">

### ⚙️ Backend & APIs
<img src="https://skillicons.dev/icons?i=nodejs,express,nextjs" />

</td>
</tr>
<tr>
<td width="50%" align="center">

### 🗄️ Databases & Cloud
<img src="https://skillicons.dev/icons?i=postgresql,mongodb,vercel" />

</td>
<td width="50%" align="center">

### 🧰 Testing, DevOps & Tools
<img src="https://skillicons.dev/icons?i=githubactions,git,github,postman,figma" />

</td>
</tr>
</table>
</p>

---

# 📊 GitHub Stats

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=surajshah20&show_icons=true&theme=github_dark&hide_border=true"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=surajshah20&layout=compact&theme=github_dark&hide_border=true"/>

<br/>

<img src="https://streak-stats.demolab.com?user=surajshah20&theme=dark&hide_border=true"/>

</div>

---

# 🏆 GitHub Achievements

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=surajshah20&theme=darkhub&no-frame=true&margin-w=15"/>
</div>

---

# 🎯 2026 Goals & Milestones

* ✅ Shipped **BlushBook** to live production (30+ physical photobook orders delivered across Nepal)
* ✅ Architected & shipped **DevGuard AI** (Autonomous AST + Gemini LLM security code review agent)
* 🔲 Secure a full-time **Full-Stack / Junior Software Engineering** role
* 🔲 Deep dive into Automated E2E Testing (Playwright) & advanced CI/CD pipelines
* 🔲 Advanced PostgreSQL query optimization, connection pooling & distributed systems

---

# 📖 Currently Exploring

* Automated End-to-End Testing & Regression Suites (Playwright)
* Deterministic Static Analysis & AST Transformations
* Enterprise Backend Architecture & Domain-Driven Design
* PostgreSQL Performance Tuning, Indexing & Connection Pooling

---

<div align="center">

### ⭐ Clean Architecture · Production Reliability · Building from Kathmandu 🇳🇵

</div>
