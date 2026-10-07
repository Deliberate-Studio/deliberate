# Deliberate

Deliberate is an AI agent team for consumer brands. Eleven named agents share one memory of the business and run its day-to-day work: ads and creative, creators, email, customer support, finance and operations. They read the brand's own data every day, propose work with the evidence attached, and carry it out once a person approves.

This repository explains how Deliberate works, for the people evaluating it and for the AI agents that read about it. The platform itself is closed source.

- Website: <https://deliberatestudio.com>
- Agent-readable summary: [`llms.txt`](llms.txt)

## The idea

The same team can run a much bigger business. Growing a consumer brand used to mean another hire, another agency, or another gap left open. Deliberate gives the team a brand already has a full bench of agents: they carry the daily load, and people set direction, make the calls, and do the work only people can do.

## The team

| Agent | Job |
| --- | --- |
| Zelda | Paid media and creative: turns what customers say into ranked angles and finished ads, then manages spend |
| Anni | Email and retention: campaigns, lifecycle flows and SMS in the brand's voice |
| Louisa | Customer support and insights: answers tickets and turns reviews, surveys and support into patterns |
| Zora | Creators: applications, gifting, usage rights and partnership ads |
| Eliza | Assistant and PM: the morning brief, inbox, calendar and follow-ups |
| Waldo | Operations: orders, fulfillment and inventory, flagged before customers notice |
| Maggie | Finance: landed cost, margin by SKU and a P&L that doesn't wait for month-end |
| C.J. | Amazon: listing health, reviews and marketplace numbers |
| Aaron | Wholesale: order forms, line sheets and invoices |
| Mariah | The website: tests the site like a customer, runs experiments and ships fixes |
| Lucretia | People ops: the paperwork and process |

Every agent reads the same memory. A librarian agent, Dorothy, keeps the brand's research current, so an answer starts from the latest finding rather than the oldest one.

## How it works

1. **Read.** Connect the brand's stack (Shopify, Meta, Klaviyo, Gorgias, Gmail, Slack, the books and more). The agents build one living picture of the business.
2. **Propose.** Drafts, briefs, budget moves and flags arrive with the evidence attached.
3. **You decide.** Approve, redirect or ignore. Nothing outward ships without a person's decision.
4. **Execute.** The agents carry it out: the send, the ad, the reply.
5. **Learn.** Results become guidance the whole team follows next time.

The interface is one chat. Ask in plain words, and the work comes back as something you can see, with one decision attached. See [docs/how-it-works.md](docs/how-it-works.md).

## Trust and safety

- **One locked room per brand.** Each brand runs in its own isolated environment with its own keys. One brand's agents can never see another brand's data.
- **Allow-listed by design.** Every agent has an explicit list of what it may touch; the platform refuses everything else.
- **Approval before anything outward.** Ads launch paused until a person turns them on. Sends, replies and budget changes wait for approval unless the brand has turned that loop on.
- **Claims are checked.** Customer-facing copy is checked against its sources, and anything an agent can't source is blocked.
- **Everything is logged** and can be undone or revoked.

More in [docs/security.md](docs/security.md).

## Where it works

The Deliberate app, Slack and Gmail, plus inside Claude, ChatGPT and Grok through Deliberate's MCP connector. See [docs/mcp-connector.md](docs/mcp-connector.md).

## Pricing

Brands hire the agents they need, month to month, with no annual contract and never a cut of sales or ad spend. Usage-based credits, billed through the Shopify App, are coming soon. Current pricing is on [deliberatestudio.com](https://deliberatestudio.com).

## Proof

Deliberate runs Loftie, the sleep-wellness brand behind the Loftie Clock (New York Times Wirecutter's best alarm clock six years running). Loftie replaced Siena with Deliberate.

## Contact

Matt Hassett, founder: [deliberatestudio.com](https://deliberatestudio.com)
