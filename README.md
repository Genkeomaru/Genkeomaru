<div align="center">

# Guilherme Rodrigues · Genkeomaru

**Accountant turned Developer** — Bridging the gap between Business Logic and Full-Stack Software Engineering

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/guilherme-rodrigues-gr/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:genkeomaru.dev@gmail.com)

</div>

---

## About Me

I hold a Bachelor's degree in Accounting and am currently pursuing a degree in Systems Analysis and Development — which means I don't just write code; I understand the financial and operational logic that runs behind it.

My background in tax accounting gave me an unusual engineering superpower: **I read systems at the data-flow level before writing a single line of code**. Today, I channel that analytical rigor into building full-stack solutions that solve real enterprise problems — from KPI orchestration platforms to automated document generation pipelines.

I build with a product-minded approach: performance, clean architecture, semantic markup, and accessibility aren't afterthoughts — they're defaults.

Currently working as a **Full Stack Developer at Stattus4**, a cleantech company in the sanitation sector.

---

## 🛠 Technical Toolbox

### Languages & Frameworks
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### Databases & BaaS
![SQL Server](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=for-the-badge&logo=microsoft-sql-server&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

### Cloud, DevOps & Tooling
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Google Apps Script](https://img.shields.io/badge/Google%20Apps%20Script-4285F4?style=for-the-badge&logo=google&logoColor=white)

---

## 💼 Case Studies

### Case 1 — Tax Reconciliation Automation · Aethra

> *Turning a 20-hour monthly solo process into a fast, reliable automation.*

| | |
|---|---|
| **Problem** | The reconciliation between the Tax and Inventory departments was a manual, end-to-end process I independently owned each month — consuming approximately 20 hours of my operational time and remaining highly prone to systematic errors before the data reached the controlling department for inventory closure. |
| **Solution** | Mapped the entire data flow from its origin in SAP. Engineered a high-performance automation tool in Excel with embedded business rule validation logic, eliminating the need for manual cross-referencing at every stage of the pipeline. |
| **Impact** | **30% reduction in overall closing-cycle time**, with manual reconciliation errors cut by **90–100%** — freeing my time to focus on critical financial analysis and directly accelerating the controlling department's inventory closure calculations. |
| **Tools** | SAP · Microsoft Excel (Advanced Automation) · Business Logic Modeling |

> This project was the catalyst for my transition into software development — I realized my real passion is designing logical systems that solve real-world operational problems.

---

### Case 2 — Plataforma BMs · Stattus4

> *Full-stack platform (Product Owner + Developer) automating measurement-billing document generation across three product lines.*

| | |
|---|---|
| **Challenge** | Manual, multi-source data collection (spreadsheets, monitoring systems, CRM) for generating client billing/measurement reports (Boletins de Medição), across three distinct business lines with different data sources and calculation rules. |
| **Solution** | Architected and develop a full-stack platform with a **Next.js/React** frontend (Vercel) and a dedicated **Node.js/Express + Puppeteer** PDF generation service (Render), backed by **PostgreSQL (Supabase)** and module-specific caching via **Upstash Redis**. Integrates with CRM (Monday.com/HubSpot) and partner telemetry APIs. Covered by a suite of **900+ automated tests**. |
| **Impact** | Eliminated manual document assembly for the platform's active modules. Diagnosed and fixed two silent production data-loss bugs (a cyclic-reference guard and an empty CRM matching field) that were hiding **451 of 1,247** client records from company operations, restoring full visibility with no data loss. |
| **Tech Stack** | Next.js · TypeScript · Node.js/Express · Puppeteer · PostgreSQL (Supabase) · Upstash Redis · REST APIs · Docker |

---

## 🛠️ Independent Projects

### Banco de Ponto — Time & Attendance Platform (In Development)
Personal web application for employee time tracking and hour-bank management, built with **Next.js 15** (App Router/TypeScript) and **Supabase** (PostgreSQL). Three-tier RBAC enforced server-side (middleware, route handlers, and RLS — never UI-only), an atomic audit log on every edit, and a state machine for monthly closing with a grace period before data deletion. Identified and fixed three security vulnerabilities during development: a timing leak in user enumeration, insufficient JWT secret entropy, and RLS bypass via the database owner role.

### Mahaya & Stream Tracker — Automation Bots
Scalable automated service bots engineered to monitor external APIs and integrate third-party platform data in real-time. Both systems are designed around asynchronous **JavaScript** execution patterns, optimized **JSON** storage strategies, and resilient polling logic — built to run continuously with minimal overhead and maximum observability.

---

## 🎯 Product & UX Mindset

I engineer with the end user in mind — always.

- **Performance-First:** Every application I build is measured against Core Web Vitals. Fast is a feature.
- **Semantic & Accessible:** I write clean, semantic HTML and follow WCAG accessibility guidelines. Inclusive design is non-negotiable.
- **Design Precision:** I care about the gap between a good product and a great one — spacing, hierarchy, motion, and contrast are engineering decisions, not afterthoughts.
- **Business-Logic Driven:** My accounting background means I always ask *why* before I ask *how*. Understanding the domain is the first step to building the right abstraction.

---

## 🎓 Education

- **B.Sc. in Accounting Sciences** — Completed
- **B.Sc. in Systems Analysis and Development** — In progress

---

<div align="center">

*"The best code I ever wrote wasn't code at all — it was a clear understanding of the problem."*

[![LinkedIn](https://img.shields.io/badge/Let's%20Connect-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/guilherme-rodrigues-gr/)
[![Gmail](https://img.shields.io/badge/Send%20a%20Message-Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:genkeomaru.dev@gmail.com)

</div>
