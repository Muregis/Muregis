<div align="center">

# Victor Muregi

**Full-Stack Software Engineer · Founder, MuregiScore Technologies · Nairobi, Kenya**

Building dependable, production-oriented business systems, multi-tenant SaaS platforms, and payment integrations.

[![Portfolio](https://img.shields.io/badge/Portfolio-Live_Site-0ea5e9?style=flat-square&logo=vercel)](https://personal-portfolio-ochre-seven-62.vercel.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Victor_Muregi-0284c7?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/victor-muregi)
[![Email](https://img.shields.io/badge/Email-i.am.muregi%40gmail.com-059669?style=flat-square&logo=gmail)](mailto:i.am.muregi@gmail.com)
[![Focus](https://img.shields.io/badge/Focus-Production_Business_Systems-6366f1?style=flat-square)](https://personal-portfolio-ochre-seven-62.vercel.app)
[![Location](https://img.shields.io/badge/Location-Nairobi%2C_Kenya-64748b?style=flat-square)](https://github.com/Muregis)

</div>

---

## ⚡ Executive Summary (15-Second Overview)

* **Who I am:** Full-stack engineer and founder of **MuregiScore Technologies** in Nairobi, Kenya. Background in Computer Science (Diploma Level 6, Kiambu National Polytechnic).
* **What I build:** Production-grade business systems that replace error-prone manual workflows and fragmented spreadsheets with auditable, resilient software.
* **Core specialties:** Multi-tenant SaaS architectures, strict role-based access control (RBAC), Safaricom M-Pesa Daraja payment workflows, asynchronous job queues, and offline-tolerant institutional platforms.
* **Flagship systems:** **EduCore** (School Operations SaaS), **Core CRM** (Multi-Tenant Sales & KDPA CRM), and **EduCore Ratiba** (Automated Timetabling Engine).

---

## 🚀 Flagship Production Systems

### 1. [EduCore](https://github.com/Muregis/educore-school-management-system) — Multi-Tenant School Management SaaS
> Comprehensive academic administration and fee management platform engineered for Kenyan primary and secondary schools.

* **The Problem:** Schools struggle with paper ledgers, delayed fee reconciliation, fragmented student records, and error-prone term report compilation across multiple campuses.
* **Architecture & Highlights:**
  * Strict multi-tenant data isolation keyed by `school_id` with 5-tier RBAC (Admin, Principal, Teacher, Bursar, Student).
  * Idempotent Safaricom M-Pesa Daraja and Paystack payment processing with automated ledger reconciliation.
  * Automated CBC (Competency-Based Curriculum) and term report card generation.
* **Stack:** React, Vite, Node.js, Express REST API, Supabase (PostgreSQL & Storage), Tailwind CSS.
* **Evidence:** [Live Demo](https://educore-school-management-system-pi.vercel.app) · [Repository](https://github.com/Muregis/educore-school-management-system) · [Technical Case Study](https://personal-portfolio-ochre-seven-62.vercel.app/projects/educore)

---

### 2. [Core CRM](https://github.com/Muregis/Core-Crm-model) — Multi-Tenant Sales & Compliance CRM
> Enterprise customer relationship and sales pipeline platform designed for Kenyan SMEs, SACCOs, and growing commercial teams.

* **The Problem:** Growing businesses lose leads and customer history when commercial deals are scattered across personal WhatsApp threads, spreadsheets, and unmonitored notebooks.
* **Architecture & Highlights:**
  * Self-service tenant provisioning with dynamic subdomain and header resolution.
  * Multi-tenant M-Pesa Daraja payment rail with AES-256-GCM encrypted credential vault.
  * BullMQ & Redis asynchronous worker pipeline with tenant grouping to eliminate noisy-neighbor bottlenecks.
  * Token revocation blocklist and rotating refresh tokens on session invalidation.
  * Kenya Data Protection Act (KDPA 2019) compliance: automated telephone/PII redaction in logs, Section 26 data exports, and audit-safe anonymization.
  * **Verified Quality:** 47 / 47 passing tests across 6 automated suites in Jest and Supertest.
* **Stack:** React, Vite, Node.js, Express, MySQL / PostgreSQL, Redis, BullMQ, Tailwind CSS.
* **Evidence:** [Repository](https://github.com/Muregis/Core-Crm-model) · [Technical Case Study](https://personal-portfolio-ochre-seven-62.vercel.app/projects/core-crm)

---

### 3. [EduCore Ratiba](https://github.com/Muregis/Educore-Ratiba) — Automated Timetabling & Constraint Engine
> Combinatorial timetable scheduling engine built for Kenyan educational institutions managing complex KICD curriculum requirements.

* **The Problem:** Term timetabling manually takes days of administrator effort and frequently results in teacher double-booking, room clashes, and laboratory conflicts.
* **Architecture & Highlights:**
  * Integrates the open-source FET timetabling solver via safe process execution (`proc_open`) and XML serialization.
  * Multi-school isolation supporting both CBC and 8-4-4 curriculum structures.
  * Pure-PHP pre-flight workload validation preventing invalid state execution before solver dispatch.
  * Post-generation live clash detection engine for interactive adjustments.
  * Offline-capable and local-install ready for rural and sub-county schools with erratic internet access.
* **Stack:** PHP 8+, FET Constraint Solver Engine, MySQL / PostgreSQL, Dompdf.
* **Evidence:** [Live Demo](https://educoreratiba.vercel.app) · [Repository](https://github.com/Muregis/Educore-Ratiba) · [Technical Case Study](https://personal-portfolio-ochre-seven-62.vercel.app/projects/educore-ratiba)

---

### 4. [Livestock Management Platform](https://github.com/Muregis/Livestock-Management-App) — AgriTech Operations MVP
> Domain-specific software for animal health tracking, breeding cycles, milk yield logging, and farm feed inventory.

* **Stack:** TypeScript, React, Node.js, Relational Database, Tailwind CSS.
* **Evidence:** [Live Demo](https://livestock-management-app.vercel.app) · [Repository](https://github.com/Muregis/Livestock-Management-App) · [Technical Case Study](https://personal-portfolio-ochre-seven-62.vercel.app/projects/livestock-management)

---

## 📊 Systems & Evidence Matrix

| System | Primary Impact | Architecture & Tech | Verification & Evidence |
| :--- | :--- | :--- | :--- |
| **EduCore** | School ops, fee reconciliation, CBC reports | React, Node/Express, PostgreSQL, M-Pesa | [Live Demo](https://educore-school-management-system-pi.vercel.app) · [Repo](https://github.com/Muregis/educore-school-management-system) · [Case Study](https://personal-portfolio-ochre-seven-62.vercel.app/projects/educore) |
| **Core CRM** | Sales pipeline, KDPA compliance, async queues | Node/Express, React, MySQL, Redis, BullMQ | [Repository](https://github.com/Muregis/Core-Crm-model) · [Case Study](https://personal-portfolio-ochre-seven-62.vercel.app/projects/core-crm) · 47 Tests Passing |
| **EduCore Ratiba** | Collision-free timetable scheduling engine | PHP 8, FET Solver, MySQL/Postgres, Dompdf | [Live Demo](https://educoreratiba.vercel.app) · [Repo](https://github.com/Muregis/Educore-Ratiba) · [Case Study](https://personal-portfolio-ochre-seven-62.vercel.app/projects/educore-ratiba) |
| **Livestock Platform** | Farm records, milk yields & animal health logs | TypeScript, React, Node.js, Relational DB | [Live Demo](https://livestock-management-app.vercel.app) · [Repo](https://github.com/Muregis/Livestock-Management-App) · [Case Study](https://personal-portfolio-ochre-seven-62.vercel.app/projects/livestock-management) |

---

## 🛠️ Verified Technology Stack

```
Frontend Architecture       TypeScript · JavaScript · React · Next.js · Vite · Tailwind CSS
Backend & APIs              Node.js · Express · PHP 8+ · RESTful APIs · Modular Routing
Databases & Storage         PostgreSQL (Supabase) · MySQL · 3NF Normalization · ACID Transactions
Payments & Integrations     Safaricom M-Pesa Daraja (STK Push, C2B, Webhooks) · Paystack
Asynchronous & Background   Redis · BullMQ Queues · FET Constraint Engine · Idempotent Workers
Security & Authorization    Multi-Tenant RBAC · AES-256-GCM Vaults · Token Revocation Blocklists · Bcrypt
DevOps & Tooling            Docker · Git · GitHub Actions CI · Linux · Vercel · Render
```

---

## 💼 Professional Focus & Contact

I am open to **full-stack software engineering**, **backend engineering**, and **product engineering** opportunities — particularly across SaaS, EdTech, AgriTech, and African fintech/commercial systems.

* **Portfolio:** [personal-portfolio-ochre-seven-62.vercel.app](https://personal-portfolio-ochre-seven-62.vercel.app)
* **Email:** [i.am.muregi@gmail.com](mailto:i.am.muregi@gmail.com)
* **LinkedIn:** [linkedin.com/in/victor-muregi](https://www.linkedin.com/in/victor-muregi)
* **GitHub:** [@Muregis](https://github.com/Muregis)
