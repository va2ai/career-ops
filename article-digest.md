# Article Digest -- Proof Points for Chris Combs

<!-- Compact proof points pulled from public portfolio (github.com/va2ai + vaclaims.net).
     Used by career-ops to ground STAR stories, draft answers, and CV variants. -->

## Headline Achievements

- **V2V Intelligence** — Production legal-intelligence SaaS, live since 30 Mar 2026. Sole engineer; 0→1; paying subscribers. Veterans legal corpus (BVA, CAVC, 38 CFR, M21-1, KnowVA, Federal Register).
- **Retrieval quality lift: 55% → 83%** in controlled ablation against real CAVC outcomes.
- **25+ tool BVA MCP Research Platform** on GCP Cloud Run, unified surface for agents and humans.

## Public Repos (github.com/va2ai)

### Retrieval & RAG
- **rag-decision-analysis-system** — Graph-lite schema for BVA decision analysis with pgvector; "100-Decision Test" validation harness. (Python, ⭐1)
- **bva-decision-intelligence** — TypeScript, BVA decision intelligence layer.
- **edge-ai-search-validation-service** — Deep research API on Cloudflare Workers using OpenAI Responses API. (JavaScript)

### Multi-Agent & Platform
- **ai-agent-platform** — Multi-agent platform with Gemini 3.1, pgvector, custom runtime, chat UI. (Python)
- **ai-agent-orchestration-platform** — Agent orchestration platform. (Python, ⭐1)
- **gcp-mcp-deployer** — Shell tooling for deploying MCP servers to GCP.

### Faithfulness, Eval, & Quality
- **bva-citation-validator** — Post-generation citation validator: detects hallucinated CFR citations, BVA docket numbers, and CAVC case references in LLM responses. (JavaScript)
- **llm-compaction-benchmark** — Benchmarks LLM conversation compaction quality across 6 Gemini models, 36 combinations. (Python)

### Real-Time AI / Voice
- **crazy-caller** — Real-time AI phone assistant bridging Twilio and Gemini Live API; pure TypeScript audio codec, 30 voices, tool calling, TDD. (TypeScript)

### Public APIs
- **bvaapi2** — BVA Decision Search API + KnowVA Knowledge Base API. (Python)

### Misc public
- **devportai** (⭐1), **portfolio-site**, **awesometmplate**, **claude-remote**, **sandbox**, **excel-converter**, **skate-editor**.

## When to Cite Which Proof Point

| If the role asks about... | Lead with... |
|---------------------------|--------------|
| Production AI / shipping | V2V Intelligence (live, paying users, March 2026) |
| Retrieval / RAG | rag-decision-analysis-system + 55%→83% ablation |
| Multi-agent / orchestration | ai-agent-platform + 25+ tool MCP Research Platform |
| Hallucination / faithfulness | bva-citation-validator + eval-driven dev |
| LLM evaluation / benchmarking | llm-compaction-benchmark (6 models × 36 combos) |
| MCP / Anthropic ecosystem | 25-tool MCP platform + gcp-mcp-deployer |
| Voice / real-time AI | crazy-caller (Twilio + Gemini Live) |
| Edge / Cloudflare | edge-ai-search-validation-service |
| Domain expertise (regulated) | 15 yrs VA claims/appeals → directly powers V2V |
| Full-stack / TypeScript | V2V (React 19, TS, Node, Firebase, Cloud Run) |
| Stripe / billing | V2V Stripe Checkout + webhook + quota gating |
| Founder / 0-to-1 | V2V solo build, March 2026 launch |

## Differentiators (One-Liners)

1. "Engineer who actually shipped a paying-user AI SaaS solo — not just demos or POCs."
2. "Combines 15 years of regulated-domain operational depth with applied AI engineering — rare combination that produces grounded, faithful systems."
3. "Eval-driven discipline — 55%→83% wasn't a guess; it came from a controlled ablation against real-world outcomes."
4. "Built a 25-tool MCP research platform — early adopter of the agent-tooling stack now becoming standard."
