# Awesome-B2b-Marketing-Automation

# Awesome-B2b-Lead-Intelligence-Data-Enrichment 🎯 🔍

<p align="center">
  <img src="assets/banner.svg" alt="Awesome B2b Lead Intelligence Data Enrichment Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-B2b-Lead-Intelligence-Data-Enrichment"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-B2b-Lead-Intelligence-Data-Enrichment?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-B2b-Lead-Intelligence-Data-Enrichment/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-B2b-Lead-Intelligence-Data-Enrichment?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-B2b-Lead-Intelligence-Data-Enrichment/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-B2b-Lead-Intelligence-Data-Enrichment?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top B2B Lead Intelligence & Data Enrichment Ecosystem

**Curated List of Commercial Data Platforms & Open-Source Enrichment Engines**  
*Focused on Contact Discovery, Firmographic Enrichment, Email Verification, Intent Signals, Tech Stack Detection & Self-Hosted Data Pipelines*

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary
Welcome to the ultimate curated directory of **B2B lead intelligence and data enrichment platforms**, **open-source enrichment engines**, and **firmographic intelligence tools**. Whether you are looking for enterprise-grade commercial solutions (such as *ZoomInfo*, *Apollo.io*, and *Clearbit*), or self-hostable open-source alternatives (like *FORGE*, *Signal*, and *enrichment-kit*), this list covers category leaders, multi-vendor waterfalls, and privacy-respecting data enrichment.

**Key Market Context:**
- **FORGE** is the **most complete open-source business data enrichment engine** — enriches business databases using **free data sources and local AI** with **no API keys, no accounts, no credit cards**. Scrapes websites, imports government records (FCC ULS, NPI Registry, SAM.gov), verifies emails via SMTP, and optionally generates AI summaries with local Ollama models. Achieves **~16K records/hr with 4 workers** on the web scraping track .
- **enrichment-kit** is the **open-source Clay.com alternative** — **multi-vendor enrichment waterfalls** that order providers by **effective cost (`price / hit_rate`)** and **short-circuit on success**, paying **~$0.004 per verified contact** vs **~$0.12 for Clay**. For a 10k-lead list, cost lands near **$60 instead of $300** .
- **Signal** is the **open-source AI sales intelligence and outreach automation platform** — watches the web for buying signals (hiring changes, funding news, product launches, review shifts), enriches companies and contacts, drafts personalized outreach, and runs multi-step email sequences from a single chat-first workspace. Runs on **your own Supabase + Anthropic keys** .
- **Batuda** is the **open-source CRM with a built-in research agent** — server-side agent loop with a **mandatory citation ledger**, **five typed result schemas** (CompanyEnrichmentV1, CompetitorScanV1, ContactDiscoveryV1, ProspectScanV1, Freeform), and **90+ intent-level typed MCP tools**. Registry-first contact discovery (Companies House UK, libreBORME Spain) with **pattern-guessed emails gated through DNS MX and verifier confirmation** .
- **opengtm** is the **MIT-licensed GTM engine** — **AI-powered lead discovery, 6-dimension ICP scoring, AEO health checks (29 checks), 4-touch outreach sequences, and Claude Code integration**. Runs locally with **Gemini free tier (1,500 requests/day)** .
- **b2b-lead-intelligence** is the **official Python SDK for B2B Lead Intelligence** — the **open-source Apollo & Proxycurl alternative**. Provides `enrich_company()`, `find_executives()`, and `get_hiring_signals()` with firmographics, tech stack, decision-maker emails, and growth-stage scoring .
- **Apollo.io, ZoomInfo, and Clearbit charge $10K–$50K/year** for data that is **largely scraped from public sources** — **FORGE does the same thing for free** .

---

## 📑 Table of Contents
- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS / Commercial Platforms

