# Security and data handling

- **Isolation per brand.** Each brand has its own cloud project, database and secret store. Agents act through per-brand service accounts, so one brand's agents cannot reach another brand's data.
- **Least privilege.** Each agent has an allow-list of the data it may write. Anything not on the list is refused by the platform, not by the prompt.
- **Human approval.** Outward actions (sending, publishing, launching, spending) require a person's approval unless the brand has explicitly turned that loop on.
- **Mail stays in the mailbox.** Message bodies are read in place and are not copied into a database.
- **Audit and undo.** Every action is logged with who approved it, and can be reversed. Every connection can be revoked by the brand.
- **Claims gate.** Customer-facing statements are checked against their sources before they ship.
- **Patterns, never your data.** Deliberate improves its playbooks from what works, but one brand's data is never shown to or used in another brand's work.

Questions: see [deliberatestudio.com](https://deliberatestudio.com).
