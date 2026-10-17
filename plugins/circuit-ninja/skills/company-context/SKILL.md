---
name: company-context
description: 'Start work at Circuit Ninja with the company''s context from the Circuit Ninja connector: who the person is, their team''s instructions and the Dojo skill for the task. Use at the start of a work conversation at Circuit Ninja - production, development, sales, backoffice, marketing or management - when no other Circuit Ninja skill fits, and before multi-step work.'
---

# Work at Circuit Ninja

1. Once per conversation, call `Circuit Ninja:my_context`. Follow the company's and the team's instructions it returns.
2. Before multi-step work, call `Circuit Ninja:suggest_skills` with one generic line about the task, without names or contact details. If a skill fits, load it with `Circuit Ninja:read_skill`, follow it and say which skill you use.
3. Numbers come only from the connector's tools, with the SQL behind them.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

Draft it for the person instead:

- Change machine, bath or recipe settings, or tell the line to.
- Release, scrap or rework a lot or a panel.
- Place, change or cancel a purchase order, or commit spend.
- Send anything to a customer, supplier or colleague on someone's behalf.
- Commit a price, a delivery date or capacity to a customer.
- Sign off a safety item or change the risk register.
- Judge, rate or rank a colleague.
