---
layout: page
title: "OdooBot - HR (mail_bot_hr)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/mail_bot_hr/
nav_order: 0
---
# OdooBot - HR — `mail_bot_hr`

**Source:** [`agents/modules/generated/mail_bot_hr.yaml`](../../agents/modules/generated/mail_bot_hr.yaml) · **Wiki:** [`knowledge/modules/mail_bot_hr/overview.md`](../../knowledge/modules/mail_bot_hr/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>mail_bot_hr</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">OdooBot - HR</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/mail_bot_hr</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mail_bot_hr"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Bridge module between hr and mailbot.

## Direct dependencies

[`hr`](hr.md), [`mail_bot`](mail_bot.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.hr` | depends_on | `agents/modules/generated/hr.yaml` |
| `module.mail_bot` | depends_on | `agents/modules/generated/mail_bot.yaml` |

## Full wiki excerpt

- SME owner: [`module.mail_bot_hr`](../../../agents/modules/generated/mail_bot_hr.yaml)
- Domain: `platform_core`
- Category: Productivity/Discuss
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mail_bot_hr)
- Direct dependencies: [`hr`](../hr/overview.md), [`mail_bot`](../mail_bot/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:mail_bot_hr`](../../impact-graph.json)

## Purpose

Bridge module between hr and mailbot.

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.hr`](../../../agents/modules/generated/hr.yaml) — depends_on
- [`module.mail_bot`](../../../agents/modules/generated/mail_bot.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
