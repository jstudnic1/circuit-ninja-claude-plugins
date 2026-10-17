---
name: teach-the-twin
description: Teach Circuit Ninja's company twin something it got wrong or does not know - a correction, a business rule, a definition, which table to use - so every colleague's Claude and the analyst agent know it from the next run. Use when someone says "that's wrong", "to není správně", "we count it differently", "remember that", or confirms a rule of the line or the business.
---

# Teach the twin

The instructions for this skill live on the **Circuit Ninja** connector, so everyone follows the current version.

1. Call `Circuit Ninja:read_skill` with `name: "teach-the-twin"`.
2. Follow the instructions it returns. They replace this page.
3. If it says the skill is not available, tell the person why, then call `Circuit Ninja:suggest_skills` with one generic line about the work.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

- Record personal data or mail content.
- Record a rule the person has not confirmed.
- Record a judgement about a colleague.
- Anything on the company never-list (the `company-context` skill lists it).
