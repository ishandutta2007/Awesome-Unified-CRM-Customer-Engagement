# Awesome-Unified-CRM-Customer-Engagement

# Awesome Unified CRM & Customer Engagement

> A curated list of top Unified CRM and Customer Engagement platforms — both SaaS/Hosted commercial solutions and open-source alternatives for managing sales pipelines, marketing automation, and customer relationships on a single platform.  
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Salesforce Customer 360](#salesforce-customer-360)
  - [HubSpot CRM Suite](#hubspot-crm-suite)
  - [Microsoft Dynamics 365](#microsoft-dynamics-365)
  - [Zoho One](#zoho-one)
  - [Freshsales Suite](#freshsales-suite)
  - [ActiveCampaign](#activecampaign)
  - [Keap](#keap)
  - [SugarCRM](#sugarcrm)
  - [Bitrix24](#bitrix24)
  - [GoHighLevel](#gohighlevel)
- [Open-Source Software](#-open-source-software)
  - [Twenty](#twenty)
  - [EspoCRM](#espocrm)
  - [BottleCRM](#bottlecrm)
  - [Krayin](#krayin)
  - [Frappe CRM](#frappe-crm)
  - [SuiteCRM](#suitecrm)
  - [Helio](#helio)
  - [Mautic](#mautic)
  - [Corteza](#corteza)
  - [Dolibarr](#dolibarr)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Unified CRM and Customer Engagement platforms. These are not open-source but are included as reference points for feature comparison.

### Salesforce Customer 360
**Type:** Enterprise CRM with Agentforce AI  
Salesforce is the long-standing enterprise CRM leader, connecting sales, service, marketing, and commerce on a single platform. Its metadata-driven architecture and Einstein/Agentforce AI capabilities are frequently cited as strengths, though cost transparency and platform complexity are noted trade-offs for growing teams.

### HubSpot CRM Suite
**Type:** Integrated CRM, marketing, sales, and service  
HubSpot offers a free CRM tier with contact management, deal tracking, and Breeze AI assistance. Paid Hubs (Sales, Marketing, Service) scale per seat, with Professional and Enterprise tiers unlocking automation, custom reporting, and advanced permissions. Known for its polish and integration depth, though costs escalate significantly at higher tiers.

### Microsoft Dynamics 365
**Type:** Enterprise CRM within Microsoft ecosystem  
Dynamics 365 Sales provides core sales management, reporting, and dashboards, with connections to Microsoft 365 (Outlook, Teams) for familiar workflows. Enterprise tiers add forecasting, territory management, and Copilot AI. Best suited for organizations already standardized on Microsoft.

### Zoho One
**Type:** Unified business operating system  
Zoho One bundles 45+ integrated applications including Zoho CRM, Desk, Campaigns, and Analytics for a flat per-employee price. Zoho CRM itself offers a free edition for 3 users, with paid tiers adding scoring rules, forecasting, and Blueprint process design. Strong value for SMBs wanting breadth without multiple vendor relationships.

### Freshsales Suite
**Type:** Unified CRM across sales, marketing, and support  
Freshworks offers Freshsales (CRM), Freshmarketer, and Freshdesk (support) as an integrated suite. The platform emphasizes ease of use and AI assistance (Freddy AI) for lead scoring and revenue forecasting. Positioned as an accessible alternative to enterprise suites for mid-market organizations.

### ActiveCampaign
**Type:** Marketing automation with integrated CRM  
ActiveCampaign combines email marketing, marketing automation, and a lightweight CRM. Pricing starts at $15/month for Starter with multi-step automation and 250+ email templates. Plus ($49/month) adds conditional content and attribution tracking. Pro ($79/month) adds predictive sending and advanced segmentation. Known for automation depth relative to price, though the CRM is less robust than dedicated sales platforms.

### Keap
**Type:** CRM and automation for small businesses  
Keap (formerly Infusionsoft) provides CRM, sales automation, and marketing automation targeted at small businesses and service providers. Features include contact management, pipeline tracking, email campaigns, and appointment scheduling. Positioned for businesses wanting an all-in-one system without enterprise complexity.

### SugarCRM
**Type:** CRM platform with open-source heritage  
SugarCRM provides sales automation, marketing automation, and customer service with a focus on flexibility and customization. The platform has a long history in the CRM market, with both cloud and on-premises deployment options for enterprise customers requiring data control.

### Bitrix24
**Type:** Unified collaboration and CRM platform  
Bitrix24 combines CRM with team collaboration tools (chat, video, tasks, Drive) in a single platform. The free tier is notably generous, including unlimited deals and invoices, 5 GB storage, and CoPilot AI. Suited for small teams wanting CRM bundled with communication and project tools.

### GoHighLevel
**Type:** All-in-one agency CRM with funnels and automation  
GoHighLevel (GHL) starts at $97/month for the Starter plan with unlimited communities and members, full CRM with pipelines, email/SMS automation, funnels, landing pages, appointment booking, and course hosting. The Unlimited plan ($297/month) removes limits. A key differentiator is white-label reselling for agencies. SMS and email delivery are billed separately through Twilio and Mailgun.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Unified CRM and Customer Engagement tools. The open-source ecosystem spans **modern developer-friendly CRMs**, **established enterprise platforms**, **marketing automation engines**, and **growth platforms combining CRM with journeys**.

### Twenty
**Stack:** TypeScript / NestJS / React / PostgreSQL | **License:** AGPL-3.0 (core)  
Twenty is widely positioned as the leading modern open-source alternative to Salesforce and HubSpot, with a clean SaaS-like interface and developer-friendly architecture . It supports custom objects, pipelines, workflows, and AI agents, with objects definable as code via the Twenty SDK and versioned like the rest of the stack. REST and GraphQL APIs and webhooks connect it to other tools. Files marked as Enterprise are under a commercial license, while developer packages (SDK) are MIT . Actively maintained with commits in 2026.  
**Best for:** Teams wanting a modern, flexible CRM they can extend as code, with a SaaS-like experience and no per-seat fees.

### EspoCRM
**Stack:** PHP / MySQL/PostgreSQL | **License:** AGPL-3.0  
EspoCRM is a classic, feature-complete CRM covering leads, contacts, opportunities, marketing campaigns, support cases, and a calendar . The Entity Manager adds custom entities, fields, and relationships without code. A REST API connects it to other systems. Reports, workflows, and BPM come with the Advanced Pack, a separately licensed extension. Described as the closest open-source match to Salesforce out of the box, with a clean interface and powerful in-app administration .  
**Best for:** Organizations wanting a proven, feature-rich CRM with strong out-of-the-box administration and a complete API, accepting a large codebase and AGPL licensing.

### BottleCRM
**Stack:** Python / Django REST / SvelteKit / Flutter / PostgreSQL | **License:** MIT  
BottleCRM is a free, open-source, self-hosted, multi-tenant CRM built with Django REST Framework, SvelteKit, and Flutter . It covers leads, accounts, contacts, opportunities, support tickets (with SLA timers, approvals, escalations, macros, and knowledge base), tasks, and invoices. **PostgreSQL Row-Level Security** isolates each organization's data at the database layer, so a single deployment serves one startup or hundreds of tenants. A native Flutter mobile app (iOS + Android) is included — uncommon among open-source CRMs. The REST API is agent-ready (OpenAPI schema, per-user tokens) for AI agents like Claude or Cursor. MIT licensed with no per-seat pricing .  
**Best for:** Teams wanting a genuinely MIT-licensed, multi-tenant CRM with native mobile apps, real support tooling, and AI-agent-ready APIs.

### Krayin
**Stack:** PHP / Laravel | **License:** MIT  
Krayin is a low-code CRM with enterprise-grade features built on Laravel, with 23,900+ GitHub stars and active development . It includes lead and deal pipelines, activity management, email parsing, and a customizable admin panel. The platform explicitly positions itself as an open-source alternative to HubSpot, Keap, and Insightly, with marketing automation (campaigns, email marketing, segmentation), customer support (VoIP, live chat, feedback), and analytics . The MIT license is permissive for commercial modifications.  
**Best for:** Laravel developers and teams wanting a permissively licensed, customizable CRM with broad feature coverage.

### Frappe CRM
**Stack:** Python / Frappe Framework / Vue | **License:** AGPL-3.0  
Frappe CRM is a modern CRM built on the Frappe framework (same ecosystem as ERPNext). It provides lead and deal management, email integration, telephony (Twilio click-to-call, Exotel, WhatsApp), an SLA engine with escalation, Meta lead capture from Facebook/Instagram ads, and a no-code form layout editor . The Frappe ecosystem offers a path to ERPNext for organizations wanting integrated ERP and CRM in one open-source stack. Docker Compose deployment with a single command.  
**Best for:** Teams already in or considering the Frappe/ERPNext ecosystem, wanting CRM integrated with broader business operations.

### SuiteCRM
**Stack:** PHP / MySQL/MariaDB | **License:** AGPL-3.0  
SuiteCRM is the successor to SugarCRM Community Edition, offering enterprise-class CRM with sales automation, marketing automation, workflow, reporting, and a REST API . It has a large user base and rich plugin ecosystem, with a 360-degree customer view. The codebase is older with outdated coding practices and a dated UI, making it less suitable for simple CRM needs or modern development .  
**Best for:** Organizations with existing SuiteCRM expertise or specific legacy requirements, wanting a feature-rich platform despite technical debt.

### Helio
**Stack:** TypeScript / React Flow / Temporal / PostgreSQL / ClickHouse | **License:** AGPL-3.0  
Helio is an open-source, AI-native growth platform that combines a Customer Data Platform (CDP) with visual journey orchestration, marketing automation, and a lightweight CRM . The journey builder uses a React Flow canvas compiled into a validated DAG, with one Temporal workflow per enrolled contact for durable execution. Multi-channel delivery covers email, SMS (Twilio), WhatsApp (Cloud API), web push, and in-app messages. Includes an AI copilot that generates segments, journeys, and on-brand emails from natural language, plus an MCP server for external AI agents. Segmentation uses a visual nested AND/OR builder with always-live membership. CRM-lite features include pipelines with configurable stages, a task list, and a meeting scheduler with public booking pages. **Free forever** — no plans, contact caps, or metering .  
**Best for:** Teams wanting a genuinely self-hosted, AI-native growth platform combining CRM-lite, marketing automation, and multi-channel journeys without vendor lock-in.

### Mautic
**Stack:** PHP / MySQL | **License:** GPL  
Mautic is the world's largest open-source marketing automation project, positioned as a self-hosted alternative to Marketo, HubSpot, and ActiveCampaign . Features include email campaigns, contact segmentation, lead scoring, landing pages, and visual automation workflows. The critical deployment detail: a dedicated cron worker is required for campaigns and scheduled emails to actually fire — the most common failure point in self-hosted Mautic deployments. Self-hosting means unlimited contacts and campaigns at flat infrastructure cost, with full data ownership.  
**Best for:** Marketing teams wanting powerful automation and unlimited contacts without per-contact pricing, accepting the operational overhead of self-hosting.

### Corteza
**Stack:** Go / Vue / PostgreSQL | **License:** Apache-2.0  
Corteza is a low-code platform for building custom CRM and business applications . It provides CRM modules alongside messaging and workflow capabilities. The Apache-2.0 license is permissive. Suited for organizations wanting to build a CRM tailored to specific processes rather than adopting a pre-built one.  
**Best for:** Teams wanting to build a custom CRM on a low-code Apache-licensed platform.

### Dolibarr
**Stack:** PHP / MySQL | **License:** GPL-3.0  
Dolibarr is a modular open-source ERP and CRM for small and medium businesses, originally from France. CRM features include contacts, leads, opportunities, and activity tracking, alongside invoicing, inventory, and HR modules. Highly modular — enable only the features you need. Described as the EU SMB staple for combined ERP and CRM .  
**Best for:** SMBs wanting an all-in-one ERP + CRM in a single self-hosted package.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Marketing Automation | Multi-Tenant | Mobile App | Self-Hosted | Best For |
|----------|---------|-------|----------------------|--------------|------------|-------------|----------|
| **Salesforce** | Proprietary | Cloud | ✅ | ✅ | ✅ | ❌ | Enterprise CRM + AI |
| **HubSpot** | Proprietary | Cloud | ✅ | ✅ | ✅ | ❌ | Polished all-in-one |
| **Microsoft Dynamics** | Proprietary | Cloud | ✅ | ✅ | ✅ | ❌ | Microsoft 365 orgs |
| **Zoho One** | Proprietary | Cloud | ✅ | ✅ | ✅ | ❌ | SMB breadth at flat price |
| **Freshsales Suite** | Proprietary | Cloud | ✅ | ✅ | ✅ | ❌ | Mid-market unified suite |
| **ActiveCampaign** | Proprietary | Cloud | ✅ Deep | ✅ | ✅ | ❌ | Automation depth |
| **GoHighLevel** | Proprietary | Cloud | ✅ | ✅ | ✅ | ❌ | Agency white-label |
| **Twenty** | AGPL-3.0 | TypeScript | (Check) | (Check) | ❌ | ✅ | Modern Salesforce alternative |
| **EspoCRM** | AGPL-3.0 | PHP | ✅ (Advanced Pack) | (Check) | ❌ | ✅ | Feature-complete classic CRM |
| **BottleCRM** | MIT | Django/Flutter | (Check) | ✅ (RLS) | ✅ Flutter | ✅ | MIT + multi-tenant + mobile |
| **Krayin** | MIT | PHP/Laravel | ✅ | (Check) | ❌ | ✅ | Permissive Laravel CRM |
| **Frappe CRM** | AGPL-3.0 | Python/Frappe | (Check) | (Check) | ❌ | ✅ | ERPNext ecosystem |
| **SuiteCRM** | AGPL-3.0 | PHP | ✅ | (Check) | (Limited) | ✅ | Feature-rich legacy |
| **Helio** | AGPL-3.0 | TypeScript | ✅ (Journeys) | ✅ (Workspace) | (PWA) | ✅ | CRM + journeys + AI |
| **Mautic** | GPL | PHP | ✅ Deep | (Check) | ❌ | ✅ | Unlimited contacts + automation |
| **Corteza** | Apache-2.0 | Go/Vue | (Custom) | (Check) | ❌ | ✅ | Custom low-code CRM |
| **Dolibarr** | GPL-3.0 | PHP/MySQL | (Limited) | (Check) | ❌ | ✅ | SMB ERP + CRM |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Unified CRM or Customer Engagement platform that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem **splits** between modern developer-friendly CRMs (Twenty, BottleCRM), established enterprise platforms (EspoCRM, SuiteCRM), ERP-integrated solutions (Frappe CRM, Dolibarr), marketing automation engines (Mautic), and growth platforms combining CRM with journeys (Helio). Twenty and BottleCRM are currently the most notable modern alternatives to Salesforce/HubSpot, with BottleCRM offering the unique combination of MIT licensing, native mobile apps, and database-level multi-tenancy. Helio stands out for teams wanting CRM-lite combined with AI-native marketing automation and multi-channel journeys in one self-hosted platform.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
