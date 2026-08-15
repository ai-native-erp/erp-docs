---
layout: page
title: "LATAM Localization Base (l10n_latam_base)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_latam_base/
nav_order: 0
---
# LATAM Localization Base — `l10n_latam_base`

**Source:** [`agents/modules/generated/l10n_latam_base.yaml`](../../agents/modules/generated/l10n_latam_base.yaml) · **Wiki:** [`knowledge/modules/l10n_latam_base/overview.md`](../../knowledge/modules/l10n_latam_base/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_latam_base</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">LATAM Localization Base</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_latam_base</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_latam_base"><code>126b5bd</code></a></div></div>
</div>
## Purpose

LATAM Identification Types

## Direct dependencies

[`base_vat`](base_vat.md), [`contacts`](contacts.md)

## Reverse dependencies (modules that depend on this)

[`l10n_ar`](l10n_ar.md), [`l10n_br`](l10n_br.md), [`l10n_cl`](l10n_cl.md), [`l10n_co`](l10n_co.md), [`l10n_ec`](l10n_ec.md), [`l10n_pe`](l10n_pe.md), [`l10n_uy`](l10n_uy.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>l10n_latam.identification.type</code></div><div class="role">defined by <code>l10n_latam_base</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>l10n_latam_base</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>l10n_latam_base</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.base_vat` | depends_on | `agents/modules/generated/base_vat.yaml` |
| `module.contacts` | depends_on | `agents/modules/generated/contacts.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.l10n_ar` | model_extended_by, required_by | `agents/modules/generated/l10n_ar.yaml` |
| `module.l10n_br` | required_by | `agents/modules/generated/l10n_br.yaml` |
| `module.l10n_cl` | extends_model_from, required_by | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_co` | model_extended_by, required_by | `agents/modules/generated/l10n_co.yaml` |
| `module.l10n_ec` | required_by | `agents/modules/generated/l10n_ec.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_latam_base`](../../../agents/modules/generated/l10n_latam_base.yaml)
- Domain: `localization`
- Category: Accounting/Localizations
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_latam_base)
- Direct dependencies: [`base_vat`](../base_vat/overview.md), [`contacts`](../contacts/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_ar`](../l10n_ar/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_co`](../l10n_co/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_uy`](../l10n_uy/overview.md)
- Impact graph: [`module:l10n_latam_base`](../../impact-graph.json)

## Purpose

LATAM Identification Types

## Model relationships

- `l10n_latam.identification.type` — extended by [`l10n_ar`](../l10n_ar/overview.md), [`l10n_co`](../l10n_co/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_uy`](../l10n_uy/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.base_vat`](../../../agents/modules/generated/base_vat.yaml) — depends_on
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — depends_on
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.l10n_ar`](../../../agents/modules/generated/l10n_ar.yaml) — model_extended_by, required_by
- [`module.l10n_br`](../../../agents/modules/generated/l10n_br.yaml) — required_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from, required_by
- [`module.l10n_co`](../../../agents/modules/generated/l10n_co.yaml) — model_extended_by, required_by
- [`module.l10n_ec`](../../../agents/modules/generated/l10n_ec.yaml) — required_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_pe`](../../../agents/modules/generated/l10n_pe.yaml) — model_extended_by, required_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.l10n_uy`](../../../agents/modules/generated/l10n_uy.yaml) — model_extended_by, required_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from

## Regression impact checklist

- Review 7 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`l10n_ar`](../l10n_ar/overview.md), [`l10n_co`](../l10n_co/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_uy`](../l10n_uy/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
