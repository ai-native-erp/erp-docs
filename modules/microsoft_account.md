---
layout: page
title: "Microsoft Users (microsoft_account)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/microsoft_account/
nav_order: 0
---
# Microsoft Users — `microsoft_account`

**Source:** [`agents/modules/generated/microsoft_account.yaml`](../../agents/modules/generated/microsoft_account.yaml) · **Wiki:** [`knowledge/modules/microsoft_account/overview.md`](../../knowledge/modules/microsoft_account/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>microsoft_account</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Microsoft Users</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">integrations</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/microsoft_account</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/microsoft_account"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base_setup`](base_setup.md)

## Reverse dependencies (modules that depend on this)

[`microsoft_calendar`](microsoft_calendar.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>microsoft.service</code></div><div class="role">defined by <code>microsoft_account</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>microsoft_account</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.base_setup` | depends_on | `agents/modules/generated/base_setup.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |
| `module.microsoft_calendar` | required_by | `agents/modules/generated/microsoft_calendar.yaml` |

## Full wiki excerpt

- SME owner: [`module.microsoft_account`](../../../agents/modules/generated/microsoft_account.yaml)
- Domain: `integrations`
- Category: Hidden/Tools
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/microsoft_account)
- Direct dependencies: [`base_setup`](../base_setup/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`microsoft_calendar`](../microsoft_calendar/overview.md)
- Impact graph: [`module:microsoft_account`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `microsoft.service`
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.base_setup`](../../../agents/modules/generated/base_setup.yaml) — depends_on
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.microsoft_calendar`](../../../agents/modules/generated/microsoft_calendar.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
