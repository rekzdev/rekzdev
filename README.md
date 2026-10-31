# 👋 Hi, I'm RekzDev
### Data Systems, Automation & Analytics  —  RainWzd Design · REKZ DEV ☁️

> I build infrastructure that turns operational data into decisions —
> across aviation operations, utility systems, geospatial pipelines, and edge-deployed analytics.
>
> 15 years designing irrigation and water conservation systems taught me how physical infrastructure
> actually runs. Now I build the data systems behind it.

**Open to roles** - data engineering, cloud/infra, analytics infrastructure, automation systems, or geospatial work

<sub>Particularly interested in aviation, utilities, and infrastructure-heavy environments</sub>

🌐 [rekz.dev](https://rekz.dev) · 📬 contact@rekz.dev

---

### ✈️ FlightSignal — Aviation Operations Intelligence

FlightSignal is my aviation data platform: airline waivers, FAA status, cancellations, delays, and
operational history, all in one place. Everything below runs on shared infrastructure with
separate dev and prod environments end to end.

- **Travel Waivers — Live Reddit App** 🟢 *Public*
  A Devvit app live in [r/unitedairlines](https://www.reddit.com/r/unitedairlines/) that surfaces active
  airline travel waivers in real time. Backed by NLP waiver classification, dynamic airport mapping,
  and change tracking. United today, more carriers planned.
  `Devvit` `TypeScript` `Hono` `Cloudflare Workers` `Hyperdrive` `PostgreSQL 17` `n8n` `Mapbox`

- **Waiver History Pages**
  A history page per waiver: waiver details, affected-airport map, FAA info, cancellations, delays,
  and operational history for the waiver window.
  `Astro` `Cloudflare` `D1` `R2` `Mapbox GL JS`

- **TSA & Airport Ground Operations Analytics**
  Real-time checkpoint wait-time ingestion with 10-minute polling, a Workers + Hyperdrive data layer,
  and a dashboard with per-terminal callouts.
  `Next.js` `Cloudflare Pages` `Cloudflare Workers` `Hyperdrive` `PostgreSQL` `n8n` `ECharts`

- **OTP Flight Performance Dashboard**
  TimescaleDB + Dash app analyzing 54M+ flight records for route-level delay insights and airline KPIs.
  `Python` `TimescaleDB` `Dash` `Plotly`

---

### 💧 Utility & Infrastructure Systems

- **Utility Billing Automation & ML Anomaly Detection**
  End-to-end billing pipeline on Azure with AMI data ingest, occupancy sync, and fiscal rate management
  across 1,000+ metered endpoints. Layered anomaly detection (Prophet + Isolation Forest + XGBoost)
  with domain-specific seasonality, predictive maintenance scoring, multi-window degradation analysis
  (5 → 365-day), and maintenance ROI quantification.
  `Python` `Azure SQL` `ADF` `PowerShell` `Prophet` `XGBoost` `scikit-learn`

- **Smart Water Metering — DoD**
  ~1,000-meter metering deployment (public-private partnership) with LoRaWAN irrigation control and
  GIS asset mapping.
  `LoRaWAN` `ArcGIS` `Python`

- **GIS & Spatial Data Systems**
  Infrastructure mapping, spatial analysis, and data integration for government and utility clients,
  with web map delivery via Mapbox GL JS.
  `ArcGIS` `QGIS` `Mapbox` `Python`

<sub>Most repositories are private due to data sensitivity and client ownership. Live products are linked above.</sub>

---

### ⚙️ Tech Stack

<p align="center"><sub>Primary stack I build and deploy with</sub></p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,ts,js,powershell,postgres,redis,fastapi,nextjs,astro,tailwind&theme=dark&perline=10" />
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=cloudflare,azure,aws,docker,github,figma,autocad&theme=dark&perline=10" />
</p>

**Languages:** Python · SQL · TypeScript / JavaScript · PowerShell

**Databases:** PostgreSQL 17 · TimescaleDB · Cloudflare D1 · Azure SQL

**Cloud & Edge:** Cloudflare Workers · Pages · Hyperdrive · D1 · R2 · Azure

**APIs & Frameworks:** Hono · Astro · Next.js · FastAPI · Devvit · TanStack Query

**Automation & Ops:** n8n · Docker · Portainer · Caddy · Playwright · Redis

**ML & Analytics:** Prophet · XGBoost · scikit-learn · Pandas · NumPy

**Visualization & BI:** Apache ECharts · Plotly / Dash · Power BI

**Geospatial:** ArcGIS · QGIS · Mapbox GL JS

---

### 🛠️ How I Ship

- **Dev/prod parity** - separate environments end to end: Hyperdrive configs, Hono gateways, n8n workflows, and test communities, with promotion tracking between them
- **Disciplined migrations** - shared numbering registry, local Docker validation, manual apply, SHA-verified records
- **Backlog-driven** - work tracked in Linear across a multi-repo platform
- **Self-hosted where it counts** - Postgres, n8n, and Portainer on my own VPS; edge delivery on Cloudflare

> "Automate everything. Audit nothing manually twice."

---

### 🧭 Now

- Expanding **Travel Waivers** beyond United to additional carriers
- Building out **FlightSignal** waiver history pages, including FAA SWIM data display
- Running **TSA Wait Times** with live checkpoint data on Cloudflare edge
- Rebuilding **OTP Dash** with improved KPI layout and route-level readability
- Deploying an **ET modeling pipeline** with Open-Meteo + NASA POWER integration
- **Actively exploring new roles** in data engineering, automation, or geospatial systems

---

### 🎖️ Credentials

**Water & Infrastructure**

![CIC](https://img.shields.io/badge/CIC-Certified_Irrigation_Contractor-0052CC?style=flat-square)
![EPA-WSP](https://img.shields.io/badge/EPA--WSP-WaterSense_Partner-0052CC?style=flat-square)
![HPT](https://img.shields.io/badge/HPT-Certified-0052CC?style=flat-square)

**AI Engineering & Agents**

- **Anthropic** - [Model Context Protocol: Advanced Topics](https://academy.claude.com/verify/29bdd2bcb1d4e90d86aff537063823f4) · [Building with the Claude API](https://academy.claude.com/verify/f74fccbbf97a5fc32e12c7fba680b500) · [Claude Code in Action](https://academy.claude.com/verify/9be0039d3f0c85ada0592250c647ab6f) · [Claude with Amazon Bedrock](https://academy.claude.com/verify/029250310131cde529f3c3d64dc237ae) · [Claude on Google Cloud](https://academy.claude.com/verify/7e2aab2817359c522afe99a08b928656) · Introduction to Subagents · Introduction to Agent Skills
- **OpenAI Academy** - [Agents and Workflows](https://www.credential.net/a1fde4bd-315b-4ca8-a811-4aa382a584cb#acc.qZrTQ7nv) · [Optimize AI Application Performance](https://oaiacademy.credential.net/f60d48ac-f5d8-4c0c-867a-68f979307af3#acc.s8z6wpZi) · [Applied AI Foundations](https://oaiacademy.credential.net/a4db1058-6318-4500-8e50-e5d4c1a97677#acc.Kl23B7q5) · [Apply AI at Work Pathway](https://oaiacademy.credential.net/ba88c9d6-d338-4310-9a0f-73cea8bcef14#acc.o60uVlAe)
- **Hugging Face** - MCP Course (Unit 1) · AI Agents Course (Unit 1) · LLM Course (Chapter 3)
- **Databricks** - Generative AI Fundamentals Accreditation

<details>
<summary>Additional coursework</summary>

- **Anthropic** - Building Effective Human-Agent Teams · Deploying Claude Enterprise with Confidence · AI Capabilities and Limitations · Introduction to MCP · Claude Platform 101 · Claude Code 101 · Claude 101 · AI Fluency: Framework and Foundations · AI Fluency for Builders · AI Fluency for Small Businesses · AI Fluency pK-12 Train the Trainer
- **OpenAI Academy** - Scope AI Solutions · AI Leadership · AI Foundations
- **Google Cloud** - Introduction to Generative AI · Introduction to Large Language Models · Innovating with Google Cloud AI · Responsible AI: Applying AI Principles · Security in the World of AI

</details>

---

*Last updated:* <!--LAST_UPDATED-->October 31, 2026 • 02:10 PM CDT<!--/LAST_UPDATED-->

<p align="center">
  <sub>RainWzd Design LLC / REKZ DEV · Data Systems, Automation & Analytics · © 2026</sub>
</p>
