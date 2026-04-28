# Application Notes — Anthropic FDE, Applied AI

**Role:** Forward Deployed Engineer, Applied AI
**Score:** 4.9/5 (Tier 1, top priority)
**Date applied:** 2026-04-27
**JD URL:** https://job-boards.greenhouse.io/anthropic/jobs/4985877008
**Comp band (posted):** $200K–$300K base USD

---

## Talking points for screening call

- **MCP platform in production.** Lead with the 25-tool MCP research platform on GCP Cloud Run. Anthropic invented MCP; few candidates have shipped a 25-tool surface against it. Be ready to draw the architecture: agent runtime → MCP tool layer → data sources (BVA, CAVC, 38 CFR, M21-1, KnowVA, Federal Register). Mention `gcp-mcp-deployer` as the open-sourced deploy path.

- **Eval-driven discipline (55% → 83% retrieval).** Walk the methodology: 100-decision held-out gold set, k-shot embedding/chunking/reranker variants, precision@k against ground-truth panel decisions. The story is not the number, it is the harness that became the standard for any retrieval change.

- **Faithfulness as product requirement.** The BVA citation validator catches hallucinated 38 CFR, BVA docket, and CAVC references post-generation. Frame this as Anthropic-aligned safety thinking applied at the product layer. Mention audit logs of caught hallucinations.

- **V2V Intelligence shipping (paying users since 30 Mar 2026).** Use this as proof of end-to-end ownership: customer discovery, deploy, debug, integrate, support. Solo founder-engineer = compressed FDE skill set with no institutional cover. Stack: React 19, TS, Node, Firebase, GCP Cloud Run, Stripe, Twilio + Gemini Live, Claude in production.

- **Regulated-domain transfer.** 15 years VA claims = healthcare-adjacent (medical evidence, disability ratings) + federal-adjacent (38 CFR, BVA process). Same constraint shape as enterprise healthcare and finance: regulated, audit-trail-heavy, faithfulness-critical. Expect 3–4 week domain ramp on a new vertical; architectural patterns transfer.

---

## Risk to pre-defuse

**Location / hybrid attendance.** Chris is in Miamisburg, OH; the role requires 25% in-office at Boston, Chicago, NYC, Seattle, SF, or DC. None are in Ohio. Address head-on early in the screening:

> "I am open to relocating to any of your six hub cities within 60–90 days of an offer. DC is my top preference for federal and regulated-domain proximity; SF is second for product team density. The 25% travel cadence is consistent with how I have worked as a consultant and founder."

Do not hedge, do not apologize for OH, do not suggest remote-only. Anthropic posted the requirement explicitly — the answer needs to be a clean yes.

Secondary risk worth being ready for: "Why leave founder mode?" Answer: V2V is operating; growth is incremental. The next compounding learning curve is inside a top-tier AI team building on the MCP and Claude stack I have already invested in.

---

## Sister-role swap-in (if applying to other Anthropic Applied AI roles)

Anthropic posted 9+ Applied AI / FDE variants the same day. If swapping the cover letter for a sister role (Applied AI Architect, Applied AI Engineer, Solutions Engineer, etc.), keep the body intact and replace the opening hook with one of:

- **Applied AI Architect / Engineer (non-FDE):** "Anthropic's Applied AI team ships Claude into customer systems. I have spent 18 months doing exactly that solo: V2V Intelligence runs Claude in production for paying users on a 25-tool MCP platform I built on GCP Cloud Run."

- **Solutions Engineer / Solutions Architect:** "I have built and operated the customer side of an applied-Claude deployment end to end. V2V Intelligence is live with paying users on a 25-tool MCP research platform; I want to bring that customer-embedded discipline to Anthropic's enterprise solutions work."

- **Member of Technical Staff (Applied):** Drop the FDE framing and lead with the MCP platform plus the 55% to 83% retrieval lift as evidence of production research-to-product discipline.

Keep the relocation statement, the eval-driven paragraph, and the closing direct ask in all variants.

---

## Comp anchor reminders

- JD posted $200K–$300K base. This is **above** Chris's quoted ceiling.
- Do **not** anchor to profile.yml's $110–180K range. Disregard it for this role.
- When asked for expectations, anchor at **$260K base** plus equity question. If pushed, accept floor of $240K with accelerated equity vest or signing.
- Equity at this stage of Anthropic is the headline number — ask explicitly: "What does the equity grant look like at this level?"
