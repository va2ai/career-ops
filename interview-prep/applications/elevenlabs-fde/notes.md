# ElevenLabs FDE - Application Notes

**Role:** Forward Deployed Engineer - Software Engineer
**Location:** San Francisco
**Score:** 4.5/5
**Posting:** https://jobs.ashbyhq.com/elevenlabs/6c4c57c1-ec72-42ba-af3a-eb7aebbde2e6

---

## Talking points to bring to the screen

1. **The crazy-caller hand-roll.** Real-time AI phone assistant on Twilio plus Gemini Live with a pure-TypeScript audio codec, 30 voices, tool calling, TDD, real-time turn-taking. This is essentially a one-person reference implementation of what an ElevenLabs FDE delivers in week one through the Twilio native connector. Lead with what would change to swap Gemini Live for Eleven Agents (event loop, codec edges at PCM and mu-law, latency budget rebalance against Scribe v2 sub-150ms STT). That framing signals I am already integrating their product mentally.

2. **V2V Intelligence is the FDE loop run on myself.** Live since 30 March 2026, paying subscribers, regulated domain. Discovery, prototype, integrate, deploy, change management, SLA ownership. Done solo. The same loop FDEs run, just for someone else's product. Concrete proof: Stripe billing plus Twilio voice intake plus retrieval plus document automation, all running in production.

3. **Already shipping on MCP.** 25-tool MCP Research Platform on GCP Cloud Run, unified surface for agents and humans. ElevenLabs Agents bets on MCP tool-calling. I am not learning the abstraction; I am extending it.

4. **Eval discipline, not vibes.** Retrieval quality moved from 55 to 83 percent through controlled testing against real outcomes. Same discipline transfers to voice agent quality work, Agent Coaching, and Evaluation surfaces.

5. **Customer-facing depth.** 15+ years in a regulated, document-heavy, high-stakes domain. I have done the C-suite-style conversation under pressure where wrong answers cost real money. Fortune 500 enterprise eng teams will not be the first time I have owned an SLA in a sensitive context.

---

## Pre-prepared answer: "you've never worked at a TTS company specifically - what gives you confidence here?"

Two things.

First, crazy-caller. I wrote a TypeScript audio codec from scratch because I wanted to debug at the PCM and mu-law layer where most voice integrations actually break. 30 voices, real-time turn-taking, tool calling, TDD. I have spent time inside the audio frame where the latency and quality trade-offs you ship at ElevenLabs live. I am not coming in to learn what a codec is.

Second, the FDE arc is product-shaped, not company-shaped. I have run the discovery-to-integration-to-rollout loop end-to-end as the only engineer on V2V Intelligence in production. Swapping the underlying voice stack from Gemini Live to Eleven Agents is a week of integration work for someone with my background. The harder skill, sitting with a customer's eng team and an exec, building a bespoke integration in days, and owning it through scaling and compliance, is exactly what I have been doing for two years. ElevenLabs is the right product surface for that skill. It is not the skill itself.

If you want a cheap signal before our next conversation, I will ship a small public ElevenLabs Agents plus Twilio integration and send you the repo.

---

## Key people (LinkedIn search URLs)

- **Mati Staniszewski** - CEO and co-founder, ex-Palantir deployment strategist. The FDE motion is the real Palantir pattern at ElevenLabs because Mati ran it himself.
  https://www.linkedin.com/search/results/people/?keywords=Mati%20Staniszewski%20ElevenLabs

- **Alexander (Alex) Holt** - VP Engineering. Leads enterprise eng and largest customers. Likely owner or skip-level for this FDE track.
  https://www.linkedin.com/search/results/people/?keywords=Alexander%20Holt%20ElevenLabs

- **Tim von Kanel** - VP Backend Engineering. Backend architecture decisions for the platform FDEs deploy on top of.
  https://www.linkedin.com/search/results/people/?keywords=Tim%20von%20Kanel%20ElevenLabs

- **Piotr Dabkowski** - CTO and co-founder, ex-Google ML. Deep model side.
  https://www.linkedin.com/search/results/people/?keywords=Piotr%20Dabkowski%20ElevenLabs

- FDE team search.
  https://www.linkedin.com/search/results/people/?keywords=%22Forward%20Deployed%22%20ElevenLabs

---

## Risk to pre-defuse

**No production ElevenLabs API in my portfolio yet.** crazy-caller uses Gemini Live. My V2V voice intake uses Twilio plus Gemini Live. ElevenLabs sees this gap immediately.

**Pre-defuse:** Acknowledge it directly in the screen. "Correct, I have not shipped on the ElevenLabs SDK in production. crazy-caller used Gemini Live because that was the lowest-friction stack at the time. Before our next conversation I will publish a small ElevenLabs Agents plus Twilio integration so you can verify pickup speed against your bar." Then actually ship it. Two to three day demo. High signal at low cost. The audio codec depth in crazy-caller already proves I can debug at the layer where the swap matters.

**Secondary risk:** Comp opacity. Their pattern is to negotiate base hard against equity. Anchor at $190K base on the first comp call. Settle no lower than $170K with meaningful Series D equity. Do not anchor to the profile.yml floor; this is a $11B company at Series D with IPO chatter.
