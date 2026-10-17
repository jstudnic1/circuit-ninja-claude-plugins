---
name: morning-brief
description: Start the working day at Circuit Ninja - one screen with what needs attention today. Combines the company twin's morning pulse (last production day, urgent tickets, materials to order, requests waiting, deadlines) with the person's own calendar for today and the e-mails waiting for their answer. Use for "brief me", "good morning", "what's on today", "co je dnes".
---

# Morning brief

The instructions for this skill live on the **Circuit Ninja** connector, so everyone follows the current version.

1. Call `Circuit Ninja:read_skill` with `name: "morning-brief"`.
2. Follow the instructions it returns. They replace this page.
3. If it says the skill is not available, tell the person why, then call `Circuit Ninja:suggest_skills` with one generic line about the work.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

- Send, accept or change anything in mail or calendar.
- Copy mail into the twin.
- Judge a colleague.
- Anything on the company never-list (the `company-context` skill lists it).
