# Circuit Ninja for Claude

The company's Claude skills, kept up to date. This repository is written by `twin skills plugin` on every release
of Circuit Ninja's Dojo, so edits made here are overwritten. Change a skill in the company repository
(`company-skills/`) or from Claude with the `publish-to-dojo` skill.

## Which plugins

Everyone installs **Circuit Ninja**: the connector and the skills for everyone. Next to it, add your team's plugin.
You can add any other team's plugin too, but each one adds its skills' descriptions to every conversation, so add
the ones you use.

| plugin | for | version | skills |
|---|---|---|---|
| **Circuit Ninja** (`circuit-ninja`) | everyone | 1.0.3 | `company-context`, `company-numbers`, `inbox-follow-ups`, `morning-brief`, `ninja-onboard`, `publish-to-dojo`, `teach-the-twin` |
| **Circuit Ninja · Production** (`circuit-ninja-production`) | production | 1.0.0 | `failure-analysis`, `shift-handover` |
| **Circuit Ninja · Backoffice** (`circuit-ninja-backoffice`) | backoffice | 1.0.0 | `reorder-check` |
| **Circuit Ninja · Sales** (`circuit-ninja-sales`) | sales | 1.0.0 | `company-brief`, `order-status`, `quote-reply` |
| **Circuit Ninja · Marketing** (`circuit-ninja-marketing`) | marketing | 1.0.0 | `event-prep` |
| **Circuit Ninja · Management** (`circuit-ninja-management`) | management | 1.0.0 | `cross-check`, `weekly-review` |

No team plugin yet for development: install Circuit Ninja alone, and Claude offers other teams' skills when the work needs them.

You don't need every plugin to use every skill. When work fits a skill from a plugin you haven't added, Claude finds
it through the connector (Ninja), uses it right away, and offers to add its plugin.

## Install (once, about five minutes)

**Claude on the web or the desktop app (Pro or Max):**

1. Open **Customize > Plugins**, choose **Add > Add marketplace** and enter `jstudnic1/circuit-ninja-claude-plugins`.
2. Install **Circuit Ninja** and your team's plugin, then turn on **Sync automatically** for the marketplace. New
   versions then reach you by themselves.
3. Open the **Circuit Ninja** plugin's **Connectors** tab and connect **Circuit Ninja** with your company Google
   account. If you connected it before under **Customize > Connectors**, it already shows **Connected**.
4. If you uploaded Circuit Ninja skills as zip files before, remove them under **Customize > Skills**. Those copies
   don't update.

Plugins are saved to your account, so Cowork and Claude Code have them too, with nothing more to install.

**Claude Code only (without a claude.ai account):**

```text
/plugin marketplace add jstudnic1/circuit-ninja-claude-plugins
/plugin install circuit-ninja@circuit-ninja-dojo
/plugin install circuit-ninja-<team>@circuit-ninja-dojo
```

Then turn on updates: **/plugin > Marketplaces > circuit-ninja-dojo > Enable auto-update**. A team's plugin brings
Circuit Ninja with it.

## Every skill

| skill | what it does | for | plugin |
|---|---|---|---|
| `company-context` | Start any work: the company's and your team's instructions, and the skill for the task | everyone | `circuit-ninja` |
| `company-numbers` | Company numbers | everyone | `circuit-ninja` |
| `inbox-follow-ups` | Inbox follow-ups | everyone | `circuit-ninja` |
| `morning-brief` | Morning brief | everyone | `circuit-ninja` |
| `ninja-onboard` | Ninja onboarding | everyone | `circuit-ninja` |
| `publish-to-dojo` | Publish a skill to Dojo | everyone | `circuit-ninja` |
| `teach-the-twin` | Teach the twin | everyone | `circuit-ninja` |
| `failure-analysis` | Failure analysis | production, development, management | `circuit-ninja-production` |
| `shift-handover` | Shift handover | production | `circuit-ninja-production` |
| `reorder-check` | Reorder check | backoffice, production | `circuit-ninja-backoffice` |
| `company-brief` | Company brief | sales, marketing, management | `circuit-ninja-sales` |
| `order-status` | Order status | sales, production, backoffice | `circuit-ninja-sales` |
| `quote-reply` | Quote reply | sales | `circuit-ninja-sales` |
| `event-prep` | Event prep | marketing, sales, management | `circuit-ninja-marketing` |
| `cross-check` | Cross-check | management, production | `circuit-ninja-management` |
| `weekly-review` | Weekly review | management | `circuit-ninja-management` |

Each skill here is short. It loads its current instructions from the Circuit Ninja connector, so improvements reach
you at the next release of the twin, before any plugin changes at all. Only a new skill or a new description makes a
new plugin version.
