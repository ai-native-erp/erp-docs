---
layout: page
title: "KPI Digests (digest)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/digest/
nav_order: 0
---
# KPI Digests — `digest`

**Source:** [`agents/modules/generated/digest.yaml`](../../agents/modules/generated/digest.yaml) · **Wiki:** [`knowledge/modules/digest/overview.md`](../../knowledge/modules/digest/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>digest</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">KPI Digests</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/digest</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/digest"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`mail`](mail.md), [`portal`](portal.md), [`resource`](resource.md)

## Reverse dependencies (modules that depend on this)

[`account`](account.md), [`crm`](crm.md), [`hr_recruitment`](hr_recruitment.md), [`im_livechat`](im_livechat.md), [`mass_mailing`](mass_mailing.md), [`point_of_sale`](point_of_sale.md), [`project`](project.md), [`sale_management`](sale_management.md), [`stock`](stock.md), [`website`](website.md), [`website_sale`](website_sale.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>digest.digest</code></div><div class="role">defined by <code>digest</code></div></div>
<div class="model"><div class="name"><code>digest.tip</code></div><div class="role">defined by <code>digest</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>digest</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>digest</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | model_extended_by, required_by | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.crm` | model_extended_by, required_by | `agents/modules/generated/crm.yaml` |
| `module.hr_recruitment` | model_extended_by, required_by | `agents/modules/generated/hr_recruitment.yaml` |
| `module.im_livechat` | model_extended_by, required_by | `agents/modules/generated/im_livechat.yaml` |
| `module.mail` | depends_on, extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from, required_by | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |
| `module.point_of_sale` | model_extended_by, required_by | `agents/modules/generated/point_of_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.digest`](../../../agents/modules/generated/digest.yaml)
- Domain: `platform_core`
- Category: Marketing
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/digest)
- Direct dependencies: [`mail`](../mail/overview.md), [`portal`](../portal/overview.md), [`resource`](../resource/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`account`](../account/overview.md), [`crm`](../crm/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`im_livechat`](../im_livechat/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`project`](../project/overview.md), [`sale_management`](../sale_management/overview.md), [`stock`](../stock/overview.md), [`website`](../website/overview.md), [`website_sale`](../website_sale/overview.md)
- Impact graph: [`module:digest`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `digest.digest` — extended by [`account`](../account/overview.md), [`crm`](../crm/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`im_livechat`](../im_livechat/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`project`](../project/overview.md), [`sale_management`](../sale_management/overview.md), [`website_sale`](../website_sale/overview.md)
- `digest.tip`
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — model_extended_by, required_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — model_extended_by, required_by
- [`module.hr_recruitment`](../../../agents/modules/generated/hr_recruitment.yaml) — model_extended_by, required_by
- [`module.im_livechat`](../../../agents/modules/generated/im_livechat.yaml) — model_extended_by, required_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from, required_by
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — model_extended_by, required_by
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — depends_on
- [`module.project`](../../../agents/modules/generated/project.yaml) — model_extended_by, required_by
- [`module.resource`](../../../agents/modules/generated/resource.yaml) — depends_on
- [`module.sale_management`](../../../agents/modules/generated/sale_management.yaml) — model_extended_by, required_by
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — required_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — required_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — model_extended_by, required_by

## Regression impact checklist

- Review 11 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account`](../account/overview.md), [`crm`](../crm/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`im_livechat`](../im_livechat/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`project`](../project/overview.md), [`sale_management`](../sale_management/overview.md), [`website_sale`](../website_sale/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
