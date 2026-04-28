# Vapi MoTS Forward Deployed, Application Notes

**Role:** Member of Technical Staff, Forward Deployed
**Location:** San Francisco (onsite)
**Comp band:** $150K to $300K base plus meaningful equity plus visa sponsorship
**Stage:** YC W21, Series A $20M (Bessemer, Dec 2024), $130M post-money, ~$8M ARR, 5x YoY enterprise growth
**JD:** https://jobs.ashbyhq.com/vapi/854a9bf5-e330-4afa-9c0f-38c3d6084808
**Company brief:** `interview-prep/company-research-vapi.md`

---

## Key People (LinkedIn references)

- Jordan Dearsley, Co-founder and CEO. https://www.linkedin.com/in/jordandearsley/
  - Podcast circuits: Deepgram AI Minds #056, Coval, Krisp Voice AI Newsletter.
  - Recurring thesis: "IVRs are dying"; voice agents will live in your contacts list alongside humans.
- Nikhil Gupta, Co-founder and CTO. https://www.linkedin.com/search/results/people/?keywords=Nikhil%20Gupta%20Vapi
  - CTO still owns engineering directly; FDE role likely reports close to founders.

---

## Talking Points for the Screen Call

1. Crazy-caller is a from-scratch version of Vapi. Pure-TypeScript bridge between Twilio Programmable Voice and Gemini Live, hand-rolled audio codec, 30 voices, tool calling, TDD around the latency-critical paths. I can speak credibly to every layer the FDE role debugs in the field. Codec edge cases, latency budget, barge-in, tool calling, observability.

2. V2V Intelligence is the deployed version. Live SaaS with paying subscribers since 30 Mar 2026, and the production voice intake agent runs on the same Twilio plus Gemini Live stack a Vapi customer would adopt. I have run the 30-day "deploy a voice agent into a regulated, document-heavy environment" play already, just for myself.

3. The 25-tool MCP research platform is the productization muscle. Unified MCP server suite on GCP Cloud Run serving both AI agents and humans. Bespoke customer asks turned into reusable tooling. That is the 90-day milestone in the JD, expressed in code.

4. Eval-driven, not vibes. 55 to 83 percent retrieval quality lift in a controlled harness against real CAVC outcomes. Plus llm-compaction-benchmark, six Gemini models across 36 combinations. FDEs have to convert pilots into ARR; you do that with measurable customer-impact metrics, not promises.

5. Founder loop equals FDE loop. Three years running solo client-facing work in a regulated domain, plus the V2V solo build. Same posture as Forward Deployed at Palantir or OpenAI. Bridge sales and product, own one account end-to-end, productize learnings.

---

## Risk to Pre-Defuse: SF Onsite vs Ohio

The biggest friction is geography. Address it once, briefly, then move on.

**Pre-prepared answer:**
> "I'm based in Ohio today, but I'm open to relocating to SF for this role. Voice AI is the part of the market I most want to ship into, and the Vapi roadmap is where it's actually being built. I can talk through timing or an interim hybrid cadence if that helps."

**Do not:**
- Anchor compensation early. Vapi's posted floor ($150K) is above my prior target ceiling. Let them name the band.
- Offer relocation as a concession or apology. State it as a fact and move on.
- Bring up "but I'd prefer remote." That signals friction the role does not want.

---

## "What would your first 90 days at Vapi look like?"

> "Day one to thirty, I'd embed deeply with the assigned enterprise customer. Read every piece of internal context on the account, sit on every customer call, get into their voice flows, and stand up the first production deployment. The goal is a voice agent answering real calls inside their environment by end of week four. I have run that exact 30-day shape solo at V2V on Twilio plus Gemini Live, so I know where the codec, latency, barge-in, and tool-calling traps are.
>
> Day thirty to sixty, I'd do customer discovery inside the same account. Adjacent use cases that the deployment surfaces but doesn't yet serve. A second voice flow, an outbound campaign, a tool integration into their CRM or ticketing system. Two or three of those concrete adjacent wins, ideally one that expands the contract.
>
> Day sixty to ninety, I'd take the patterns that showed up in that account and turn them into Vapi product. Whether that is a new template, a primitive in the platform, an evals harness extension, or internal tooling for the next FDE shipping the same shape. The 25-tool MCP platform I built was that exact muscle in another domain. Bespoke customer work productized into reusable surface. The next deployment of the same shape should take a fraction of the time. That is how an FDE compounds."

---

## Why FDE, Not Founder (pre-defuse if asked)

> "V2V is live and paying. I'm not leaving the project, but solo founders hit a ceiling on shipped scope. The next chapter I want is compounding inside a category-leading voice AI team, with senior engineers and a real distribution surface. Vapi's deployment surface is exactly where I want to spend it. The FDE loop is what I'm already optimized for."

---

## Application Checklist

- [ ] Cover letter at `interview-prep/applications/vapi-mots-fde/cover-letter.md`
- [ ] Tailored CV at `interview-prep/applications/vapi-mots-fde/cv-tailored.md`
- [ ] Generate PDF from tailored CV via `/career-ops pdf`
- [ ] Submit through Ashby (https://jobs.ashbyhq.com/vapi/854a9bf5-e330-4afa-9c0f-38c3d6084808)
- [ ] Optional: short LinkedIn note to Jordan Dearsley referencing crazy-caller as a Vapi-shaped portfolio piece. Acknowledge the work, do not pitch.
- [ ] Update `data/applications.md` status to Applied after submission.
- [ ] Schedule follow-up reminder at 7 days.
