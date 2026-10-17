---
name: inbox-follow-ups
description: Turn the person's recent Circuit Ninja e-mail into a follow-up list - what customers, suppliers, partners and event organisers asked or are waiting for, what was promised and by when - enriched with facts from the company twin (CRM stage, open purchase requests, materials, events). Use for "what am I waiting on", "follow-ups", "co mi visí v mailu", "inbox zero", end-of-week clean-up.
---

# Inbox follow-ups

The instructions for this skill live on the **Circuit Ninja** connector, so everyone follows the current version.

1. Call `Circuit Ninja:read_skill` with `name: "inbox-follow-ups"`.
2. Follow the instructions it returns. They replace this page.
3. If it says the skill is not available, tell the person why, then call `Circuit Ninja:suggest_skills` with one generic line about the work.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

- Send, draft into, archive or label mail.
- Copy mail content into the twin.
- Rank colleagues by how fast they answer.
- Anything on the company never-list (the `company-context` skill lists it).
