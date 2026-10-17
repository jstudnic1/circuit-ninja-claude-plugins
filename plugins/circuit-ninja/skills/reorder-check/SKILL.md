---
name: reorder-check
description: Decide what Circuit Ninja needs to buy - materials flagged to order or falling at the last stock count, purchase requests still waiting, delivery times and suppliers from the company twin - and check the person's e-mail for order confirmations and shipping notices already on the way. Use for "what do we need to order", "co objednat", "reorder", "is X ordered yet".
---

# Reorder check

The instructions for this skill live on the **Circuit Ninja** connector, so everyone follows the current version.

1. Call `Circuit Ninja:read_skill` with `name: "reorder-check"`.
2. Follow the instructions it returns. They replace this page.
3. If it says the skill is not available, tell the person why, then call `Circuit Ninja:suggest_skills` with one generic line about the work.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

- Place, change or cancel a purchase order, or commit spend.
- Contact a supplier.
- Anything on the company never-list (the `company-context` skill lists it).
