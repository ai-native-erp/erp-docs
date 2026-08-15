---
layout: page
title: "IAP / Mail (iap_mail)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/iap_mail/
nav_order: 0
---
# IAP / Mail — `iap_mail`

**Source:** [`agents/modules/generated/iap_mail.yaml`](../../agents/modules/generated/iap_mail.yaml) · **Wiki:** [`knowledge/modules/iap_mail/overview.md`](../../knowledge/modules/iap_mail/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>iap_mail</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">IAP / Mail</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">integrations</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/iap_mail</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/iap_mail"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Bridge between IAP and mail

## Direct dependencies

[`iap`](iap.md), [`mail`](mail.md)

## Reverse dependencies (modules that depend on this)

[`crm_iap_enrich`](crm_iap_enrich.md), [`crm_iap_mine`](crm_iap_mine.md), [`iap_crm`](iap_crm.md), [`partner_autocomplete`](partner_autocomplete.md), [`sms`](sms.md), [`snailmail`](snailmail.md), [`website_crm_iap_reveal`](website_crm_iap_reveal.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>iap.account</code></div><div class="role">extended by <code>iap_mail</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.crm_iap_enrich` | required_by | `agents/modules/generated/crm_iap_enrich.yaml` |
| `module.crm_iap_mine` | required_by | `agents/modules/generated/crm_iap_mine.yaml` |
| `module.iap` | depends_on, extends_model_from | `agents/modules/generated/iap.yaml` |
| `module.iap_crm` | required_by | `agents/modules/generated/iap_crm.yaml` |
| `module.mail` | depends_on | `agents/modules/generated/mail.yaml` |
| `module.partner_autocomplete` | required_by | `agents/modules/generated/partner_autocomplete.yaml` |
| `module.sms` | required_by | `agents/modules/generated/sms.yaml` |
| `module.snailmail` | required_by | `agents/modules/generated/snailmail.yaml` |
| `module.website_crm_iap_reveal` | required_by | `agents/modules/generated/website_crm_iap_reveal.yaml` |

## Full wiki excerpt

- SME owner: [`module.iap_mail`](../../../agents/modules/generated/iap_mail.yaml)
- Domain: `integrations`
- Category: Hidden/Tools
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/iap_mail)
- Direct dependencies: [`iap`](../iap/overview.md), [`mail`](../mail/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`crm_iap_enrich`](../crm_iap_enrich/overview.md), [`crm_iap_mine`](../crm_iap_mine/overview.md), [`iap_crm`](../iap_crm/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`sms`](../sms/overview.md), [`snailmail`](../snailmail/overview.md), [`website_crm_iap_reveal`](../website_crm_iap_reveal/overview.md)
- Impact graph: [`module:iap_mail`](../../impact-graph.json)

## Purpose

Bridge between IAP and mail

## Model relationships

- Extends `iap.account` — defined by [`iap`](../iap/overview.md)

## Related SME agents

- [`module.crm_iap_enrich`](../../../agents/modules/generated/crm_iap_enrich.yaml) — required_by
- [`module.crm_iap_mine`](../../../agents/modules/generated/crm_iap_mine.yaml) — required_by
- [`module.iap`](../../../agents/modules/generated/iap.yaml) — depends_on, extends_model_from
- [`module.iap_crm`](../../../agents/modules/generated/iap_crm.yaml) — required_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — required_by
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — required_by
- [`module.snailmail`](../../../agents/modules/generated/snailmail.yaml) — required_by
- [`module.website_crm_iap_reveal`](../../../agents/modules/generated/website_crm_iap_reveal.yaml) — required_by

## Regression impact checklist

- Review 7 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`iap`](../iap/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
