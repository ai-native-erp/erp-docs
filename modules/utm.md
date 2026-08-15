---
layout: page
title: "UTM Trackers (utm)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/utm/
nav_order: 0
---
# UTM Trackers — `utm`

**Source:** [`agents/modules/generated/utm.yaml`](../../agents/modules/generated/utm.yaml) · **Wiki:** [`knowledge/modules/utm/overview.md`](../../knowledge/modules/utm/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>utm</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">UTM Trackers</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/utm</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/utm"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base`](base.md), [`web`](web.md)

## Reverse dependencies (modules that depend on this)

[`crm`](crm.md), [`event`](event.md), [`hr_recruitment`](hr_recruitment.md), [`im_livechat`](im_livechat.md), [`link_tracker`](link_tracker.md), [`mass_mailing`](mass_mailing.md), [`sale`](sale.md), [`website`](website.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>utm.campaign</code></div><div class="role">defined by <code>utm</code></div></div>
<div class="model"><div class="name"><code>utm.medium</code></div><div class="role">defined by <code>utm</code></div></div>
<div class="model"><div class="name"><code>utm.mixin</code></div><div class="role">defined by <code>utm</code></div></div>
<div class="model"><div class="name"><code>utm.source</code></div><div class="role">defined by <code>utm</code></div></div>
<div class="model"><div class="name"><code>utm.source.mixin</code></div><div class="role">defined by <code>utm</code></div></div>
<div class="model"><div class="name"><code>utm.stage</code></div><div class="role">defined by <code>utm</code></div></div>
<div class="model"><div class="name"><code>utm.tag</code></div><div class="role">defined by <code>utm</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>utm</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | depends_on, extends_model_from | `agents/modules/generated/base.yaml` |
| `module.crm` | model_extended_by, required_by | `agents/modules/generated/crm.yaml` |
| `module.event` | required_by | `agents/modules/generated/event.yaml` |
| `module.hr_recruitment` | model_extended_by, required_by | `agents/modules/generated/hr_recruitment.yaml` |
| `module.im_livechat` | model_extended_by, required_by | `agents/modules/generated/im_livechat.yaml` |
| `module.link_tracker` | model_extended_by, required_by | `agents/modules/generated/link_tracker.yaml` |
| `module.mass_mailing` | model_extended_by, required_by | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_crm` | model_extended_by | `agents/modules/generated/mass_mailing_crm.yaml` |
| `module.mass_mailing_crm_sms` | model_extended_by | `agents/modules/generated/mass_mailing_crm_sms.yaml` |
| `module.mass_mailing_sale` | model_extended_by | `agents/modules/generated/mass_mailing_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.utm`](../../../agents/modules/generated/utm.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/utm)
- Direct dependencies: [`base`](../base/overview.md), [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`crm`](../crm/overview.md), [`event`](../event/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`im_livechat`](../im_livechat/overview.md), [`link_tracker`](../link_tracker/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`sale`](../sale/overview.md), [`website`](../website/overview.md)
- Impact graph: [`module:utm`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `utm.campaign` — extended by [`crm`](../crm/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`link_tracker`](../link_tracker/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_crm`](../mass_mailing_crm/overview.md), [`mass_mailing_crm_sms`](../mass_mailing_crm_sms/overview.md), [`mass_mailing_sale`](../mass_mailing_sale/overview.md), [`mass_mailing_sale_sms`](../mass_mailing_sale_sms/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`sale`](../sale/overview.md)
- `utm.medium` — extended by [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- `utm.mixin` — extended by [`crm`](../crm/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`link_tracker`](../link_tracker/overview.md), [`sale`](../sale/overview.md), [`test_mass_mailing`](../test_mass_mailing/overview.md)
- `utm.source` — extended by [`hr_recruitment`](../hr_recruitment/overview.md), [`mass_mailing`](../mass_mailing/overview.md)
- `utm.source.mixin` — extended by [`hr_recruitment`](../hr_recruitment/overview.md), [`im_livechat`](../im_livechat/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`test_mass_mailing`](../test_mass_mailing/overview.md)
- `utm.stage`
- `utm.tag`
- Extends `ir.http` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on, extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — model_extended_by, required_by
- [`module.event`](../../../agents/modules/generated/event.yaml) — required_by
- [`module.hr_recruitment`](../../../agents/modules/generated/hr_recruitment.yaml) — model_extended_by, required_by
- [`module.im_livechat`](../../../agents/modules/generated/im_livechat.yaml) — model_extended_by, required_by
- [`module.link_tracker`](../../../agents/modules/generated/link_tracker.yaml) — model_extended_by, required_by
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — model_extended_by, required_by
- [`module.mass_mailing_crm`](../../../agents/modules/generated/mass_mailing_crm.yaml) — model_extended_by
- [`module.mass_mailing_crm_sms`](../../../agents/modules/generated/mass_mailing_crm_sms.yaml) — model_extended_by
- [`module.mass_mailing_sale`](../../../agents/modules/generated/mass_mailing_sale.yaml) — model_extended_by
- [`module.mass_mailing_sale_sms`](../../../agents/modules/generated/mass_mailing_sale_sms.yaml) — model_extended_by
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — model_extended_by
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — model_extended_by, required_by
- [`module.test_mass_mailing`](../../../agents/modules/generated/test_mass_mailing.yaml) — model_extended_by
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — required_by

## Regression impact checklist

- Review 8 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`crm`](../crm/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`im_livechat`](../im_livechat/overview.md), [`link_tracker`](../link_tracker/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_crm`](../mass_mailing_crm/overview.md), [`mass_mailing_crm_sms`](../mass_mailing_crm_sms/overview.md), [`mass_mailing_sale`](../mass_mailing_sale/overview.md), [`mass_mailing_sale_sms`](../mass_mailing_sale_sms/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`sale`](../sale/overview.md), [`test_mass_mailing`](../test_mass_mailing/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
