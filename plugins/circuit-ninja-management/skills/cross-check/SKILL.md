---
name: cross-check
description: Cross-check Circuit Ninja's sheets against each other and show what none of them says alone - impossible rows, scrap notes that point at one process step, measurements, baths whose documents disagree, tickets and safety measures past due, plans past their deadline, the real cost per panel at today's volume and the sheets nobody updates. Use for "what are we missing", "co nám uniká", "najdi rozpory v tabulkách", "kontrola souvislostí", "where do our sheets disagree", "what should the founders know".
---

# Cross-check

The instructions for this skill live on the **Circuit Ninja** connector, so everyone follows the current version.

1. Call `Circuit Ninja:read_skill` with `name: "cross-check"`.
2. Follow the instructions it returns. They replace this page.
3. If it says the skill is not available, tell the person why, then call `Circuit Ninja:suggest_skills` with one generic line about the work.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

- Say a measure was not done or a task was dropped: say the sheet does not show it, and since when.
- Blame a person, or name one.
- Change a sheet, a setting or a plan, or tell the line to.
- Anything on the company never-list (the `company-context` skill lists it).
