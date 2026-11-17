---
name: supplier-rfq
description: Ask suppliers for prices on a material, a part or a service for Circuit Ninja and compare what comes back - one request with the exact specification, the quantities, the date needed and a fixed answer format so the offers can be compared, an e-mail draft per supplier for the buyer to send, then the returned offers in one table with what each left out and a recommendation. The buyer decides. Works from what the person gives and their own mail; needs no company data. Use for "poptej dodavatele", "oslovit dodavatele", "ceny od dodavatelů", "porovnej nabídky dodavatelů", "hledáme jiného dodavatele", "alternativní dodavatel", "ask suppliers for a quote", "compare supplier offers", "find an alternate supplier", "second source".
---

# Supplier RFQ

The instructions for this skill live on the **Circuit Ninja** connector, so everyone follows the current version.

1. Call `Circuit Ninja:read_skill` with `name: "supplier-rfq"`.
2. Follow the instructions it returns. They replace this page.
3. If it says the skill is not available, tell the person why, then call `Circuit Ninja:suggest_skills` with one generic line about the work.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

- Send the request, accept an offer, order, or commit spend: the buyer does.
- Tell one supplier another supplier's name or price, or the price we pay today.
- Send a supplier anything that belongs to a customer: order data, board files, drawings.
- Use or repeat a login or password from any sheet (some supplier sheets still hold them).
- Anything on the company never-list (the `company-context` skill lists it).
