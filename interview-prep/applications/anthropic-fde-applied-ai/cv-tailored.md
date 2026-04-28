# Chris Combs

**Forward Deployed Engineer · Applied AI · MCP Platform Builder**

Miamisburg, OH (open to relocation) | ai@vaclaims.net | [github.com/va2ai](https://github.com/va2ai) | [vaclaims.net](https://vaclaims.net)

---

## Professional Summary

Senior applied AI engineer with 15+ years shipping production systems and 18 months operating as a solo founder-engineer of a live, paying-user AI SaaS. Builds MCP servers, sub-agents, agent skills, and eval-driven retrieval pipelines for regulated, audit-trail-heavy workflows. Production Claude, Gemini, and Grok routing in customer-facing systems today. Comfortable embedded with enterprise customers, translating ambiguous requirements into deployed Claude applications.

---

## Core Capabilities

**Applied AI / LLM Systems**
- MCP server architecture (25-tool platform in production)
- Multi-agent orchestration and sub-agent design
- Agent skills, tool routing, and runtime guardrails
- Claude API integration and model routing (Claude, Gemini, Grok)
- Retrieval-augmented generation, pgvector, controlled evals
- Hallucination reduction and grounded outputs (citation validators)
- Evaluation frameworks and quality benchmarking
- Prompt systems and workflow automation

**Engineering**
- Python, TypeScript, JavaScript
- React 19, Next.js, Node.js, Express
- SQL, PostgreSQL, pgvector
- REST APIs, WebSockets, SSE
- Vitest, Playwright, Testing Library, CI/CD

**Cloud / DevOps**
- Google Cloud Run
- Firebase (Auth, Firestore, Functions, Hosting)
- Docker, Cloudflare R2
- CI/CD pipelines, monitoring, reliability

**Product Systems**
- Stripe subscriptions and billing automation
- Twilio voice systems (Programmable Voice + Gemini Live)
- PDF automation and structured document generation
- SaaS onboarding, growth, and SEO infrastructure

---

## Professional Experience

### Founder & Lead Engineer
*V2V Intelligence | Remote (Miamisburg, OH) | 2024 – Present*

Solo founder-engineer of a production legal-intelligence SaaS, live with paying subscribers since 30 March 2026.

- Architected and deployed a **25+ tool MCP research platform** on GCP Cloud Run; unified tool surface for sub-agents and human users across BVA decisions, CAVC cases, 38 CFR, M21-1, KnowVA, and Federal Register data sources.
- Designed and orchestrated **multi-agent workflows** with custom runtime, per-tool budgets, retry on hallucination signal, and observability across Claude, Gemini, and Grok.
- Lifted retrieval quality from **55% to 83%** through controlled testing against real CAVC outcomes, using a 100-decision held-out gold set and documented ablation harness adopted as the team standard for retrieval changes.
- Built a **post-generation citation validator** that detects hallucinated 38 CFR, BVA docket, and CAVC references in LLM output; integrated into the V2V production output pipeline with audit logs.
- Built full-stack production platform with **React 19, TypeScript, Node.js, Firebase, and Google Cloud Run**.
- Implemented **Stripe Checkout, recurring billing, webhook automation, quota enforcement, and usage controls**.
- Built AI-powered document intake and form automation pipelines using structured extraction and PDF generation (pdf-lib, jsPDF).
- Built a **real-time voice assistant** using Twilio Programmable Voice and Gemini Live APIs.
- Owned product strategy, engineering, DevOps, AI quality, billing, UX, and growth.

### Independent AI Engineering Consultant
*Generative AI Ohio | Ohio | 2023 – Present*

Production AI customer deployments for clients in regulated workflows. Multi-agent workflow design, MCP server development, agent tooling integrations, retrieval evaluation, and faithfulness validation. Multiple POC-to-production handoffs across two years.

### Independent Consultant, Regulated Domain Operations
*Self-employed | 2009 – 2024*

15+ years of high-stakes case workflows in a complex, document-heavy regulated domain. Direct client-facing translation between medical evidence, federal statute, and decision logic. Operational depth that informs grounded AI design surviving real customer constraints.

---

## Selected Projects

- **25+ Tool MCP Research Platform.** Unified tool surface for sub-agents and humans on GCP Cloud Run. Per-tool latency and error budgets, stateless idempotent calls, deployed via open-sourced `gcp-mcp-deployer`. Core differentiator inside V2V Intelligence.
- **BVA Citation Validator** ([github.com/va2ai/bva-citation-validator](https://github.com/va2ai/bva-citation-validator)). Post-generation faithfulness layer. Detects hallucinated 38 CFR, BVA docket, and CAVC citations in LLM responses. Open-source TypeScript.
- **V2V Intelligence** ([vaclaims.net](https://vaclaims.net)). Production legal-intelligence SaaS. Live since 30 March 2026 with paying subscribers. Sole engineer, end-to-end ownership.
- **LLM Compaction Benchmark.** 6 Gemini models across 36 combinations, evaluating conversation compaction quality. Eval-driven discipline applied to model selection.

---

## Key Differentiators

- Ships production Claude applications with paying users, not demos.
- MCP-native builder: 25-tool platform in production before MCP became standard.
- Eval-driven, not vibe-coded: 55% to 83% retrieval lift was measured through controlled testing.
- 15 years regulated-domain depth translates directly to healthcare, federal, and financial-services enterprise customers.
- Solo founder discipline plus team-ready: high agency, customer-facing, used to navigating ambiguous requirements.
