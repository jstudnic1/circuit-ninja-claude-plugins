---
name: company-brief
description: Everything Circuit Ninja knows about one company before a call, a meeting or a reply - the CRM record and price quotes from the company twin, plus the person's own e-mail threads and meetings with them. Use for "brief me on Gatema", "who is this company", "co víme o firmě", before a sales call or when a new e-mail arrives from a company.
---

# Company brief

The instructions for this skill live on the **Circuit Ninja** connector, so everyone follows the current version.

1. Call `Circuit Ninja:read_skill` with `name: "company-brief"`.
2. Follow the instructions it returns. They replace this page.
3. If it says the skill is not available, tell the person why, then call `Circuit Ninja:suggest_skills` with one generic line about the work.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

- Send anything to the company, or share our prices, costs or terms with them.
- Copy anything from the person's mail into the twin (`Circuit Ninja:record_learning`).
- Anything on the company never-list (the `company-context` skill lists it).
