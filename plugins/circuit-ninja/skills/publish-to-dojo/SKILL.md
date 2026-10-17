---
name: publish-to-dojo
description: Spot work worth keeping as a Circuit Ninja skill and publish it to Dojo, the company skill library, so next time it is one sentence away for everyone in the right roles. Use when the person says "turn this into a skill", "make it a skill", "keep it as a skill", "udělej z toho skill", "ulož to jako skill", "publish to Dojo", "I do this every week", "dělám to pořád", or when multi-step work that will repeat is done and suggest_skills found no skill for it.
---

# Publish a skill to Dojo

The instructions for this skill live on the **Circuit Ninja** connector, so everyone follows the current version.

1. Call `Circuit Ninja:read_skill` with `name: "publish-to-dojo"`.
2. Follow the instructions it returns. They replace this page.
3. If it says the skill is not available, tell the person why, then call `Circuit Ninja:suggest_skills` with one generic line about the work.

If the Circuit Ninja tools are not available, the connector is not connected. Ask the person to connect it (Customize > Plugins > Circuit Ninja > Connectors, or Customize > Connectors), signing in with the company Google account, and stop. Do not do the work from memory.

## Never

- <what this skill must never do: send, order, commit a price, change a setting, judge a colleague ...>
- Anything on the company never-list (the `company-context` skill lists it).
