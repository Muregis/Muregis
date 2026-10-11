<div align="center">

# Hey there, I'm Victor Muregi 👋

<a href="https://personal-portfolio-ochre-seven-62.vercel.app">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=38BDF8&center=true&vCenter=true&width=620&height=45&lines=Full-Stack+Software+Engineer;Founder+%40+MuregiScore+Technologies;Architecting+Production+Business+Systems;Building+EduCore+%7C+Core+CRM+%7C+Ratiba" alt="Typing SVG Banner" />
</a>

<p align="center">
  <b>Building robust multi-tenant SaaS, bulletproof relational schemas, and real-time payment rails for African institutions and businesses.</b>
</p>

<p align="center">
  <a href="https://personal-portfolio-ochre-seven-62.vercel.app"><img src="https://img.shields.io/badge/🌐_Portfolio-Live_Site-0ea5e9?style=for-the-badge" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/victor-muregi"><img src="https://img.shields.io/badge/💼_LinkedIn-Connect-0284c7?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:i.am.muregi@gmail.com"><img src="https://img.shields.io/badge/📬_Email-Get_in_Touch-10b981?style=for-the-badge" alt="Email" /></a>
</p>

</div>

---

### ⚡ The 15-Second Snapshot

* 🚀 **Founder & Full-Stack Engineer** at **MuregiScore Technologies** in Nairobi, Kenya.
* 🎓 **Computer Science** student (Diploma Level 6) at Kiambu National Polytechnic.
* 🛠️ **What I Build:** Production-grade business systems that replace error-prone manual ledgers and fragmented spreadsheets with auditable, resilient software.
* 💳 **Payment & Security Focus:** Idempotent **Safaricom M-Pesa Daraja** payment webhooks, multi-tenant RBAC, and ACID ledger reconciliation.
* 🏆 **Flagship Systems:** **EduCore** (School Operations SaaS), **Core CRM** (Multi-Tenant Sales & KDPA Engine), and **EduCore Ratiba** (Automated Scheduling Engine).

---

### 📈 Developer Activity & Systems Scale

<div align="center">
  <a href="https://github.com/Muregis">
    <img src="https://github-readme-stats.vercel.app/api?username=Muregis&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&icon_color=38bdf8&text_color=e2e8f0" alt="Victor Muregi's GitHub Activity" height="165" />
  </a>
  <a href="https://github.com/Muregis">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Muregis&layout=compact&hide_border=true&bg_color=0d1117&title_color=38bdf8&text_color=e2e8f0" alt="Victor Muregi's Top Languages" height="165" />
  </a>
</div>

---

## 🚀 Flagship Production Systems

### 🎓 1. [EduCore](https://github.com/Muregis/educore-school-management-system) — Multi-Tenant School Management SaaS
> *Comprehensive institutional administration, fee accounting, and academic reporting platform built for Kenyan schools.*

