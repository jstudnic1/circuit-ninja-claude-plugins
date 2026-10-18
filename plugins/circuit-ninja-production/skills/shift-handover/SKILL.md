---
name: shift-handover
description: Prepare or read the production shift handover at Circuit Ninja - today's shift plan, the last production days with their scrap and action notes, open tickets by station, recent bath changes and lab tests - and write the handover note for the production chat. Use for "handover", "předávka směny", "what happened on the line", "what should I watch today".
---

# Shift handover

The instructions for this skill live on the **Circuit Ninja** connector, so everyone follows the current version.

1. Call `Circuit Ninja:read_skill` with `name: "shift-handover"`.
2. Follow the instructions it returns. They replace this page.
3. If it says the skill is not available, tell the person why, then call `Circuit Ninja:suggest_skills` with one generic line about the work.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

- Change machine, bath or recipe settings, or tell the line to.
- Release, scrap or rework a lot, or sign off a safety item.
- Judge an operator: the note says what happened, not who failed.
- Anything on the company never-list (the `company-context` skill lists it).
