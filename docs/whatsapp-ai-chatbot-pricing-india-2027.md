---
title: "WhatsApp AI Chatbot Pricing in India 2027: What You Actually Pay"
description: "A plain-English breakdown of what a WhatsApp AI chatbot costs in India in 2027 — the three separate fees, a worked monthly example, the five things that move your bill, and the quote red flags."
---

# WhatsApp AI Chatbot Pricing in India 2027

**Short answer:** a WhatsApp AI chatbot in India is billed as three separate things — a platform fee (roughly ₹0–₹3,000/month for an SMB, sometimes a one-time setup instead), Meta's per-conversation fee, and model/AI usage — so any single "₹X per month" number you are quoted is only a third of the answer. Ask for all three, at your own volume, in writing.

If you are planning your 2027 stack now, the useful thing is not a price list. Vendor prices move every few months and this page would be wrong by the time you read it. The useful thing is knowing *what the bill is made of*, so a quote either adds up or it does not.

## The three line items

| Line item | Who charges it | How it scales | What people get wrong |
| --- | --- | --- | --- |
| **Platform / software fee** | The tool or agency | Flat per month, or per agent, or per user seat | They assume it covers message costs. It does not. |
| **Meta conversation fee** | Meta, via your WhatsApp Business account | Per 24-hour conversation or per template message, billed in USD, moved with the rupee | They budget for month one and get surprised in month two when volume grows. |
| **AI / model usage** | Your model provider, or bundled by the platform | Per token or per reply — invisible until someone forwards 4,000 messages | They never ask if AI usage is capped, and it is not. |

There is often a fourth: **one-time build or setup**. A pure BSP tool is self-serve and cheap to start. A configured agent or a custom build has a setup cost and then a smaller monthly. Those are different products and they should not be compared on the monthly number alone.

## A worked monthly example

Assumptions, stated so you can change them: 2,000 customer conversations a month, 500 of them marketing templates (you started the conversation), 1,500 service conversations inside the 24-hour window, an AI agent replying to most of them, one number.

- **Platform:** a mid-range configured agent, ₹2,000–₹3,000/month.
- **Meta:** service conversations started by the customer are the cheap end; template/marketing messages are the expensive end by roughly five to seven times. Small numbers per message, but 500 of them is a real line.
- **AI usage:** depends entirely on reply length and how much context the agent carries. This is the line nobody quotes and the one that grows with success.

Change any one assumption and the total moves more than most people expect. That is why a vendor quoting a flat number without asking your volume is guessing.

## The five things that move your bill

1. **Who starts the conversation.** Customer-initiated (service) is far cheaper than you-initiated (marketing template). Broadcast-heavy use is a different cost shape from inbound support.
2. **Language and code-mixing.** Hinglish, Marathi, Tamil replies cost more tokens than clipped English. Worth it; just know it.
3. **Memory.** An agent that remembers a customer's budget across weeks is carrying more context into every reply. Memory is a feature *and* a line item.
4. **Integrations.** CRM sync, calendar booking and payment links mean more tool calls, and tool calls are billed like text.
5. **Retries and fallbacks.** An agent that re-asks, re-tries or escalates is doing more work than one that answers once.

## Red flags in a quote

- One number, no volume question. They have not modelled your usage.
- "Unlimited messages." Nobody can sell Meta's fee as unlimited; check whether it means *platform* messages only.
- No answer on what happens at 3× your current volume. The bill is not the number, the curve is.
- A per-seat price for a chatbot. Seats matter for humans reading transcripts, not for the agent.
- No mention of who owns the number, the WABA and the prompt library if you leave. That is the expensive part of switching.

## Who should *not* pay for one

- Under ~30 genuine enquiries a month: a saved-replies catalogue and one attentive human cost less and answer better.
- If your prices are not written down in one place, an agent will confidently quote the wrong one — fix the source of truth first, then automate.
- If nobody will read the first 100 transcripts, you are paying for a system that repeats its own mistakes quietly.

## What the cheapest legitimate path looks like

Month 1: official Cloud API number, a small configured agent on the FAQ set, every conversation handing over to a human. Pay the middle amount, measure deflection and reply time. Month 2: add the two flows you actually saw in transcripts, nothing else. Month 3: only then decide if a custom build is worth it. Most Indian SMBs never need to leave step 2, and the ones who do know exactly why.

## FAQ

**Is there a free way to do this?** The WhatsApp Cloud API has a free tier for a limited number of service conversations a month, and some platforms charge nothing at low volume. Free gets you the channel, not the agent — the AI usage and the setup work are still yours.

**Why is the marketing message so much more expensive than the reply?** Because you are buying the right to start a conversation. Meta prices that higher to keep the channel from becoming a bulk SMS pipe. Use templates for genuine follow-ups, not for re-sending your catalogue.

**Should I pay an agency or a tool?** Tool: cheaper, faster, you configure it. Agency: more money, someone else writes the flows and you inherit their decisions. Pay an agency only when you can answer "what do I keep if I stop working with you".

**Is GST extra?** Indian vendors quote both ways. Ask whether the number is inclusive or exclusive, and whether Meta's USD charges are passed through at cost.

**What will it cost in 2027?** Nobody can tell you Meta's 2027 rate card, and anyone who does is guessing. Structure aside, budget for the platform fee to stay flat and the message + AI lines to track your volume.

---

*Written by the team at [Innovators AI Hub](https://innovatorsaihub.com/?utm_source=github&utm_medium=parasite&utm_campaign=2027-whatsapp-pricing). We build WhatsApp and LinkedIn AI agents for Indian businesses. If you want the one-page quote checklist we use — the three fees above, plus the ten questions that turn a vendor's number into a comparable one — it is free and needs no call: [get the checklist](https://innovatorsaihub.com/?utm_source=github&utm_medium=parasite&utm_campaign=2027-whatsapp-pricing-checklist).*
