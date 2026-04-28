# Deepgram — Company Brief

**Date:** 2026-04-27 | **For:** Chris Combs | **Roles in play:** FDE, Deepgram for Restaurants (SF) + Solutions Architect (US Remote, EST/PST)

---

## 1. Company Snapshot

Deepgram builds **foundational voice AI infrastructure**: real-time Speech-to-Text (Nova-3), Text-to-Speech (Aura/Aura-2), and a unified **Voice Agent API** (STT + LLM + TTS in one voice-to-voice interface). Founded **2015** by three University of Michigan physicists (Scott Stephenson, Adam Sypniewski, Noah Shutty) who pivoted from dark-matter waveform analysis. **HQ:** 548 Market Street, San Francisco; Ann Arbor, MI office; remote staff across 20+ states / 6 continents. **Headcount:** ~210–260 (Jan 2026, growing fast post-Series C). **Scale:** 200,000+ developers, 1,300+ enterprise customers.

## 2. Funding Trajectory

- **Series C: $130M at $1.3B valuation, Jan 13, 2026** (now a unicorn). Led by **AVP**; existing backers Madrona, Tiger, Wing, YC, Alkeon, In-Q-Tel, BlackRock; new strategics: **Twilio**, **ServiceNow Ventures**, **SAP**, **Citi Ventures**.
- Use of funds: global expansion, multi-language, **restaurants vertical**, OfOne acquisition. Total raised ~$200M+. Profitability not disclosed; aggressive FDE/SA hiring is the signal.

## 3. Recent Launches (last 6 months)

- **Voice Agent API GA** — voice-to-voice unified API replacing the old "stitch STT+LLM+TTS" pattern. Direct competitor to OpenAI Realtime, ElevenLabs Conversational, Vapi.
- **Nova-3 STT** — 54.2% WER reduction streaming, 47.4% batch vs. competitors. First model with self-serve vocab customization (no retraining). Real-time multilingual.
- **Aura-2 TTS** — sub-250ms response, conversational voices, paired with Voice Agent API.
- **Deepgram for Restaurants (Jan 2026)** — anchored on the **OfOne acquisition** (YC, drive-thru voice AI). OfOne shipped 95%+ containment for national QSR brands. Target: drive-thru, noisy multi-speaker ordering.
- **Series C strategic partnerships:** Twilio (carrier/infra), ServiceNow, SAP, Citi.

## 4. Key People (LinkedIn search URLs)

LinkedIn search format: `https://www.linkedin.com/search/results/people/?keywords={NAME}%20Deepgram`

- **Scott Stephenson** — CEO & Co-founder
- **Adam Sypniewski** — CTO & Co-founder
- **Shadi Baqleh** — COO
- **Kris Efland** — VP Engineering
- **Natalie Rutgers** — VP Product
- **Ralphette English** — VP Customer Success (likely owns SA org)
- **Chris Dyer** — VP Sales
- **Andrew Seagraves** — VP Research
- **Anoop Dawar** — Chief Strategy Officer

For FDE-Restaurants, also search "OfOne Deepgram" — acquired founder is likely hiring manager.

## 5. The Two Roles Compared

| Dimension | FDE, Deepgram for Restaurants (SF) | Solutions Architect (Remote EST/PST) |
|-----------|-----------------------------------|--------------------------------------|
| **Phase** | Zero-to-one in a brand-new vertical (post-acquisition) | Post-sales architecture across enterprise book |
| **Customers** | National QSR / drive-thru chains | Cross-vertical (contact center, conv-AI, vertical SaaS) |
| **Day-to-day** | Embed with customer, deploy in noisy multi-speaker prod, write code, codify playbooks | Architecture sessions, Tier-3 escalations, pre-sales credibility, roadmap feedback |
| **Coding** | High — adapt platform to real-world constraints | Medium — POCs, integrations, debugging |
| **Travel** | On-site at restaurant locations likely | Mostly remote |
| **Career signal** | Founding-engineer-of-a-vertical leverage | Steady senior IC, broader exposure |

**Better fit for Chris:** **FDE-Restaurants.** (1) You already shipped a working voice-agent SaaS solo (V2V Intelligence + crazy-caller) — exactly the zero-to-one lift this role demands; (2) "embed, write code, codify playbooks" maps to your founder muscle; (3) restaurants is a new pod with an acquired team — you'd define patterns, not inherit them. SA is the safer fallback. Apply to both; lead with FDE energy.

## 6. Comp Signals

- **Solutions Architect (SF):** $165K–$220K base (Levels.fyi posting). Levels' $139K median figure is older/junior data.
- **Software Engineer:** $210K–$276K total comp; median ~$266K.
- **FDE benchmark:** No Deepgram-specific FDE data. Cross-company FDE median $163K; Palantir FDE band $171K–$415K (median $215K). Deepgram FDE likely **$180K–$260K base + 0.05–0.20% equity** at Series C unicorn stage; SF role toward upper end.
- **Glassdoor:** Comp/benefits 4.5/5; interview difficulty 3.12/5.
- **Negotiation lever:** Series C just closed → equity priced at $1.3B post; ask for refresh language and ratchet on FDE-Restaurants given new-vertical risk premium.

## 7. What Will Impress Them

Chris's portfolio reads like a Deepgram FDE résumé in three artifacts:

- **crazy-caller (Twilio + Gemini Live, pure-TS audio codec, 30 voices, TDD)** — exactly the stack Deepgram's Voice Agent API competes with, and Twilio just joined as a Series C strategic investor. A working μ-law codec and bidirectional audio pipeline in TS proves you can debug what most candidates only diagram.
- **V2V Intelligence (live SaaS, March 2026, Twilio Programmable Voice + Gemini Live in production)** — solo founder shipping a real voice agent to paying users is the cleanest signal for FDE-Restaurants: zero-to-one customer deployment on a noisy real-world telephony channel.
- **25-tool MCP research platform + 55%→83% retrieval lift** — proves multi-API integration and measurable accuracy gains. Drive-thru voice AI lives or dies on order accuracy and containment; you've shown you can move the metric.

**Pitch:** "I built and shipped what your customers are trying to buy. I've debugged Twilio Programmable Voice in prod, written my own audio codec, integrated a real-time voice LLM, and lifted retrieval accuracy on a multi-tool agent. I want to do that for your QSR customers as your first FDE on the restaurants pod." Bring the crazy-caller repo and a 60-second V2V demo to the screen.

**Risk to defuse:** Solo-founder background can read as "won't take direction." Counter with a story about codifying a reusable playbook — the patterns-library angle the FDE JD explicitly calls out.

---

*Sources: Deepgram press release / about / leadership pages; TechCrunch; Levels.fyi; Glassdoor; SiliconANGLE; Built In SF; Pitchbook/Crunchbase summaries; aijobs.com FDE listing.*
