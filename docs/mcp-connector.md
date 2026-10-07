# Using Deliberate from Claude, ChatGPT or Grok

Deliberate exposes each brand's agent team through an MCP (Model Context Protocol) connector, so you can ask your whole team questions from inside the assistant you already use. Answers are grounded in the brand's real numbers and research.

## What you can do

| Tool | What it does |
| --- | --- |
| `ask` | Ask the agent team anything about the business; the right agent answers. |
| `get_metrics` | Revenue, spend, MER and CAC over a window. |
| `get_ad_performance` | Meta and other channel performance. |
| `finance_snapshot` | P&L snapshot. |
| `unit_economics` | Subscription LTV and retention. |
| `get_order_health` | Shopify operations health. |
| `sales_summary` | Units, net sales and orders by product, channel or country. |
| `get_inventory` | Stock and reorder needs. |
| `cx_themes` | Support themes. |
| `voice_of_customer` | Surveys, reviews and NPS. |
| `query_research`, `get_research` | Search and read the brand's research library. |
| `search_context`, `get_context`, `save_context` | Read and file decisions, briefs and meeting notes for the agents. |
| `get_marketing_calendar`, `save_calendar_entry` | The shared marketing calendar. |
| `draft_cs_reply`, `draft_readout` | Drafts for a person to review. |

Tools that change anything are limited to what the brand allows, and assistants like ChatGPT and Grok connect read-and-draft only.

## Connecting

- **Claude and ChatGPT** connect with a standard sign-in (OAuth). The brand's admin enables the assistant in Deliberate's settings, then adds the connector in the assistant.
- **Grok Bot** connects with a server URL and a token generated in Deliberate's settings.

Ask your Deliberate contact or visit [deliberatestudio.com](https://deliberatestudio.com) to set it up.
