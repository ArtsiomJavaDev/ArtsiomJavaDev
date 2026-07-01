# Hi there, I'm Artsiom 👋

### Middle Fullstack Developer · Integrations & Automation

> I turn messy, manual back-office processes into reliable, production-grade software —
> building the bridges between CRMs, ERPs, banks and the people who use them.

📍 Warsaw, Poland · 💼 Currently at **Freedom Business Area**

---

## 🧠 About Me

- 🔭 **Currently building** ERP integrations (Comarch Optima) that automate invoice transfer and bank payments, plus a secure data API for a CRM serving ~950 clients.
- ⚙️ **I ship end-to-end** — from Spring Boot / Laravel / Python backends and SQL databases to React & React Native front-ends. Recently automated an HR & payroll process, cutting a ~150h/month manual workload down to ~10h and saving ~$30k/year.
- 💪 **I'm strong in** system integrations, REST/API design, business-process automation, and application security (JWT/OAuth2, PII protection, CI/CD).
- 🌱 **I'm learning** Data Science & AI (engineering degree in progress) and lean heavily on AI-assisted development (Cursor) to move fast.

---

## 🛠️ Tech Stack

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-025E8C?style=for-the-badge&logo=postgresql&logoColor=white)

**Frameworks & Libraries**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)

**Tools & DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Architecture & Methodologies**

![REST APIs](https://img.shields.io/badge/REST_APIs-005571?style=for-the-badge)
![System Integration](https://img.shields.io/badge/System_Integration-1F4E79?style=for-the-badge)
![CI/CD](https://img.shields.io/badge/CI%2FCD-3E8E8E?style=for-the-badge)
![Security](https://img.shields.io/badge/Security_(JWT%2FOAuth2)-6E4B9E?style=for-the-badge)
![Agile / Scrum](https://img.shields.io/badge/Agile_%2F_Scrum-0B7285?style=for-the-badge)
![TDD](https://img.shields.io/badge/TDD-8B2E2E?style=for-the-badge)

---

## 🚀 Highlighted Projects

⚡ CentralHub — HR & Payroll Automation

Desktop fullstack app bridging an internal CRM and a Polish payroll system. It ingests data from two sources (REST API + MySQL over SSH), validates it against a custom 2026 tax engine (ZUS/PIT/PPK), and imports it in one click.


Impact: cut a ~150h/month manual process down to ~10h of verification · ~$30k/year saved
Stack: Python PyQt6 MS SQL Server MySQL AWS RDS REST API · 216 pytest golden-case tests, CI on GitHub Actions
🔒 Commercial project — source private under NDA


🔗 CRM — Accounting & Payroll Platform (Comarch Optima integration)

Team project: a multitenant CRM for an accounting, payroll & legalization business serving ~950 clients across 15 account managers. I own the secure integration layer and API.


What I built: a hardened read-only Data API (16+ entities) with defense-in-depth security (IP-whitelist → Bearer token → rate limiting) and transparent PII decryption; currently building a Comarch Optima ERP integration that automates invoice transfer and triggers automatic bank payments.
Stack: PHP Laravel 10 REST API Eloquent MySQL AWS S3 · code review + Jira
🔒 Commercial project — source private under NDA


📚 Education Content Platform — catalog with AI moderation

Fullstack platform with a public searchable catalog and gated, secure downloads, plus an AI pipeline that auto-moderates imported PDFs before publication.


Highlights: cost-aware AI classification (heuristics → LLM with JSON mode), one-time SHA-256 download tokens + MySQL job queue, three-tier RBAC, Partner-API sync, full CI/CD (PHPUnit + E2E, PHPStan level 6)
Stack: PHP 8.2 React 19 TypeScript MySQL Vite Tailwind CSS OpenAI API
🔒 Commercial project — source private under NDA


💱 Crypto Exchange Platform — crypto/FX exchange (web + mobile + backend)

End-to-end pet project: a Spring Boot REST backend (JWT, RBAC, 7-stage order lifecycle), a React/TypeScript web client and an Expo mobile app, wired to 4 external APIs with graceful fallback.


Highlights: real-time rates & charts, offline-capable mobile app (i18n EN/PL/RU), unified Redux Toolkit state, Docker Compose
Stack: Java 21 Spring Boot PostgreSQL React TypeScript React Native (Expo) Docker
🔗 Repository https://github.com/ArtsiomDziainekaDev/cryptoexchange

---


## 🤝 Connect with me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/artsiom-dziaineka-2b811829a)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:bden5353@gmail.com)
[![Telegram](https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/artsiomdev)

