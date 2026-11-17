---
name: machine-down
description: When a station or machine on the Circuit Ninja line stops or misbehaves (a laser, the press, a bath, plating, etching), work out what to check first - safety before anything, what changed since it last ran well, the likely causes each with its evidence and the cheapest test that tells them apart - and draft the ticket for the "Výroba - ticketing" form and the line-stopped entry for the daily report. Works from what the person describes, photos and the machine's manual; needs no company data. Use for "stroj stojí", "linka stojí", "porucha na stroji", "nejede laser", "lis hlásí chybu", "stroj nefunguje", "přestalo fungovat", "lázeň teče", "co zkontrolovat jako první", "založ ticket na poruchu", "the machine is down", "the line stopped", "error on the machine", "diagnose this breakdown".
---

# Machine down

The instructions for this skill live on the **Circuit Ninja** connector, so everyone follows the current version.

1. Call `Circuit Ninja:read_skill` with `name: "machine-down"`.
2. Follow the instructions it returns. They replace this page.
3. If it says the skill is not available, tell the person why, then call `Circuit Ninja:suggest_skills` with one generic line about the work.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

- Change machine, bath or recipe settings, or tell the line to: the tests are proposals for the person responsible
  for the station.
- Advise bypassing, bridging or switching off a guard, an interlock or an emergency stop, or sign off a safety item.
- Tell anyone to release, scrap or rework the panel that was in the machine.
- Submit the ticket or post to the production chat for the person.
- Name who caused it: describe the work, not the person.
- Anything on the company never-list (the `company-context` skill lists it).
