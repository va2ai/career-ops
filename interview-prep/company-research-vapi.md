# Vapi — Company Research Brief

**Role:** Member of Technical Staff, Forward Deployed (San Francisco)
**JD:** https://jobs.ashbyhq.com/vapi/854a9bf5-e330-4afa-9c0f-38c3d6084808
**Comp:** $150K–$300K base + equity + visa sponsorship (per YC listing)
**Prepared:** 2026-04-27

---

## 1. Company snapshot

Vapi (legal entity: Superpowered Labs Inc.) is a developer platform for building, testing, and deploying voice AI agents. Their stack orchestrates STT + LLM + TTS into a single low-latency pipeline; they sit one layer above Deepgram/ElevenLabs/Twilio and abstract the plumbing.

- **Founded:** 2020 (originally as Superpowered, a productivity app; pivoted to Vapi in late 2023)
- **YC Batch:** Winter 2021 (W21)
- **HQ:** San Francisco, CA
- **Team size:** ~50 per YC profile, ~153 per Tracxn (Jan 2026) — likely ~100–150 today and growing fast
- **Tagline:** "Bend the arc of technology back to the human voice"
- **Traction:** 600K+ developers in two years, ~5x YoY enterprise growth, $4.5M ARR (2024) → $8M+ (2025) per Latka
- **Notable customers:** New York Life, Intuit, Mindtickle, Luma Health, Ellipsis Health, Deepgram

## 2. Funding trajectory

