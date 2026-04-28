# ElevenLabs - Company Brief (Forward Deployed Engineer, SF)

**Role:** Forward Deployed Engineer - Software Engineer | **Location:** San Francisco | **Comp:** Undisclosed
**URL:** https://jobs.ashbyhq.com/elevenlabs/6c4c57c1-ec72-42ba-af3a-eb7aebbde2e6
**Brief date:** 2026-04-27

## 1. Company snapshot

ElevenLabs is the category-defining AI audio/voice lab: production-grade TTS, voice cloning, dubbing, Scribe (STT), and now ElevenLabs Agents (conversational voice + chat). Founded 2022 by Mati Staniszewski (CEO, ex-Palantir deployment strategist) and Piotr Dabkowski (CTO, ex-Google ML). HQ London + New York; major SF presence. Headcount ~400 (Sept 2025) -> ~776 (March 2026); aggressive US hiring. ~$330M ARR (175% YoY), serving ~41% of the Fortune 500, 250k+ agents built on platform.

## 2. Funding trajectory

- **Series C, Jan 2025:** $180M @ $3.3B - co-led by a16z and ICONIQ Growth; NEA, Sequoia, Salesforce Ventures, NVIDIA, Deutsche Telekom, RingCentral, HubSpot Ventures, NTT DOCOMO, LG.
- **Series D, Feb 2026:** $500M @ $11B - led by Sequoia; a16z 4x'd, ICONIQ 3x'd; new: Lightspeed, BOND, Evantic. Total raised ~$781M. IPO chatter.

## 3. Recent news/launches (last 6 months)

- **Nov 2025 - Inaugural ElevenLabs Summit:** Agents platform GA-class push - Scribe v2 Realtime (sub-150ms STT), Agent Coaching & Evaluation (feedback-driven improvement), no-code Native App Integrations, MCP tool-calling.
- **Feb 2026:** Series D + IPO signals.
- **Mar 25, 2026 - IBM partnership:** ElevenLabs voice into IBM watsonx agentic stack (enterprise reach).
- **Twilio native integration:** First-party connector for Programmable Voice <-> Agents - directly relevant to Chris.
- **11ai (alpha):** Voice-first assistant using MCP to act on Slack/tickets/etc.

## 4. Key people (LinkedIn search URLs)

- **Mati Staniszewski (CEO/co-founder):** https://www.linkedin.com/search/results/people/?keywords=Mati%20Staniszewski%20ElevenLabs
- **Piotr Dabkowski (CTO/co-founder):** https://www.linkedin.com/search/results/people/?keywords=Piotr%20Dabkowski%20ElevenLabs
- **Alexander (Alex) Holt - VP Engineering (leads enterprise eng / largest customers):** https://www.linkedin.com/search/results/people/?keywords=Alexander%20Holt%20ElevenLabs
- **Tim von Kanel - VP Backend Engineering:** https://www.linkedin.com/search/results/people/?keywords=Tim%20von%20Kanel%20ElevenLabs
- **Forward Deployed team (search):** https://www.linkedin.com/search/results/people/?keywords=%22Forward%20Deployed%22%20ElevenLabs

## 5. What "Forward Deployed Engineer" means at ElevenLabs

From the JD twin (`/forward-deployed-engineer-strategist`), the FDE blog post (`elevenlabs.io/blog/forward-deployed-engineers`), and the dedicated landing page (`elevenlabs.io/agents/forward-deployed-engineers`): this is the **Palantir FDE pattern** - Mati's own pedigree - now applied to enterprise voice agents. FDEs sit with the customer's eng + exec teams, identify use cases, design bespoke integrations, prototype, and own the implementation arc end-to-end (system design -> integration -> scaling -> change management -> compliance). The "Software Engineer" track skews more toward shipping production code on customer infra (vs the "Strategist" track which is heavier on discovery/account ownership). Expect: Python + TypeScript, Twilio/SIP plumbing, MCP tool wiring, latency tuning, demo-grade prototyping, and direct C-suite communication. The team's stated mandate is "launch enterprise AI agents that deliver value faster."

## 6. Comp signals

Levels.fyi shows ElevenLabs SWE base/TC clustered around $140k-$200k base for IC ranges, with US FDE roles industry-median ~$201k TC. ElevenLabs SF is late-stage AI infra at an $11B mark - expect SF FDE pay roughly **$180-230k base + $50-120k equity (Series D RSUs) + bonus**, total comp **$230k-$380k** depending on level. Strong upside on the equity given Sequoia-led D and IPO talk; ask for refresher cadence and strike-date timing. (Glassdoor data is thin; H1B filings show several Eleven Labs Inc. SWE roles in the $150-200k base band.)

## 7. What's likely to impress them

ElevenLabs FDE is built for engineers who can sit across the table from a Fortune 500 voice ops team and ship a working agent in days. Chris's stack maps cleanly:

- **crazy-caller (Twilio + Gemini Live, pure-TS audio codec, 30 voices, TDD)** is essentially a one-person reference implementation of what an ElevenLabs FDE delivers in week one - the Twilio <-> realtime-LLM <-> TTS loop is exactly the integration ElevenLabs sells via its Twilio native connector. The hand-rolled TS audio codec in particular is rare and signals he can debug at the PCM/mu-law/sample-rate layer where most FDEs hit walls.
- **V2V Intelligence (live SaaS, paying users, March 2026)** is 0->1 founder muscle: discovery, deployment, change management with real customers - the exact loop FDEs run, just for someone else's product.
- **25-tool MCP research platform + 55%->83% retrieval lift** speaks directly to ElevenLabs' MCP-driven Agents and the new Agent Coaching/Evaluation surface area; he's already shipped on the abstraction Eleven now bets on.
- **Live voice agent on Twilio Programmable Voice + Gemini Live** - he can swap Gemini for ElevenLabs Agents on day 1 and explain the latency/codec/turn-taking trade-offs in customer language.

Lead the conversation with: "I've built and shipped what your customers are trying to buy." Bring the crazy-caller demo on a phone in the room.

## Sources

- TechCrunch, CNBC, BusinessWire, IBM Newsroom, elevenlabs.io/careers + /blog + /agents, Levels.fyi, Wikipedia, TheOrg, Tracxn.
