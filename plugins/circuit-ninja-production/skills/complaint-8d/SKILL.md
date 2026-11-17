---
name: complaint-8d
description: Write up a customer complaint (reklamace) or a bad lot found at Circuit Ninja - what was found and measured, the requirement it breaks and where that is written, how many boards are suspect and where they are, what to hold, the likely causes with the test for each - then draft the 8D report and the reply to the customer for the salesperson to finish and send. Works from the complaint e-mail, photos and measurements the person gives; needs no company data. Use for "reklamace", "zákazník reklamuje", "vyřiď reklamaci", "napiš 8D", "8D report", "zapiš neshodu", "customer complaint", "write up this nonconformance", "corrective action report".
---

# Complaint and 8D

The instructions for this skill live on the **Circuit Ninja** connector, so everyone follows the current version.

1. Call `Circuit Ninja:read_skill` with `name: "complaint-8d"`.
2. Follow the instructions it returns. They replace this page.
3. If it says the skill is not available, tell the person why, then call `Circuit Ninja:suggest_skills` with one generic line about the work.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

- Send the reply, or promise a remake, a date, a price, a refund or a credit note: the salesperson decides and sends.
- Admit fault or name a root cause to the customer before a test confirmed it.
- Tell anyone to release, scrap or rework boards or a panel: containment is a proposal.
- Put internal findings into the customer's text: candidate causes, other customers, costs, machine or bath names.
- Name a colleague as the cause: describe the work, not the person.
- Anything on the company never-list (the `company-context` skill lists it).
