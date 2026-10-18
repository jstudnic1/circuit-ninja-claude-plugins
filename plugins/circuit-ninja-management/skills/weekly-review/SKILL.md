---
name: weekly-review
description: Prepare Circuit Ninja's weekly review meeting - KPIs against the previous window, production by week, purchase spend by job family, tickets raised, overdue safety measures and sales tasks - as an agenda with the three decisions for this week. Use for "weekly review", "týdenní porada", "Monday meeting", "how was the week".
---

# Weekly review

The instructions for this skill live on the **Circuit Ninja** connector, so everyone follows the current version.

1. Call `Circuit Ninja:read_skill` with `name: "weekly-review"`.
2. Follow the instructions it returns. They replace this page.
3. If it says the skill is not available, tell the person why, then call `Circuit Ninja:suggest_skills` with one generic line about the work.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

- Decide for the meeting: the three decisions are proposals.
- Rank or judge individuals.
- Change budgets or plans.
- Anything on the company never-list (the `company-context` skill lists it).
