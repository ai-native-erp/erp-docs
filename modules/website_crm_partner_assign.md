---
layout: page
title: "Resellers (website_crm_partner_assign)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_crm_partner_assign/
nav_order: 0
---
# Resellers — `website_crm_partner_assign`

**Source:** [`agents/modules/generated/website_crm_partner_assign.yaml`](../../agents/modules/generated/website_crm_partner_assign.yaml) · **Wiki:** [`knowledge/modules/website_crm_partner_assign/overview.md`](../../knowledge/modules/website_crm_partner_assign/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_crm_partner_assign</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Resellers</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_crm_partner_assign</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_crm_partner_assign"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Publish your resellers/partners and forward leads to them

## Direct dependencies

[`account`](account.md), [`base_geolocalize`](base_geolocalize.md), [`crm`](crm.md), [`portal`](portal.md), [`website_google_map`](website_google_map.md), [`website_partner`](website_partner.md)

## Reverse dependencies (modules that depend on this)

[`test_crm_full`](test_crm_full.md), [`website_customer`](website_customer.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>crm.lead.assignation</code></div><div class="role">defined by <code>website_crm_partner_assign</code></div></div>
<div class="model"><div class="name"><code>crm.lead.forward.to.partner</code></div><div class="role">defined by <code>website_crm_partner_assign</code></div></div>
<div class="model"><div class="name"><code>crm.partner.report.assign</code></div><div class="role">defined by <code>website_crm_partner_assign</code></div></div>
<div class="model"><div class="name"><code>res.partner.activation</code></div><div class="role">defined by <code>website_crm_partner_assign</code></div></div>
<div class="model"><div class="name"><code>res.partner.grade</code></div><div class="role">defined by <code>website_crm_partner_assign</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>crm.lead</code></div><div class="role">extended by <code>website_crm_partner_assign</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>website_crm_partner_assign</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>website_crm_partner_assign</code></div></div>
<div class="model"><div class="name"><code>website.published.mixin</code></div><div class="role">extended by <code>website_crm_partner_assign</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.base_geolocalize` | depends_on | `agents/modules/generated/base_geolocalize.yaml` |
| `module.crm` | depends_on, extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.l10n_tr_nilvera` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.partner_autocomplete` | extends_model_from | `agents/modules/generated/partner_autocomplete.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_crm_partner_assign`](../../../agents/modules/generated/website_crm_partner_assign.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_crm_partner_assign)
- Direct dependencies: [`account`](../account/overview.md), [`base_geolocalize`](../base_geolocalize/overview.md), [`crm`](../crm/overview.md), [`portal`](../portal/overview.md), [`website_google_map`](../website_google_map/overview.md), [`website_partner`](../website_partner/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_crm_full`](../test_crm_full/overview.md), [`website_customer`](../website_customer/overview.md)
- Impact graph: [`module:website_crm_partner_assign`](../../impact-graph.json)

## Purpose

Publish your resellers/partners and forward leads to them

## Model relationships

- `crm.lead.assignation`
- `crm.lead.forward.to.partner`
- `crm.partner.report.assign`
- `res.partner.activation`
- `res.partner.grade`
- Extends `crm.lead` — defined by [`crm`](../crm/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `website` — defined by [`website`](../website/overview.md)
- Extends `website.published.mixin` — defined by [`website`](../website/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.base_geolocalize`](../../../agents/modules/generated/base_geolocalize.yaml) — depends_on
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — depends_on, extends_model_from
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — depends_on
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.test_crm_full`](../../../agents/modules/generated/test_crm_full.yaml) — required_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_customer`](../../../agents/modules/generated/website_customer.yaml) — required_by
- [`module.website_google_map`](../../../agents/modules/generated/website_google_map.yaml) — depends_on
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
