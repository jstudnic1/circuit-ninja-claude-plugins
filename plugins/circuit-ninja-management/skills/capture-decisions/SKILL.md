---
name: capture-decisions
description: After a meeting, a call, an e-mail thread or a Chat discussion, turn what was decided, promised (with dates), blocked or left open into short sentences on the right Circuit Ninja project, show them, and save the ones the person confirms into the company memory - so the project overview, the timeline and the Monday "Co visí" track them. Reads the person's own Google Calendar, meeting notes and Gmail, or a thread they paste. Use for "zapiš ze schůzky", "co jsme dohodli na poradě", "ulož rozhodnutí z porady do projektu", "capture the decisions from this meeting", "dej ty sliby z mailu do přehledu projektu".
---

# Capture decisions

The instructions for this skill live on the **Circuit Ninja** connector, so everyone follows the current version.

1. Call `Circuit Ninja:read_skill` with `name: "capture-decisions"`.
2. Follow the instructions it returns. They replace this page.
3. If it says the skill is not available, tell the person why, then call `Circuit Ninja:suggest_skills` with one generic line about the work.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

- Save anything the person did not confirm, or more than they confirmed.
- Names of people, contact details, quotes from mail or Chat, or anything personal: health, pay, performance,
  private life. Say the role: "výroba slíbila", "dodavatel potvrdil".
- Read or save from anyone else's calendar or mailbox; save who attended a meeting.
- Send, reply to, or change mail, events or documents.
- Judge, rate or rank a colleague, even when the notes do.
- Anything on the company never-list (the `company-context` skill lists it).
