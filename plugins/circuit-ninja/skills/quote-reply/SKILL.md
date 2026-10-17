---
name: quote-reply
description: Prepare the answer to a PCB quote request at Circuit Ninja - read the customer's e-mail, extract the board specs, check them against what the line can make, pull pricing inputs (competitor prices per dm2, our cost per panel) from the company twin and write a reply for the salesperson to finish and send. Use for "quote request", "poptávka", "nabídka", "how much would we charge for ...".
---

# Quote reply

The instructions for this skill live on the **Circuit Ninja** connector, so everyone follows the current version.

1. Call `Circuit Ninja:read_skill` with `name: "quote-reply"`.
2. Follow the instructions it returns. They replace this page.
3. If it says the skill is not available, tell the person why, then call `Circuit Ninja:suggest_skills` with one generic line about the work.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

- Send the quote, or commit a price, a delivery date or capacity - the salesperson finishes and sends it.
- Claim a capability the line does not have.
- Show the customer our costs or competitors' prices.
- Anything on the company never-list (the `company-context` skill lists it).
