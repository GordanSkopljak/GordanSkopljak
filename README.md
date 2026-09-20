# Gordan Skopljak

I build AI automation that holds up in production, and audit it against EU regulation.

Based in Hamburg. n8n, LangChain, Python.

---

## What I do

I work in the gap between the people who want an AI system and the people who build it. That means taking a problem from a first conversation through to a working system, then answering the questions that decide whether it ships: what does it cost, what breaks, is it legal, and is it actually worth doing.

Every project here was taken end to end. Problem definition, working build, compliance assessment, business case, and a recommendation the client could act on.

## Start here

| Project | What it is |
|---|---|
| [airline-disruption-care-platform](https://github.com/GordanSkopljak/airline-disruption-care-platform) | Three connected n8n workflows for overnight flight cancellations. Costs the night, ranks hotel options, captures what was agreed on the phone. Built against 3,305 real care events from 10,919 US DOT cancellations. Ships with EU AI Act classification, GDPR documentation, a DPIA, ROI with sensitivity analysis, and a written list of what it cannot do. |
| [stups-suggestion-agent](https://github.com/GordanSkopljak/stups-suggestion-agent) | A scheduled agent that reads live weather, branches indoor or outdoor, pulls what is on in Hamburg tonight, and sends two suggestions to Telegram. No human in the loop from trigger to delivery. |
| LLM evaluation pipeline | An OpenAI model extracts, an independent DeepSeek model judges. Four evaluation methods. When scores hit a ceiling I hardened the dataset rather than tuning the metric. |
| Gonelu | Retrieval over a curated voice corpus, built by three people in a two day window. Two retrieval approaches compared, provider fallback so one outage cannot take the product down. |

## How I work

**The model never calculates money.** In the disruption platform, the model extracts and writes prose. Every number that decides spend is computed in deterministic code, and a human gates every commitment. That is not a safety feature bolted on at the end, it is the architecture, and it is the direct answer to a client who says AI is not transparent.

**Compliance from the first design decision.** EU AI Act classification and GDPR are cheap when they shape the data flow and expensive when they are audited into a finished system. When a third workflow broke the privacy argument the first two rested on, I wrote a separate addendum arguing it on different grounds rather than quietly weakening the original pack.

**Limitations are stated, not discovered.** Every repo here lists what does not work. A broken webhook, a simulated dispatch, an unverified cost assumption. If you find a problem I did not write down, tell me, because that is the one that matters.

**I will recommend against spending.** The disruption platform's final recommendation to the client was not to fund the integration. Fund an eight week pilot across three stations first, because the entire business case rests on one assumption nobody has measured. The software costs around 140 dollars a year to run. The risk was never the software.

## Nine years of delivery, nine weeks of building

I spent nine years running delivery in technology and operations before any of this. In summer 2026 I started an intensive AI consulting programme, and the repositories here are the full record of it, including the early ones named things like `Day-1` and `Day-3`. I have left them exactly as they were.

What that record shows is not that I became a machine learning engineer. It shows that I can go from knowing nothing about a domain to shipping working systems in it, with the documentation a client would need, in a short time. That has been the job in every role I have held.

## What I am not

I do not train models and I am not an ML researcher. I connect models to a business process, make the result explainable, work out whether it was worth doing, and say so honestly when it was not.

## Get in touch

gordan.skopljak@gmail.com | [LinkedIn](https://www.linkedin.com/in/gordan-skopljak/)

Open to AI automation and delivery roles in Germany.
