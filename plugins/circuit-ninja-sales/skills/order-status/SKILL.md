---
name: order-status
description: Answer where a Circuit Ninja order is and what needs attention in the order pipeline - one order by its number (e.g. 000123L) or a customer, orders at risk of missing the 24-hour promise, orders waiting for approval or payment, what ships today, drafts worth a follow-up. Use for "where is order 000123L", "co je s objednávkou", "what's late", "what ships today", "which orders are stuck".
---

# Order status

The instructions for this skill live on the **Circuit Ninja** connector, so everyone follows the current version.

1. Call `Circuit Ninja:read_skill` with `name: "order-status"`.
2. Follow the instructions it returns. They replace this page.
3. If it says the skill is not available, tell the person why, then call `Circuit Ninja:suggest_skills` with one generic line about the work.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

- Promise a delivery date or a price to a customer.
- Change an order's status.
- Send the reply - the person checks and sends it.
- Anything on the company never-list (the `company-context` skill lists it).
