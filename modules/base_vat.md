---
layout: page
title: "VAT Number Validation (base_vat)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/base_vat/
nav_order: 0
---
# VAT Number Validation — `base_vat`

**Source:** [`agents/modules/generated/base_vat.yaml`](../../agents/modules/generated/base_vat.yaml) · **Wiki:** [`knowledge/modules/base_vat/overview.md`](../../knowledge/modules/base_vat/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base_vat</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">VAT Number Validation</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/base_vat</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/base_vat"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`account`](account.md)

## Reverse dependencies (modules that depend on this)

[`l10n_at`](l10n_at.md), [`l10n_be`](l10n_be.md), [`l10n_bg`](l10n_bg.md), [`l10n_br`](l10n_br.md), [`l10n_cl`](l10n_cl.md), [`l10n_cy`](l10n_cy.md), [`l10n_cz`](l10n_cz.md), [`l10n_de`](l10n_de.md), [`l10n_dk`](l10n_dk.md), [`l10n_dz`](l10n_dz.md), [`l10n_es`](l10n_es.md), [`l10n_fi`](l10n_fi.md), [`l10n_fr`](l10n_fr.md), [`l10n_gr`](l10n_gr.md), [`l10n_hr`](l10n_hr.md), [`l10n_hu`](l10n_hu.md), [`l10n_id`](l10n_id.md), [`l10n_ie`](l10n_ie.md), [`l10n_in`](l10n_in.md), [`l10n_it`](l10n_it.md), [`l10n_latam_base`](l10n_latam_base.md), [`l10n_latam_check`](l10n_latam_check.md), [`l10n_lu`](l10n_lu.md), [`l10n_lv`](l10n_lv.md), [`l10n_mr`](l10n_mr.md), [`l10n_mt`](l10n_mt.md), [`l10n_ng`](l10n_ng.md), [`l10n_nl`](l10n_nl.md), [`l10n_no`](l10n_no.md), [`l10n_pe`](l10n_pe.md), [`l10n_ph`](l10n_ph.md), [`l10n_pl`](l10n_pl.md), [`l10n_pt`](l10n_pt.md), [`l10n_ro`](l10n_ro.md), [`l10n_rs`](l10n_rs.md), [`l10n_sa_edi`](l10n_sa_edi.md), [`l10n_se`](l10n_se.md), [`l10n_si`](l10n_si.md), [`l10n_sk`](l10n_sk.md), [`l10n_uk`](l10n_uk.md), [`l10n_za`](l10n_za.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.fiscal.position</code></div><div class="role">extended by <code>base_vat</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>base_vat</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>base_vat</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>base_vat</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.l10n_at` | required_by | `agents/modules/generated/l10n_at.yaml` |
| `module.l10n_be` | required_by | `agents/modules/generated/l10n_be.yaml` |
| `module.l10n_bg` | required_by | `agents/modules/generated/l10n_bg.yaml` |
| `module.l10n_br` | required_by | `agents/modules/generated/l10n_br.yaml` |
| `module.l10n_cl` | extends_model_from, required_by | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_cy` | required_by | `agents/modules/generated/l10n_cy.yaml` |
| `module.l10n_cz` | required_by | `agents/modules/generated/l10n_cz.yaml` |

## Full wiki excerpt

- SME owner: [`module.base_vat`](../../../agents/modules/generated/base_vat.yaml)
- Domain: `platform_core`
- Category: Accounting/Accounting
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/base_vat)
- Direct dependencies: [`account`](../account/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_at`](../l10n_at/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_bg`](../l10n_bg/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_cy`](../l10n_cy/overview.md), [`l10n_cz`](../l10n_cz/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_dk`](../l10n_dk/overview.md), [`l10n_dz`](../l10n_dz/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_fi`](../l10n_fi/overview.md), [`l10n_fr`](../l10n_fr/overview.md), [`l10n_gr`](../l10n_gr/overview.md), [`l10n_hr`](../l10n_hr/overview.md), [`l10n_hu`](../l10n_hu/overview.md), [`l10n_id`](../l10n_id/overview.md), [`l10n_ie`](../l10n_ie/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_it`](../l10n_it/overview.md), [`l10n_latam_base`](../l10n_latam_base/overview.md), [`l10n_latam_check`](../l10n_latam_check/overview.md), [`l10n_lu`](../l10n_lu/overview.md), [`l10n_lv`](../l10n_lv/overview.md), [`l10n_mr`](../l10n_mr/overview.md), [`l10n_mt`](../l10n_mt/overview.md), [`l10n_ng`](../l10n_ng/overview.md), [`l10n_nl`](../l10n_nl/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_pt`](../l10n_pt/overview.md), [`l10n_ro`](../l10n_ro/overview.md), [`l10n_rs`](../l10n_rs/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_si`](../l10n_si/overview.md), [`l10n_sk`](../l10n_sk/overview.md), [`l10n_uk`](../l10n_uk/overview.md), [`l10n_za`](../l10n_za/overview.md)
- Impact graph: [`module:base_vat`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `account.fiscal.position` — defined by [`account`](../account/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.l10n_at`](../../../agents/modules/generated/l10n_at.yaml) — required_by
- [`module.l10n_be`](../../../agents/modules/generated/l10n_be.yaml) — required_by
- [`module.l10n_bg`](../../../agents/modules/generated/l10n_bg.yaml) — required_by
- [`module.l10n_br`](../../../agents/modules/generated/l10n_br.yaml) — required_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from, required_by
- [`module.l10n_cy`](../../../agents/modules/generated/l10n_cy.yaml) — required_by
- [`module.l10n_cz`](../../../agents/modules/generated/l10n_cz.yaml) — required_by
- [`module.l10n_de`](../../../agents/modules/generated/l10n_de.yaml) — required_by
- [`module.l10n_dk`](../../../agents/modules/generated/l10n_dk.yaml) — required_by
- [`module.l10n_dz`](../../../agents/modules/generated/l10n_dz.yaml) — required_by
- [`module.l10n_es`](../../../agents/modules/generated/l10n_es.yaml) — required_by
- [`module.l10n_fi`](../../../agents/modules/generated/l10n_fi.yaml) — required_by
- [`module.l10n_fr`](../../../agents/modules/generated/l10n_fr.yaml) — required_by
- [`module.l10n_gr`](../../../agents/modules/generated/l10n_gr.yaml) — required_by
- [`module.l10n_hr`](../../../agents/modules/generated/l10n_hr.yaml) — required_by
- [`module.l10n_hu`](../../../agents/modules/generated/l10n_hu.yaml) — required_by
- [`module.l10n_id`](../../../agents/modules/generated/l10n_id.yaml) — required_by
- [`module.l10n_ie`](../../../agents/modules/generated/l10n_ie.yaml) — required_by
- [`module.l10n_in`](../../../agents/modules/generated/l10n_in.yaml) — required_by
- [`module.l10n_it`](../../../agents/modules/generated/l10n_it.yaml) — required_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_latam_base`](../../../agents/modules/generated/l10n_latam_base.yaml) — required_by
- [`module.l10n_latam_check`](../../../agents/modules/generated/l10n_latam_check.yaml) — required_by
- [`module.l10n_lu`](../../../agents/modules/generated/l10n_lu.yaml) — required_by
- [`module.l10n_lv`](../../../agents/modules/generated/l10n_lv.yaml) — required_by
- [`module.l10n_mr`](../../../agents/modules/generated/l10n_mr.yaml) — required_by
- [`module.l10n_mt`](../../../agents/modules/generated/l10n_mt.yaml) — required_by
- [`module.l10n_ng`](../../../agents/modules/generated/l10n_ng.yaml) — required_by
- [`module.l10n_nl`](../../../agents/modules/generated/l10n_nl.yaml) — required_by
- [`module.l10n_no`](../../../agents/modules/generated/l10n_no.yaml) — required_by
- [`module.l10n_pe`](../../../agents/modules/generated/l10n_pe.yaml) — required_by
- [`module.l10n_ph`](../../../agents/modules/generated/l10n_ph.yaml) — required_by
- [`module.l10n_pl`](../../../agents/modules/generated/l10n_pl.yaml) — required_by
- [`module.l10n_pt`](../../../agents/modules/generated/l10n_pt.yaml) — required_by
- [`module.l10n_ro`](../../../agents/modules/generated/l10n_ro.yaml) — required_by
- [`module.l10n_rs`](../../../agents/modules/generated/l10n_rs.yaml) — required_by
- [`module.l10n_sa_edi`](../../../agents/modules/generated/l10n_sa_edi.yaml) — required_by
- [`module.l10n_se`](../../../agents/modules/generated/l10n_se.yaml) — required_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_si`](../../../agents/modules/generated/l10n_si.yaml) — required_by
- [`module.l10n_sk`](../../../agents/modules/generated/l10n_sk.yaml) — required_by
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.l10n_uk`](../../../agents/modules/generated/l10n_uk.yaml) — required_by
- [`module.l10n_za`](../../../agents/modules/generated/l10n_za.yaml) — required_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from

## Regression impact checklist

- Review 41 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