- **Series A:** $20M, Dec 2024, **$130M post-money valuation**
- **Lead:** Bessemer Venture Partners
- **Co-investors:** Abstract Ventures, AI Grant, Y Combinator, Saga Ventures, Michael Ovitz (angel)
- **Total raised:** ~$22–25M
- **No public Series B as of April 2026** — but given enterprise growth and the voice-AI hype cycle (20% of YC's 2025 batch were voice startups, $3B+ VC into voice since 2024), a B is plausible in 2026.

## 3. Recent news / launches (last ~6 months)

- **VapiCon 2025** (Oct 2, 2025, SF): first-ever Voice AI Summit. Panels on Frontier Speech Models, Voice AI Infrastructure & Scaling. Big positioning moment — Vapi staking out leadership of the developer voice-AI category.
- **Vapi Evals** (2025): testing framework for functional/regression testing of voice agents via mock conversations. Direct relevance to the FDE role (customers want repeatable QA).
- **Enterprise tier**: HIPAA-compliant deployments, unlimited concurrency, 24/7 support — pushed hard at healthcare (Luma Health, Ellipsis Health) and financial services (NYLife).
- **Hiring wave:** 5 active MoTS roles on YC (Forward Deployed, Frontend, Infra, Infra-Security, Customer Support Eng). Aggressive engineering build-out.

## 4. Key people

| Role | Name | LinkedIn search pattern |
|---|---|---|
| Co-founder / CEO | **Jordan Dearsley** | https://www.linkedin.com/in/jordandearsley/ |
| Co-founder / CTO | **Nikhil Gupta** | https://www.linkedin.com/search/results/people/?keywords=Nikhil%20Gupta%20Vapi |
| Head of Eng / VP Eng | (not publicly identified — likely doesn't exist as a role yet; CTO still owns eng) | https://www.linkedin.com/search/results/people/?keywords=Vapi%20engineering |
| Head of Forward Deployed | (no public lead — this is likely a "founding-flavored" role reporting close to founders) | https://www.linkedin.com/search/results/people/?keywords=Vapi%20forward%20deployed |

Jordan does podcast circuits (Deepgram AI Minds #056, Coval, Krisp Voice AI Newsletter); his recurring thesis is "IVRs are dying" and voice agents will live in your contacts list alongside humans.

## 5. What "Forward Deployed" means at Vapi

From the JD and YC listing, this is Palantir-style FDE adapted to a voice-AI platform play:

- **Day-to-day:** Own a single enterprise customer end-to-end after the deal closes. Be the PM + engineer for both their team and Vapi's. Solve technical issues at any phase of the customer journey.
- **30-60-90 framework (verbatim from JD):**
  - **30 days:** Deploy a large enterprise onsite.
  - **60 days:** Discover 2nd and 3rd use cases inside that account.
  - **90 days:** Build product that makes the next similar deployment trivial (i.e., productize what you learned).
- **Stack:** Typescript + Node, prompt engineering, plus customer-facing technical comms.
- **Required:** 1+ years (at YC listing; the Ashby version says 2+) shipping to enterprise customers, ideally at an early-stage startup. Bonuses for prior FDE experience or founder background.

The role is explicitly the bridge between sales and product — half deployment engineer, half PM, half de-facto founder for one account.

## 6. Comp signals

- **Vapi (this role):** $150K–$300K base + equity (YC listing)
- **OpenAI MoTS, SF:** ~$237K avg, up to ~$378K (90th pct) — Glassdoor
- **Palantir FDE:** ~$238K avg total comp; staff FDEs $630K+ — public comp data
- **OpenAI / Anthropic FDE (mid-senior):** $350K–$550K stabilized
- **Series B agentic startup FDE benchmark:** $130K–$180K + equity + relocation

Vapi is sitting roughly mid-market — Series A pricing with OpenAI-style title inflation. The $300K top of band is real for someone with shipped enterprise + early-stage chops; expect equity to be the big lever (Series A at $130M means meaningful upside if a B prints in 2026).

## 7. What's likely to impress them

Chris's profile aligns unusually well. Vapi sells a developer platform that orchestrates Twilio/Deepgram/LLM/TTS into voice agents — and Chris has already built that exact stack from scratch. **Crazy-caller (Twilio + Gemini Live + a hand-rolled TS audio codec, 30 voices, TDD) is essentially a from-scratch demo of what Vapi abstracts**, which means he can speak credibly to every layer the FDE role debugs (codec edge cases, latency, barge-in, tool-calling). The **V2V Intelligence live voice agent on Twilio Programmable Voice + Gemini Live** is a deployed, production-shaped equivalent of what Vapi customers are trying to ship in their first 30 days. The **25-tool MCP research platform** signals exactly the "build product that makes the next deployment trivial" muscle the 90-day milestone calls for — turning bespoke customer asks into reusable tooling. The **55%→83% retrieval lift** is the kind of measurable, customer-impact metric FDEs need to show to justify pilots converting to ARR. Pair that with TypeScript fluency (Vapi's stack) and it's a near-perfect fit profile: he's done both halves of the job already, just for himself.

---

## Sources

- [Vapi YC profile (founders, team, jobs)](https://www.ycombinator.com/companies/vapi)
- [MoTS Forward Deployed JD (YC)](https://www.ycombinator.com/companies/vapi/jobs/3GU4CIx-member-of-technical-staff-forward-deployed)
- [Vapi $20M Series A — Bessemer announcement](https://www.bvp.com/news/our-investment-in-vapi-the-voice-ai-developer-platform)
- [SiliconANGLE: Vapi $20M Series A](https://siliconangle.com/2024/12/12/vapi-secures-20m-advance-ai-voice-agent-platform-scale-operations/)
- [Sacra: Vapi valuation & funding](https://sacra.com/c/vapi/)
- [Tracxn: Vapi 2026 profile](https://tracxn.com/d/companies/vapi/___SoH-BLiCayDw_mTGLHOiTAhjxhsyDFWfZsDK9vzq4g)
- [Latka revenue/team data](https://getlatka.com/companies/vapi.ai)
- [VapiCon 2025 recap — Krisp](https://voice-ai-newsletter.krisp.ai/p/takeaways-from-vapicon-2025)
- [Jordan Dearsley on Deepgram AI Minds #056](https://deepgram.com/podcast/ai-minds-056-jordan-dearsley-founder-ceo-at-vapi)
- [Coval interview with Jordan Dearsley](https://www.coval.dev/blog/voice-ai-platforms-in-2025-a-conversation-with-vapi-founder-jordan-dearsley)
- [TechCrunch: Superpowered → Vapi pivot](https://techcrunch.com/2023/11/10/yc-backed-productivity-app-superpowered-pivots-to-become-a-voice-api-platform-for-bots/)
- [Jordan Dearsley LinkedIn](https://www.linkedin.com/in/jordandearsley/)