The B2B lead intelligence and data enrichment market spans **contact data platforms** (ZoomInfo, Apollo.io, Cognism) that provide **verified emails, direct dials, and firmographics**, **enrichment APIs** (Clearbit, Lusha, LeadIQ) that **fill in missing data for existing records**, and **sales intelligence platforms** (People Data Labs, Crunchbase Enterprise) that combine **company data with funding, hiring, and news signals**. **ZoomInfo and Apollo.io charge $10K–$50K/year** for data largely scraped from public sources . **Clearbit charges $99/month** for its enrichment API . **People Data Labs offers a free tier with 100 monthly credits** and **100M+ free records available** .

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Salesforce Data.com](https://www.salesforce.com/)** ☁️ | Salesforce | ~$250 Billion | **Included with Sales Cloud**  | **Free with Salesforce subscription** | **CRM-native data enrichment** — **Data.com integration for Salesforce records**. **Contact and account data enrichment within CRM**. |
| **[ZoomInfo](https://www.zoominfo.com/)** 🎯 | ZoomInfo Technologies | ~$4 Billion | **Custom enterprise pricing** (typically $15K–$50K+/year) | **Free trial available** | **Market-leading B2B contact data** — **100M+ companies, 500M+ contacts, billions of buying signals**. **GTM.AI CLI is open source under MIT license** — search and lookup commands are free . **Enrichment and agentic research consume bulk data credits**. |
| **[Apollo.io](https://www.apollo.io/)** 🚀 | Apollo.io | ~$1.6 Billion | **$99/month** (Basic)  | **Free tier: limited credits** | **All-in-one sales intelligence and engagement** — **210M+ contacts, 35M+ companies**. **Email finder, sequences, and CRM integrations**. **Solo costs ~$0.02 per contact** . |
| **[Clearbit](https://clearbit.com/)** 🔵 | HubSpot (Acquired) | ~$30 Billion (HubSpot) | **$99/month**  | **Free tier: limited lookups** | **Enrichment API** — **Company and person enrichment, logo API, and reveal**. **Standard for filling in missing CRM data**. **Person enrichment: 0.5 credits; company enrichment: 0.25 credits**. |
| **[Cognism](https://www.cognism.com/)** 🌍 | Cognism | Private | **Custom enterprise pricing** | **Free trial available** | **International B2B data** — **Phone-verified contacts with global coverage**. **Diamond Data for EMEA compliance**. |
| **[People Data Labs](https://www.peopledatalabs.com/)** 📊 | People Data Labs | ~$1 Billion | **Free tier: 100 monthly credits**  | **Free: 100 credits/month**  | **Developer-friendly B2B data** — **100M+ free records available**. **Person enrichment, company enrichment, and job posting datasets**. **The most generous free tier in B2B data** . |
| **[Lusha](https://www.lusha.com/)** 📞 | Lusha | Private | **Custom pricing** | **Free tier: 50 credits/month** | **Direct dial and email finder** — **Browser extension for LinkedIn and Salesforce**. |
| **[LeadIQ](https://leadiq.com/)** ⚡ | LeadIQ | Private | **Custom pricing** | **Free trial available** | **Sales prospecting platform** — **Contact and account data capture from LinkedIn**. |
| **[UpLead](https://www.uplead.com/)** 📈 | UpLead | Private | **$99/month** (Essentials) | **Free trial: 5 credits** | **B2B contact data platform** — **160M+ contacts with email verification**. |
| **[Kaspr](https://www.kaspr.io/)** 🇪🇺 | Kaspr | Private | **Custom pricing** | **Free tier: limited credits** | **European B2B data** — **Phone numbers and emails for French and European professionals**. |
| **[Crunchbase Enterprise](https://www.crunchbase.com/)** 🏢 | Crunchbase | Private | **Custom enterprise pricing** | **Free tier: limited searches** | **Company and investment intelligence** — **Private company data, funding rounds, and acquisitions**. |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub_Stars_Count (Descending)* 🌟

- **[FORGE](https://github.com/Nuclear-Marmalade/dataforge)** [![Stars](https://img.shields.io/github/stars/Nuclear-Marmalade/dataforge?style=social&color=white)](https://github.com/Nuclear-Marmalade/dataforge/stargazers)  
  **Free open-source business data enrichment engine**, open-source. **The open-source alternative to Apollo, ZoomInfo, and Clearbit** — **enriches business databases using free data sources and local AI** . **No API keys, no accounts, no credit cards. Runs on your machine**. **Features**: **email extraction (6 layers)** — mailto links, regex, Cloudflare decode, JSON-LD, obfuscation decode, contact page crawl. **SMTP verification** — generates candidates (info@, contact@, admin@), verifies via RCPT TO without sending mail. **Tech detection (30+)** — WordPress, Shopify, React, Next.js, Stripe, Intercom, Google Analytics, Tailwind. **Government data importers** — FCC ULS (~3M records), NPI Registry (~7M records, free API), SAM.gov (~900K entities, free API key). **Local AI enrichment** via Ollama — business summaries, industry classification, health scores, pain points. No API costs. **Two parallel tracks**: web scraping (~16K records/hr with 4 workers) and AI track (~7-20K/day). **COALESCE writes** (only update NULL fields) and checkpoint after every batch . 🚀

- **[Signal](https://github.com/jay-sahnan/signal)** [![Stars](https://img.shields.io/github/stars/jay-sahnan/signal?style=social&color=white)](https://github.com/jay-sahnan/signal/stargazers)  
  **Open-source AI sales intelligence and outreach automation**, open-source. **The open alternative to Clay, Apollo, and Outreach — run it on your own keys** . **Watches the web for buying signals** (hiring changes, funding news, product launches, review shifts), **enriches the companies and contacts behind them**, **drafts personalized outreach**, and **runs multi-step email sequences** — all from a single chat-first workspace. **Signals engine**: authorable "recipes" that watch companies and surface buying triggers. **Contact enrichment**: pulls LinkedIn, GitHub, and company pages into a single profile. **Outreach sequences**: multi-step emails sent from your own Gmail with reply/bounce tracking. **Browser automation**: Browserbase + Stagehand for the long tail of sites without APIs. **Tech stack**: Next.js 16, React 19, TypeScript, Supabase (Postgres + Auth + RLS), Anthropic Claude, Tailwind CSS 4, shadcn/ui. **Own your data** — Postgres + RLS on your Supabase; bring your own LLM keys . 🎯

- **[enrichment-kit](https://github.com/masteranime/enrichment-kit)** [![Stars](https://img.shields.io/github/stars/masteranime/enrichment-kit?style=social&color=white)](https://github.com/masteranime/enrichment-kit/stargazers)  
  **Open-source Clay.com alternative**, open-source. **Multi-vendor enrichment waterfalls — bring your own API keys, pay ~85% less per lead** . **The waterfall pattern**: orders providers by **effective cost (`price / hit_rate`)** and **short-circuits on success** — Hunter ($0.004, 55% hit rate) → Apollo ($0.01, 70%) → SerpAPI + LLM ($0.02, 80%) → Proxycurl ($0.03, 85%). **For a 10k-lead list, typical cost lands near $60 instead of $300**. **5 providers out of the box** — Hunter, Apollo, Anymailfinder, SerpAPI + LLM, Proxycurl. **Built-in cache** — file or memory, 30-day TTL by default, enrichments are **~40% cheaper after week 1**. **Semantic validation gate** — catches role emails, domain mismatches, malformed LinkedIn URLs before they corrupt your DB. **CSV batch mode** — enrich 10k rows with one command. **CLI + SDK** — use it as a tool or embed it. **TypeScript-native** — full types, zero `any` . 🛠️

- **[Batuda](https://github.com/guillempuche/batuda)** [![Stars](https://img.shields.io/github/stars/guillempuche/batuda?style=social&color=white)](https://github.com/guillempuche/batuda/stargazers)  
  **Open-source CRM with a built-in research agent**, MIT licensed. **Find people, email them, follow up, remember the trail. Your providers, your budget. MCP-ready** . **Research as the core capability**: server-side agent loop with a **mandatory citation ledger**, a **guard chain over extracted fields**, **gap rounds** that keep searching for fields that came back empty, and **live SSE progress**. **Five typed result schemas** — CompanyEnrichmentV1, CompetitorScanV1, ContactDiscoveryV1, ProspectScanV1, Freeform. **Wired today**: Firecrawl (search + scrape), Brave (search), Hunter (enrich + verify), libreBORME (Spanish registry), Companies House (UK registry), and any OpenAI-compatible inference endpoint. **Quality you can measure**: CLI eval scores the pipeline against a **golden set of companies with known answers** — grounding accuracy, field precision and recall, decision-maker recall, and the wrong-company rate. **Contact discovery**: registry-first where a national registry exists (free and authoritative), paid enrichment elsewhere. **Pattern-guessed addresses are gated through a free DNS MX check and only asserted when a verifier confirms them** . 🏛️

- **[opengtm](https://pypi.org/project/opengtm/)** [![Stars](https://img.shields.io/github/stars/...?style=social&color=white)](https://github.com/.../stargazers)  
  **MIT-licensed open-source GTM engine**, MIT licensed. **AI-powered lead discovery, 6-dimension ICP scoring, AEO health checks, 4-touch outreach sequences, and Claude Code integration** . **Runs locally with Gemini free tier (1,500 requests/day)** — sufficient for most small teams. **Monthly cost: Free vs $807/month if you replaced opengtm with Clay, Apollo, Instantly, Semrush, Clearbit, and AEO SaaS tools**. **Use cases**: startup founders doing 0-to-1 outbound, growth agencies running discovery at scale, SEO consultants running AEO health checks. **Python API**: `discover()`, `research()`, `qualify_batch()`, `generate_messages()`, `run_health_check()`, `generate_article()`, `research_keywords()` . 📊

- **[b2b-lead-intelligence](https://pypi.org/project/b2b-lead-intelligence/)** [![Stars](https://img.shields.io/github/stars/...?style=social&color=white)](https://github.com/.../stargazers)  
  **Official Python SDK for B2B Lead Intelligence (Open-Source Apollo & Proxycurl Alternative)**, open-source. **Provides `enrich_company()`, `find_executives()`, and `get_hiring_signals()`** . **Firmographics & tech stack**: company name, headcount tier, technologies. **Executive decision-maker leads**: name, title, email, email confidence. **Growth & hiring signals**: growth stage, hiring intent score (0-100). **The most accessible Python SDK for B2B company and contact intelligence** . 🐍

- **[company-gtm-enricher](https://github.com/lucifinil/company-gtm-enricher)** [![Stars](https://img.shields.io/github/stars/lucifinil/company-gtm-enricher?style=social&color=white)](https://github.com/lucifinil/company-gtm-enricher/stargazers)  
  **Local CSV company enrichment tool for GTM data**, open-source. **Upload a CSV with company names, enrich each row with public business data, and download a refreshed CSV** . **Appends**: HQ City, HQ State, Country, Approximate Annual Revenue, Current Total Funding. **Audit columns**: Enrichment Confidence, Source URLs, Enrichment Status, Research Notes. **Streamlit UI** for upload, preview, processing, and download. **OpenAI requests batched by unique company names** to reduce request count. **Mock provider** included for dry runs without an API key. **Interim backup CSV every 10 minutes** during long runs. **Cost estimator** compares 6 curated models (GPT-5, GPT-5 mini, Claude Sonnet 4.5, Claude Haiku 4.5, MiniMax-M2.5) . 📁

- **[company-data-enrichment](https://github.com/brightdata/company-data-enrichment)** [![Stars](https://img.shields.io/github/stars/brightdata/company-data-enrichment?style=social&color=white)](https://github.com/brightdata/company-data-enrichment/stargazers)  
  **Company Data Enrichment Tool**, open-source. **Instantly enrich company lists with actionable business data using Bright Data Web Scraper API, Google Gemini AI, and Streamlit** . **Collects 13+ data points per company** — CEO, Founders, Executives, LinkedIn URL, Services, Contact Email, Headquarters, Founded, Funding, Investors, Trustpilot Rating, News, Products, Open Roles. **CSV upload** — process multiple company records in a single upload. **Progress tracking** — monitor enrichment progress as the tool processes data. **End-to-end workflow**: CSV upload → Pandas validation → Bright Data scraping → Gemini AI standardization → interactive Streamlit table . 🏢

- **[leads-db](https://github.com/IsaacBell/leads-db)** [![Stars](https://img.shields.io/github/stars/IsaacBell/leads-db?style=social&color=white)](https://github.com/IsaacBell/leads-db/stargazers)  
  **AI-powered B2B lead generation system**, MIT licensed. **Daily ingestions of company data and Newly Registered Domains (NRDs)**, identifies candidate leads, and presents best results to user . **REST API** for lead data retrieval. **Next.js frontend + Flask backend + Cassandra database**. **Automatic NRD ingestion, company data enrichment using Abstract API, and subscriber management using Notion API**. **GitHub Actions workflow for daily data updates**. **Preview available — email contact@isaacbell.io** . 🤖

- **[CObtainFlow](https://github.com/jlingjun/JJCustumorObtain)** [![Stars](https://img.shields.io/github/stars/jlingjun/JJCustumorObtain?style=social&color=white)](https://github.com/jlingjun/JJCustumorObtain/stargazers)  
  **AI-powered B2B enterprise contact discovery tool**, open-source. **Just describe what kind of supplier you're looking for, and CObtainFlow automatically completes search, organization, and report generation** . **Intelligent multi-round search**: **Broad mode** for broad discovery of new companies, **Deep mode** for completing contact info for specific companies. **Multi-channel verification**: integrates official websites, Contact/About pages, LinkedIn, enterprise directories, and social media. **Contact types**: Email, Phone (E.164 format), WhatsApp (wa.me links), LinkedIn, Contact forms, Other social media. **Structured output**: Markdown report + JSON data for CRM import. **Tech stack**: Flow orchestration layer → Crew single-round execution layer → Tool execution layer (searcher agent + organizer agent) . 🌏

- **[Fire Enrich](https://github.com/firecrawl/fire-enrich)** [![Stars](https://img.shields.io/github/stars/firecrawl/fire-enrich?style=social&color=white)](https://github.com/firecrawl/fire-enrich/stargazers)  
  **AI-powered data enrichment tool that transforms emails into rich datasets**, open-source. **Transforms emails into company profiles, funding data, tech stacks, and more using Firecrawl and multi-agent AI** . **Five specialized agents**: **Discovery Agent** (company name, website, business type), **Company Profile Agent** (industry, headquarters, year founded), **Financial Intel Agent** (funding stage, total raised, investors), **Tech Stack Agent** (programming languages, frameworks, infrastructure), **General Purpose Agent** (custom fields like CEO, competitors). **Sequential execution with shared context** — each agent adds context that makes subsequent searches more accurate. **Type-safe Zod schemas** for easy extensibility. **Field routing system** automatically categorizes user requests . 🔥

- **[ai-ark-mcp](https://github.com/dropoutsanta/ai-ark-mcp)** [![Stars](https://img.shields.io/github/stars/dropoutsanta/ai-ark-mcp?style=social&color=white)](https://github.com/dropoutsanta/ai-ark-mcp/stargazers)  
  **MCP server for AI Ark API**, open-source. **Search 400M+ people, 69M+ companies, find verified emails, phone numbers, and analyze personalities** . **Works with Cursor, Claude, Windsurf, and any MCP-compatible client**. **10 tools**: `search_companies`, `search_people`, `export_people_with_email`, `find_emails_by_track_id`, `get_export_results`, `get_email_statistics`, `reverse_people_lookup`, `find_mobile_phone`, `analyze_personality`, `get_credits`. **Email finding is async (15-120 seconds)** — search for people, get a trackId, and poll for verified emails. **Each email is verified in real time by BounceBan** — you get the email address, validation status (VALID/INVALID), and MX provider . 📡

- **[OpenCRM](https://github.com/clawnify/OpenCRM)** [![Stars](https://img.shields.io/github/stars/clawnify/OpenCRM?style=social&color=white)](https://github.com/clawnify/OpenCRM/stargazers)  
  **Open-source HubSpot alternative**, MIT licensed. **A lightweight CRM for SaaS to manage contacts, companies, and deals** . **Contacts belong to companies. A deal has its own company and its own contact, both optional**. **Custom attributes are real columns**, registered in `custom_field_defs`. **Relations** are two defs, one per side, pointing at each other (`inverse_def_id`). **List endpoints take `filters`**: a JSON list, ANDed, of rules `{field, op, value}` and groups `{logic: "and"|"or", rules: [...]}`. **Operators**: `contains`, `does_not_contain`, `is` / `is_not`, `is_empty`, `is_not_empty`, `gt` / `gte` / `lt` / `lte`, and for dates `on`, `before`, `after`, `today`, `in_past`, `in_future`, `relative` (`PAST_7_DAY`, `NEXT_2_WEEK`, `THIS_1_MONTH`) . 🏢

- **[AI Lead Generation and Enrichment Tool](https://github.com/mir-ehmad/ai-lead-generation-and-enrichment-tool)** [![Stars](https://img.shields.io/github/stars/mir-ehmad/ai-lead-generation-and-enrichment-tool?style=social&color=white)](https://github.com/mir-ehmad/ai-lead-generation-and-enrichment-tool/stargazers)  
  **AI-powered lead generation and enrichment tool**, open-source. **Combines Apify for lead scraping, AI for personalization, and HubSpot for CRM integration** . **Supports LinkedIn and Apollo as lead sources**. **Generates personalized outreach messages and manages leads in HubSpot**. **Configurable daily lead generation through HubSpot scheduler** . 🎯

---

## 🛠️ How to Contribute

Contributions are welcome! Follow these steps to submit new B2B lead intelligence platforms or open-source enrichment software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-B2b-Lead-Intelligence-Data-Enrichment&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-B2b-Lead-Intelligence-Data-Enrichment&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship

If you find this B2B lead intelligence and data enrichment repository useful, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow sales operations leaders, demand generation teams, and open-source advocates.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- **Apollo, ZoomInfo, and Clearbit charge $10K–$50K/year** for data that is **largely scraped from public sources** — **FORGE does the same thing for free** . **enrichment-kit pays ~$0.004 per verified contact** vs **~$0.12 for Clay** by using multi-vendor waterfalls .
- **Signal is designed for single-tenant self-hosting** — **one Supabase project per team** . **Upgrading from pre-Clerk versions is destructive and not reversible** — it **wipes all user-owned data** because old Supabase user UUIDs don't map to Clerk IDs .
- **People Data Labs offers a free tier with 100 monthly credits** and **100M+ free records available** — the **most generous free tier in B2B data** . **Clearbit charges 0.5 credits per person enrichment and 0.25 credits per company enrichment** .
- **Open-source enrichment tools are not turnkey** — **FORGE requires PostgreSQL and Python 3.x** . **Signal requires Node 20+, Docker, Supabase CLI, and an Anthropic API key** . **Batuda requires Node 24, pnpm 10, Docker, and Postgres** . **Always validate email verification accuracy, data freshness, and compliance (GDPR, CCPA) with a proof-of-concept** before production deployment. 🔍

---

<p align="center">
  <b>Made with ❤️ for sales operations leaders, demand generation teams, and open-source B2B intelligence advocates.</b>
</p>
