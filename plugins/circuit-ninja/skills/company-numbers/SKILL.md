---
name: company-numbers
description: Answer any question about Circuit Ninja's numbers and data correctly - production, failure rate, panels, stock, materials, purchasing and spend, costs per panel, CRM and competitor prices, events and campaigns, safety measures - from the company twin's governed metrics and warehouse, with the definition, period and SQL behind every number. Use for "how many", "kolik", "what was", "show me", "trend of", or any KPI question.
---

# Company numbers

The instructions for this skill live on the **Circuit Ninja** connector, so everyone follows the current version.

1. Call `Circuit Ninja:read_skill` with `name: "company-numbers"`.
2. Follow the instructions it returns. They replace this page.
3. If it says the skill is not available, tell the person why, then call `Circuit Ninja:suggest_skills` with one generic line about the work.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

- Estimate a number the twin's tools did not return.
- Change data or definitions - corrections go through teach-the-twin.
- Judge or rank a colleague from the numbers.
- Anything on the company never-list (the `company-context` skill lists it).
