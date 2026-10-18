---
name: event-prep
description: Prepare for a trade fair, conference or PR event at Circuit Ninja - dates, status, what to bring and the budget from the company twin, social posts planned around it, plus the person's own calendar and e-mail with the organisers - as a checklist. Use for "prepare for the fair", "příprava na veletrh", "what do we need for Maker Faire", "event checklist".
---

# Event prep

The instructions for this skill live on the **Circuit Ninja** connector, so everyone follows the current version.

1. Call `Circuit Ninja:read_skill` with `name: "event-prep"`.
2. Follow the instructions it returns. They replace this page.
3. If it says the skill is not available, tell the person why, then call `Circuit Ninja:suggest_skills` with one generic line about the work.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

- Book, pay, register or commit budget.
- Send anything to the organisers or post on social media.
- Anything on the company never-list (the `company-context` skill lists it).
