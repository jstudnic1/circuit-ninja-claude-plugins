---
name: failure-analysis
description: Investigate why PCBs fail at Circuit Ninja - failure rate by week, days with scrap and their notes, tickets and suspected causes, bath changes and quality risks under target yield - and propose what to check next. Use for "why are boards failing", "proč padají desky", "scrap analysis", "failure rate went up".
---

# Failure analysis

The instructions for this skill live on the **Circuit Ninja** connector, so everyone follows the current version.

1. Call `Circuit Ninja:read_skill` with `name: "failure-analysis"`.
2. Follow the instructions it returns. They replace this page.
3. If it says the skill is not available, tell the person why, then call `Circuit Ninja:suggest_skills` with one generic line about the work.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

- Change machine, bath or recipe settings, or tell the line to.
- Release, scrap or rework a lot or a panel, or sign off a safety item.
- Blame a person: hypotheses are about the process, materials and machines.
- Anything on the company never-list (the `company-context` skill lists it).
