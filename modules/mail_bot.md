---
layout: page
title: "OdooBot (mail_bot)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/mail_bot/
nav_order: 0
---
# OdooBot — `mail_bot`

**Source:** [`agents/modules/generated/mail_bot.yaml`](../../agents/modules/generated/mail_bot.yaml) · **Wiki:** [`knowledge/modules/mail_bot/overview.md`](../../knowledge/modules/mail_bot/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>mail_bot</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">OdooBot</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/mail_bot</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mail_bot"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Add OdooBot in discussions

## Direct dependencies

[`mail`](mail.md)

## Reverse dependencies (modules that depend on this)

[`im_livechat_mail_bot`](im_livechat_mail_bot.md), [`mail_bot_hr`](mail_bot_hr.md), [`test_discuss_full`](test_discuss_full.md), [`test_mail_full`](test_mail_full.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.bot</code></div><div class="role">defined by <code>mail_bot</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>discuss.channel</code></div><div class="role">extended by <code>mail_bot</code></div></div>
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>mail_bot</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>mail_bot</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>mail_bot</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.im_livechat` | extends_model_from | `agents/modules/generated/im_livechat.yaml` |
| `module.im_livechat_mail_bot` | model_extended_by, required_by | `agents/modules/generated/im_livechat_mail_bot.yaml` |
| `module.mail` | depends_on, extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mail_bot_hr` | required_by | `agents/modules/generated/mail_bot_hr.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |
| `module.test_discuss_full` | required_by | `agents/modules/generated/test_discuss_full.yaml` |
| `module.test_mail_full` | required_by | `agents/modules/generated/test_mail_full.yaml` |

## Full wiki excerpt

- SME owner: [`module.mail_bot`](../../../agents/modules/generated/mail_bot.yaml)
- Domain: `platform_core`
- Category: Productivity/Discuss
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mail_bot)
- Direct dependencies: [`mail`](../mail/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`im_livechat_mail_bot`](../im_livechat_mail_bot/overview.md), [`mail_bot_hr`](../mail_bot_hr/overview.md), [`test_discuss_full`](../test_discuss_full/overview.md), [`test_mail_full`](../test_mail_full/overview.md)
- Impact graph: [`module:mail_bot`](../../impact-graph.json)

## Purpose

Add OdooBot in discussions

## Model relationships

- `mail.bot` — extended by [`im_livechat_mail_bot`](../im_livechat_mail_bot/overview.md)
- Extends `discuss.channel` — defined by [`im_livechat`](../im_livechat/overview.md), [`mail`](../mail/overview.md)
- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.im_livechat`](../../../agents/modules/generated/im_livechat.yaml) — extends_model_from
- [`module.im_livechat_mail_bot`](../../../agents/modules/generated/im_livechat_mail_bot.yaml) — model_extended_by, required_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.mail_bot_hr`](../../../agents/modules/generated/mail_bot_hr.yaml) — required_by
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.test_discuss_full`](../../../agents/modules/generated/test_discuss_full.yaml) — required_by
- [`module.test_mail_full`](../../../agents/modules/generated/test_mail_full.yaml) — required_by

## Regression impact checklist

- Review 4 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`im_livechat_mail_bot`](../im_livechat_mail_bot/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`im_livechat`](../im_livechat/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