[![Live Demo](https://img.shields.io/badge/🟢_Live_Demo-educore--pi.vercel.app-10b981?style=flat-square)](https://educore-school-management-system-pi.vercel.app)
[![Source Code](https://img.shields.io/badge/📦_GitHub-Muregis%2Feducore-1e293b?style=flat-square&logo=github)](https://github.com/Muregis/educore-school-management-system)
[![Case Study](https://img.shields.io/badge/📖_Architecture-Deep_Dive-0ea5e9?style=flat-square)](https://personal-portfolio-ochre-seven-62.vercel.app/projects/educore)

* **The Problem:** Schools struggle with paper ledgers, delayed fee reconciliation, fragmented student records, and error-prone term report compilation across multiple campuses.
* **Engineering Highlights:**
  * **Strict Multi-Tenancy:** Complete tenant boundary isolation keyed by `school_id` across all database queries.
  * **Granular RBAC:** 5-tier access control (Admin, Principal, Teacher, Bursar, Student).
  * **Resilient Payments:** Idempotent Safaricom M-Pesa Daraja and Paystack webhook handling ensuring zero double-crediting during network retries.
  * **CBC Report Cards:** Automated term grade compilation compliant with Kenya's Competency-Based Curriculum.
* **Stack:** `React` · `TypeScript` · `Node.js` · `Express REST API` · `Supabase PostgreSQL` · `Tailwind CSS`

---

### 💼 2. [Core CRM](https://github.com/Muregis/Core-Crm-model) — Multi-Tenant Sales Pipeline & KDPA Compliance CRM
> *Enterprise customer relationship engine with background job queues and localized African business workflows.*

[![Source Code](https://img.shields.io/badge/📦_GitHub-Muregis%2FCore--Crm--model-1e293b?style=flat-square&logo=github)](https://github.com/Muregis/Core-Crm-model)
[![Case Study](https://img.shields.io/badge/📖_Architecture-Deep_Dive-0ea5e9?style=flat-square)](https://personal-portfolio-ochre-seven-62.vercel.app/projects/core-crm)
[![Tests Passing](https://img.shields.io/badge/🧪_Tests-47%2F47_Passing-10b981?style=flat-square)](https://github.com/Muregis/Core-Crm-model)

* **The Problem:** SMEs and SACCOs leak sales opportunities when prospect conversations, payment agreements, and deal follow-ups are scattered across personal WhatsApp threads and unmonitored notebooks.
* **Engineering Highlights:**
  * **Automated Tenant Onboarding:** Self-service registration provisioning tenant subdomains, stages, and localized settings.
  * **AES-256-GCM Credential Vault:** Per-tenant encrypted storage for Safaricom Daraja shortcodes, passkeys, and API secrets.
  * **BullMQ & Redis Fair Queues:** Asynchronous worker processing with tenant grouping to eliminate noisy-neighbor bottlenecks.
  * **Session Invalidation & Blocklist:** Rotating refresh tokens with immediate JWT blocklisting upon logout.
  * **KDPA 2019 Compliance:** Automated PII masking in logs, Section 26 data exports, and audit-safe anonymization.
* **Stack:** `React` · `TypeScript` · `Node.js` · `Express` · `MySQL` · `Redis` · `BullMQ` · `Jest/Supertest`

---

### 🗓️ 3. [EduCore Ratiba](https://github.com/Muregis/Educore-Ratiba) — Automated Timetabling & Constraint Solver
> *High-performance scheduling engine solving combinatorial class, teacher, and room allocation constraints.*

[![Live Demo](https://img.shields.io/badge/🟢_Live_Demo-educoreratiba.vercel.app-10b981?style=flat-square)](https://educoreratiba.vercel.app)
[![Source Code](https://img.shields.io/badge/📦_GitHub-Muregis%2FEducore--Ratiba-1e293b?style=flat-square&logo=github)](https://github.com/Muregis/Educore-Ratiba)
[![Case Study](https://img.shields.io/badge/📖_Architecture-Deep_Dive-0ea5e9?style=flat-square)](https://personal-portfolio-ochre-seven-62.vercel.app/projects/educore-ratiba)

* **The Problem:** School administrators spend days manually constructing term timetables, frequently causing teacher double-booking, room conflicts, and laboratory bottlenecks under KICD curriculum rules.
* **Engineering Highlights:**
  * **FET Engine Integration:** Integrates the open-source Free Evolutionary Timetabling (FET) solver via secure process control (`proc_open`) and XML serialization.
  * **Pre-Flight Validation:** Pure-PHP constraint validator checks teacher workloads and subject quotas before firing the solver, preventing state-space explosion.
  * **Live Clash Detection:** Real-time post-generation collision warnings during interactive manual period adjustments.
  * **Offline Resilience:** Fully functional in low-connectivity and offline environments for rural institutions.
* **Stack:** `PHP 8+` · `FET Constraint Solver Engine` · `MySQL / PostgreSQL` · `Dompdf`

---

### 🐄 4. [Livestock Management Platform](https://github.com/Muregis/Livestock-Management-App) — AgriTech Operations MVP
> *Field operations software for animal health records, breeding cycles, milk production tracking, and feed inventory.*

[![Live Demo](https://img.shields.io/badge/🟢_Live_Demo-livestock--app.vercel.app-10b981?style=flat-square)](https://livestock-management-app.vercel.app)
[![Source Code](https://img.shields.io/badge/📦_GitHub-Muregis%2FLivestock--Management-1e293b?style=flat-square&logo=github)](https://github.com/Muregis/Livestock-Management-App)
[![Case Study](https://img.shields.io/badge/📖_Case_Study-Review-0ea5e9?style=flat-square)](https://personal-portfolio-ochre-seven-62.vercel.app/projects/livestock-management)

* **Stack:** `TypeScript` · `React` · `Node.js` · `Relational DB` · `Tailwind CSS`

---

## 🛠️ The Developer Toolkit

<p>
  <b>Languages & Core:</b><br/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/PHP_8+-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP 8+" />
  <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL" />
</p>

<p>
  <b>Frontend Engineering:</b><br/>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
</p>

<p>
  <b>Backend & Queues:</b><br/>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/BullMQ-E0234E?style=flat-square&logo=bullmq&logoColor=white" alt="BullMQ" />
</p>

<p>
  <b>Databases & Infrastructure:</b><br/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions" />
</p>

---

## 🎯 Systems & Verification Matrix

| Product | Operational Impact | Architecture Highlights | Working Evidence |
| :--- | :--- | :--- | :--- |
| **EduCore** | School operations, fee reconciliation, CBC cards | Multi-Tenant `school_id`, 5-tier RBAC, Supabase Postgres | [🟢 Live Demo](https://educore-school-management-system-pi.vercel.app) · [📦 Repo](https://github.com/Muregis/educore-school-management-system) · [📖 Docs](https://personal-portfolio-ochre-seven-62.vercel.app/projects/educore) |
| **Core CRM** | Sales pipelines, KDPA compliance, async queues | AES-256 Vault, BullMQ fair queueing, Token Blocklist | [📦 Repo](https://github.com/Muregis/Core-Crm-model) · [📖 Docs](https://personal-portfolio-ochre-seven-62.vercel.app/projects/core-crm) · 47 Tests Passed |
| **EduCore Ratiba** | Collision-free timetable scheduling engine | PHP 8, FET Solver (`proc_open`), Pre-flight validator | [🟢 Live Demo](https://educoreratiba.vercel.app) · [📦 Repo](https://github.com/Muregis/Educore-Ratiba) · [📖 Docs](https://personal-portfolio-ochre-seven-62.vercel.app/projects/educore-ratiba) |
| **Livestock Platform** | Farm records, breeding cycles & milk yield logs | TypeScript, React, Node.js, Relational DB | [🟢 Live Demo](https://livestock-management-app.vercel.app) · [📦 Repo](https://github.com/Muregis/Livestock-Management-App) · [📖 Docs](https://personal-portfolio-ochre-seven-62.vercel.app/projects/livestock-management) |

---

## 💡 Engineering Philosophy

> *"Software built for the African market cannot assume permanent 5G connectivity or unlimited cloud budgets. It must be resilient to intermittent mobile networks, enforce strict tenant isolation at the database level, handle payment webhook retries idempotently, and deliver sub-second performance on everyday hardware. That is the standard I build to."*

---

## 🤝 Let's Build Together

I am actively open to **Full-Stack Software Engineering**, **Backend Systems Engineering**, and **Product Engineering** roles — particularly teams building high-impact SaaS, EdTech, AgriTech, or African fintech platforms.

* 🌐 **Interactive Portfolio:** [personal-portfolio-ochre-seven-62.vercel.app](https://personal-portfolio-ochre-seven-62.vercel.app)
* 📬 **Email:** [i.am.muregi@gmail.com](mailto:i.am.muregi@gmail.com)
* 💼 **LinkedIn:** [linkedin.com/in/victor-muregi](https://www.linkedin.com/in/victor-muregi)
* 🐙 **GitHub:** [@Muregis](https://github.com/Muregis)
