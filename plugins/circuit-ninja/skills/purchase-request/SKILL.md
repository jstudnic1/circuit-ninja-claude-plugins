---
name: purchase-request
description: Help a colleague buy something Circuit Ninja pays for - fill in the "Nákupčí" purchase request form right the first time (a new request for the buyer, or an express purchase already ordered or paid by card or own money), with what exactly, how many, the product link, for whom and the cost code it is booked to (a cost centre, or the machine it is for). Needs no company data. Use for "jak zadat nákupní požadavek", "nákupní požadavek", "potřebuji koupit", "zadat nákup", "koupil jsem to kartou", "expresní nákup", "na jaké středisko to dát", "purchase request", "I need to buy", "I paid with the company card".
---

# Purchase request

The instructions for this skill live on the **Circuit Ninja** connector, so everyone follows the current version.

1. Call `Circuit Ninja:read_skill` with `name: "purchase-request"`.
2. Follow the instructions it returns. They replace this page.
3. If it says the skill is not available, tell the person why, then call `Circuit Ninja:suggest_skills` with one generic line about the work.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

- Submit the form, order, pay, or contact a shop or supplier for the person: they send the request, the buyer orders.
- Use or repeat a login or password from any sheet (some supplier sheets still hold them).
- Put the person's phone number, card details or other personal data into the note or a summary.
- Anything on the company never-list (the `company-context` skill lists it).
