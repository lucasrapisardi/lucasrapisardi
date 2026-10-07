<div align="center">

# Lucas Rapisardi de Moura

**DevOps & AI Engineer**

São Paulo, Brazil · [lucas.rapisardi@live.com](mailto:lucas.rapisardi@live.com)

[![Website](https://img.shields.io/badge/lucasrapisardimoura.com-BFFF00?style=flat-square&logo=googlechrome&logoColor=black)](https://lucasrapisardimoura.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/lucas-rapisardi-moura)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:lucas.rapisardi@live.com)
![Location](https://img.shields.io/badge/São_Paulo,_BR-grey?style=flat-square&logo=googlemaps&logoColor=white)

</div>

---

I build production-grade AI-powered systems and automation pipelines. My focus is turning manual, repetitive workflows into intelligent, observable, and scalable processes — from infrastructure management at scale to a multi-tenant SaaS I designed, built and run in production.

---

## 💼 Experience

| Period | Role | Company |
|---|---|---|
| Apr 2026 — Present | Support Engineer | **ActiveState** — led the helpdesk migration from Salesforce to Pylon, integrated it with Slack, Salesforce, WhatsApp and Microsoft Teams, and built support processes and SLAs from the ground up |
| Aug 2024 — May 2026 | IT Administrator & AI Automation Specialist | **California Intercontinental University** — N8n pipelines for credential provisioning and compliance tracking, enterprise infrastructure (Windows Server, AD, M365) |
| Apr 2023 — Apr 2026 | DevOps & ITSM Analyst | **Equinix** — Ansible/Puppet automation across 3,000+ hosts, full ITSM lifecycle in ServiceNow, GitLab CI/CD, VMware, Kubernetes |
| Ongoing | Founder & Lead Engineer | **Trinis AI** — see below |

---

## 🚀 Trinis AI — Founder & Lead Engineer · [trinis.ai](https://trinis.ai)

> AI-powered catalog operations SaaS for Shopify stores. It collects a supplier's catalog from a URL, spreadsheet or PDF, rewrites descriptions in the brand's voice, generates images and keeps price, stock and publishing in sync every day. Live in production.

<!-- Optional: add a dashboard screenshot or a GIF of a job running -->
<!-- ![Trinis AI dashboard](./trinis-dashboard.png) -->

| | |
|---|---|
| **Pipeline** | Collect (URL · sheet · PDF) → AI Enrich (GPT · Gemini · Claude) → Image AI → Publish & Sync |
| **Async processing** | Long-running jobs on worker queues with live per-product progress and logs — the API never blocks and one failure doesn't take the job down |
| **AI cost control** | Model choice per task · EAN-based cache skips products that were already enriched |
| **Undo for bulk actions** | Automatic catalog snapshot before every bulk job · one-click revert or per-product diff & restore |
| **Multi-tenant** | Per-account data isolation · encrypted store credentials · multiple stores and teams per account |
| **Shopify app** | OAuth install · embedded in the Shopify admin · mandatory privacy (GDPR) webhooks |
| **Billing** | Stripe subscriptions and add-ons · usage metering with plan limits enforced across the pipeline |
| **Modules** | Scraper & Import · AI Enricher · Image AI & bulk · Blog AI · Sync Engine · Backup |

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)
![Shopify](https://img.shields.io/badge/Shopify-7AB55C?style=flat-square&logo=shopify&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## 🌐 Remote Gateway — Founder & Lead Engineer

> Job board aggregator that scrapes Braintrust's marketplace daily and funnels talent through a referral-monetized pipeline — built entirely in Python with zero database dependencies.

| | |
|---|---|
| **Data Pipeline** | Daily automated scraper → JSON cache → filtered frontend delivery |
| **Monetization** | All job CTAs routed through referral link · services section with tiered BTRST pricing |
| **Frontend** | Bilingual (PT/ES) toggle · keyword + category filters · responsive card grid |
| **Architecture** | Stateless Flask app · file-based job cache · scheduler-driven refresh |

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

---

## 🛍️ Dimora Mediterranea — Founder & Ecommerce Operator

> End-to-end Shopify store with an LLM integration tool (Claude + OpenAI) for automated product descriptions, images and blog content — the real-world testbed that became Trinis AI.

---

## 🛠️ Skills

**AI & Automation**
`LLM Prompt Engineering` `OpenAI API` `Claude API` `Gemini API` `Agent Architecture` `N8n` `Celery Pipelines` `Async Workflows` `Process Mapping`

**Backend & Integration**
`FastAPI` `Flask` `Next.js` `TypeScript` `REST API` `OAuth2` `Webhooks` `PostgreSQL` `Redis` `Shopify API` `Stripe`

**Infrastructure & DevOps**
`Docker` `Kubernetes` `Ansible` `Puppet` `GitLab CI/CD` `VMware vSphere` `Linux` `AWS` `Zabbix` `Prometheus` `Grafana`

**Systems & Identity**
`Windows Server` `Active Directory` `Microsoft 365` `PowerShell` `Bash`

**ITSM & Support Ops**
`ServiceNow` `Pylon` `Salesforce` `ITIL` `Incident / Change / Problem` `CMDB` `CAB` `SLA Design` `Knowledge Base`

---

## 📊 Impact

```
86%  reduction in manual infrastructure operations
     Equinix · Ansible automation across 3,000+ hosts

93%  reduction in average incident response time
     CIU · runbook-driven automated triage

48x  faster full-store product sync
     Trinis AI · full catalog (images, rich description, meta, categorization)
     from ~10 products per day → an entire store live in half a day

4    channels unified into one helpdesk
     ActiveState · Slack, Salesforce, WhatsApp and Microsoft Teams integrated into Pylon
```

---

## 📚 Currently Learning

- DevOps & Architect Specialization — Full Cycle 3.0
- Linux System Administrator & Network Engineer — 4Linux
- Prometheus & Grafana for advanced observability

---

## 🌍 Languages

`Portuguese` Native &nbsp;·&nbsp; `English` C1 Advanced &nbsp;·&nbsp; `Italian` B1

---

<div align="center">

*"A solution that creates a dependency on the person who built it isn't really a solution."*

</div>
