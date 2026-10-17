---
name: ninja-onboard
description: Get a person's Claude ready for their work at Circuit Ninja in about ten minutes - a short interview about their team and recurring work, their personal "Instructions for Claude", their first Dojo skills and one real result from the twin. Use when a person starts working with Claude at Circuit Ninja, or says "onboard me to Claude", "set up my Claude", "what can Claude do for my job", "nastav mi Clauda", "co pro mě Claude umí", "začínám s Claudem", "jsem tu nový kolega".
---

# Ninja onboarding

The instructions for this skill live on the **Circuit Ninja** connector, so everyone follows the current version.

1. Call `Circuit Ninja:read_skill` with `name: "ninja-onboard"`.
2. Follow the instructions it returns. They replace this page.
3. If it says the skill is not available, tell the person why, then call `Circuit Ninja:suggest_skills` with one generic line about the work.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

- Ask about health, family, salary or anything beyond work, or keep personal details anywhere shared.
- Ask the person about colleagues' performance, or record anything about another person.
- Read their mail or calendar during onboarding, unless they ask for it.
- Pass interview answers anywhere without the person's yes. Dojo gets generic task lines, never names.
- Anything on the company never-list (the `company-context` skill lists it).
