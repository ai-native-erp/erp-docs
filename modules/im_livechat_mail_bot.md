---
layout: page
title: "OdooBot for livechat (im_livechat_mail_bot)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/im_livechat_mail_bot/
nav_order: 0
---
# OdooBot for livechat — `im_livechat_mail_bot`

**Source:** [`agents/modules/generated/im_livechat_mail_bot.yaml`](../../agents/modules/generated/im_livechat_mail_bot.yaml) · **Wiki:** [`knowledge/modules/im_livechat_mail_bot/overview.md`](../../knowledge/modules/im_livechat_mail_bot/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>im_livechat_mail_bot</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">OdooBot for livechat</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/im_livechat_mail_bot</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/im_livechat_mail_bot"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Add livechat support for OdooBot

## Direct dependencies

[`im_livechat`](im_livechat.md), [`mail_bot`](mail_bot.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.bot</code></div><div class="role">extended by <code>im_livechat_mail_bot</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>im_livechat_mail_bot</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.im_livechat` | depends_on | `agents/modules/generated/im_livechat.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mail_bot` | depends_on, extends_model_from | `agents/modules/generated/mail_bot.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |

## Full wiki excerpt

- SME owner: [`module.im_livechat_mail_bot`](../../../agents/modules/generated/im_livechat_mail_bot.yaml)
- Domain: `platform_core`
- Category: Productivity/Discuss
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/im_livechat_mail_bot)
- Direct dependencies: [`im_livechat`](../im_livechat/overview.md), [`mail_bot`](../mail_bot/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:im_livechat_mail_bot`](../../impact-graph.json)

## Purpose

Add livechat support for OdooBot

## Model relationships

- Extends `mail.bot` — defined by [`mail_bot`](../mail_bot/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.im_livechat`](../../../agents/modules/generated/im_livechat.yaml) — depends_on
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mail_bot`](../../../agents/modules/generated/mail_bot.yaml) — depends_on, extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mail_bot`](../mail_bot/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
