# UBEC Dev

Software and data infrastructure for Nigeria's **Universal Basic Education Commission (UBEC)**, built and maintained by the **Department of Data, Digital Platform & Analytics (DDPA)**.

🔗 [ubec.gov.ng](https://ubec.gov.ng)

---

## What this account is for

This is the engineering home for UBEC's digital systems — the tools that collect, move, clean, and report on basic-education data from schools and State Universal Basic Education Boards (SUBEBs) up to UBEC headquarters. Repos here span:

- **Field data collection** — offline-capable mobile data collection (ODK Central-based, and a Flutter/Laravel alternative in development)
- **M&E and reporting systems** — quarterly departmental dashboards for HQ, State Offices, and SUBEBs
- **Legacy platform maintenance** — BEMIS (school-level data management, CodeIgniter 4) covering ECCDE, Primary, and JSS levels
- **Data pipelines** — ETL from ODK Central / OData sources into structured reporting databases
- **Compliance tooling** — NDPA 2023 / GAID 2025 data-protection compliance for UBEC's digital systems
- **Internal utilities** — assessment data consolidation (e.g. the National Learning Assessment), server and platform administration scripts

## Stack

| Area | Tools |
|---|---|
| Data collection | ODK Central (self-hosted), KoBoToolbox |
| Backend | PHP / CodeIgniter 4, Laravel |
| Mobile / offline apps | Flutter |
| Frontend | React, Tailwind CSS |
| Data & reporting | Python (ETL), MySQL, Looker Studio, SPSS |
| Infrastructure | cPanel/WHM, AlmaLinux, Ubuntu, Cloudflare DNS |

## Repositories

_No public repositories yet — this space will fill in as DDPA projects are published or open-sourced._

## Working here

Most of this work supports statutory reporting obligations and serves field conditions with intermittent connectivity, so contributions should keep offline-first design, data governance (NDPA 2023), and low-bandwidth environments in mind.

## Contact

For questions about UBEC's digital platforms, reach DDPA through [ubec.gov.ng](https://ubec.gov.ng).
