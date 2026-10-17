# Circuit Ninja for Claude

The company's Claude skills, kept up to date: version 1.0.0. This repository is written by `twin skills plugin`
on every release of Circuit Ninja's Dojo, so edits made here are overwritten. Change a skill in the company
repository (`company-skills/`) or from Claude with the `publish-to-dojo` skill.

## Install (once, about five minutes)

**Claude on the web or the desktop app (Pro or Max):**

1. Open **Customize > Plugins**, choose **Add > Add marketplace** and enter `jstudnic1/circuit-ninja-claude-plugins`.
2. Install **Circuit Ninja**, then turn on **Sync automatically** for the marketplace. New versions then reach you
   by themselves.
3. Open the plugin's **Connectors** tab and connect **Circuit Ninja** with your company Google account. If you
   connected it before under **Customize > Connectors**, it already shows **Connected**.
4. If you uploaded Circuit Ninja skills as zip files before, remove them under **Customize > Skills**. Those copies
   don't update.

The plugin is saved to your account, so Cowork and Claude Code have it too, with nothing more to install.

**Claude Code only (without a claude.ai account):**

```text
/plugin marketplace add jstudnic1/circuit-ninja-claude-plugins
/plugin install circuit-ninja@circuit-ninja-dojo
```

Then turn on updates: **/plugin > Marketplaces > circuit-ninja-dojo > Enable auto-update**.

## What's inside

| skill | what it does |
|---|---|
| `company-context` | Start any work: the company's and your team's instructions, and the skill for the task |
| `company-brief` | Company brief |
| `company-numbers` | Company numbers |
| `event-prep` | Event prep |
| `failure-analysis` | Failure analysis |
| `inbox-follow-ups` | Inbox follow-ups |
| `morning-brief` | Morning brief |
| `ninja-onboard` | Ninja onboarding |
| `order-status` | Order status |
| `publish-to-dojo` | Publish a skill to Dojo |
| `quote-reply` | Quote reply |
| `reorder-check` | Reorder check |
| `shift-handover` | Shift handover |
| `teach-the-twin` | Teach the twin |
| `weekly-review` | Weekly review |

Each skill here is short. It loads its current instructions from the Circuit Ninja connector, so improvements reach
you at the next release of the twin, before this plugin changes at all. Only a new skill or a new description makes a
new plugin version.
