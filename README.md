# Awesome-Cross-App-Contextual-Revenue-Operations

# Top Cross-App Contextual Revenue Operations Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Revenue Intelligence, Pipeline Insights & Cross-Application Data Unification*
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cross-App Contextual Revenue Operations**. These tools unify data across CRM, billing, and internal systems—surfacing pipeline insights, detecting buying signals, and orchestrating revenue workflows across HubSpot, Stripe, and fragmented internal data.

**Examples** include Clari, Gong, BoostUp, People.ai (Backstory), Aviso, RevOps, Syncari, LeanData, Fullcast, and MonetizeNow (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, revenue intelligence, and open RevOps infrastructure—ideal for revenue operations teams, data engineers, and developers seeking transparent, vendor-independent revenue orchestration.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Clari](https://www.clari.com/)**
  Revenue operations platform with pipeline inspection, forecasting, and revenue intelligence. Features AI-powered deal scoring, risk detection, and forecast accuracy.

- **[Gong](https://www.gong.io/)**
  Revenue intelligence platform capturing customer interactions across email, meetings, and calls. Maps activity to opportunities for pipeline insights and coaching.

- **[BoostUp](https://boostup.ai/)**
  Revenue operations and forecasting platform with pipeline inspection, deal scoring, and revenue intelligence.

- **[Backstory (formerly People.ai)](https://backstory.ai/)**
  Rebranded April 2026. AI revenue intelligence platform automatically capturing customer interactions across email, meetings, calls, chat, and CRM records. Maps activity to opportunities for revenue teams .

- **[Aviso](https://aviso.com/)**
  AI-powered revenue operations platform with forecasting, pipeline management, and deal risk detection.

- **[Syncari](https://syncari.com/)**
  Data unification platform for RevOps. Syncs and normalizes data across CRM, marketing, billing, and support systems.

- **[LeanData](https://www.leandata.com/)**
  Revenue orchestration platform on Salesforce. Invented lead-to-account matching and routing. Features Orchestration (routing, deduplication, SLAs), BookIt (scheduling), Buying Groups (multi-stakeholder pipeline), and Revenue Insights (analytics). APIs include Matching, Round Robin, BookIt, and Graph .

- **[Fullcast](https://www.fullcast.com/)**
  GTM planning and operations platform with territory design, quota management, and revenue operations.

- **[MonetizeNow](https://www.monetizenow.com/)**
  Revenue operations platform for quote-to-cash. Features CPQ, billing, and subscription management.

- **[RevOps](https://revops.io/)**
  Revenue operations platform providing pipeline visibility, forecasting, and CRM data hygiene.

## Open-Source GitHub Projects

- **[RevenueOS](https://github.com/unempyd/revenueos)**
  Self-hosted revenue operations platform (MIT). Connects to your website, ad exports, lead lists, mailbox, and open web—then turns findings into a short list of **approvable actions**. Workers never send, publish, or spend without approval. Features **Discover → Approve → Execute → Measure** workflow. Workers include seo, ads-audit, discover, outreach, inbox, content, monitor, growth, heartbeat, and measure. Integrations span website crawl, Hacker News, ad-platform exports, lead-list CSVs, SMTP/IMAP mailboxes, and 64 connector CLIs (analytics, CRM, email, SEO, ads, enrichment). Python 3.12+ with optional Anthropic API key; deterministic checks run without LLM .

- **[revenue-ops-ai-assistant](https://github.com/mizcausevic-dev/revenue-ops-ai-assistant)**
  AI-enabled GTM operations backend (open-source). Combines PostgreSQL-backed SaaS modeling, OpenAI-assisted operator summaries, and production-minded API structure. Focused on **decision support for revenue teams**—grounded in structured systems of record, not generic chat over data. API-first so the AI layer remains inspectable and replaceable. Targets RevOps, SaaS operators, and AI product teams .

- **[Revenue Intelligence (open-source)](https://github.com/topics/revenue-intelligence)**
  Community project detecting buying signals from **PostHog + CRM data** and routing warmest leads to sales. Self-hostable. Positioned as open-source alternative to Pocus and Common Room. 65+ repositories matching the revenue-intelligence topic on GitHub .

- **[Vesh Agents](https://github.com/topics/revenue-intelligence)**
  Open-source agentic AI for revenue intelligence. Six specialized agents (extract, resolve, compute, detect, explain) with BYOM via LiteLLM. CLI + MCP server. Installable via `pip install vesh-agents` .

- **[Lago](https://github.com/getlago/lago)**
  Open-source metering, billing, and revenue infrastructure (AGPL-3.0). Payment-agnostic (Stripe, Adyen, GoCardless). Features usage metering, billing/invoicing, entitlements, cash collection, revenue analytics, and **Lago AI with MCP server**. Integrations include NetSuite, Xero, Salesforce, HubSpot, Avalara. Self-host via Docker Compose. SOC 2 Type II certified .

- **[Meteroid](https://github.com/meteroid-oss/meteroid)**
  Open-source pricing and billing infrastructure (AGPL-3.0, Rust). Subscription management, invoicing, usage-based billing, cost limiting, grandfathering, experiments, **revenue analytics**, and **quotes (CPQ)**. Once a quote is signed, subscription is created and billing starts automatically. 1,089 GitHub stars .

- **[OpenBRMS](https://github.com/openbrms/openbrms)**
  Open-source Business Rules Management System (Java). Abstracts business logic (rules, policies) from application core. Dynamic sandboxed expressions via Tweakflow. REST API with Quarkus. Docker Compose deployment. Relevant for revenue rules orchestration .

### Additional Strong Open-Source Options

- **[Revenue Recognition (Odoo OCA)](https://github.com/open-synergy/ssi-revenue-recognition)** — Odoo addons for revenue recognition (AGPL-3.0). Performance obligations, quality control integration, project integration, and work log integration. Part of Odoo Community Association ecosystem .
- **[eRev](https://github.com/ChipmunkRPA/eRev)** — Pure Python revenue recognition system (lightweight, SQLite-backed). Handles ASC 606 & IFRS 15. Windows EFS encryption. Integrates with PowerBI, Tableau, Alteryx .
- **[revenue-recognition (ASP.NET)](https://github.com/antonio-backnotfront/revenue-recognition)** — REST API handling upfront payments and revenue recognition over time per contract terms. Transparent, auditable financial tracking .
- Community **n8n** workflows for revenue data sync and pipeline alert automation.

**Frameworks for building custom systems**: Combine **RevenueOS** for self-hosted revenue operations workflow with **revenue-ops-ai-assistant** for AI-assisted operator summaries, **Lago** or **Meteroid** for billing/revenue infrastructure, **OpenBRMS** for business rules orchestration, and **PostgreSQL** for persistence—creating a fully self-hosted, enterprise-grade cross-app RevOps platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Cross-app revenue operations platforms handling pipeline, billing, and customer data must comply with data protection regulations (GDPR, CCPA, etc.) and financial controls.
- **Open-source RevOps is emerging, not mature.** RevenueOS provides a self-hosted revenue workflow with approval gates . revenue-ops-ai-assistant provides AI-assisted decision support grounded in structured data . The revenue-intelligence community projects provide buying signal detection . **No single open-source tool provides the end-to-end pipeline inspection, forecasting, and revenue intelligence of Clari or Gong.** Integration work is required.
- **Approval gates are essential for autonomous revenue actions.** RevenueOS workers "never send, publish or spend" without explicit approval . This pattern prevents runaway automation in revenue-critical workflows.
- **Billing infrastructure is the mature open-source layer.** Lago and Meteroid handle metering, invoicing, subscriptions, and revenue analytics with production-grade reliability . These can serve as the billing backbone for cross-app RevOps.
- **Business rules orchestration requires separation.** OpenBRMS abstracts rules from application logic, enabling dynamic policy changes without code deployment . Critical for revenue workflows that need approval thresholds, routing logic, and compliance rules.
- Self-hosted open-source solutions require proper security hardening, payment processor configuration, and ongoing maintenance. Revenue data is financially sensitive—access controls and audit trails are essential.

---

**Made for RevOps teams, revenue analysts, and developers building transparent cross-app revenue operations solutions.**
Let's make Cross-App Contextual Revenue Operations more open, data-driven, and unified.
