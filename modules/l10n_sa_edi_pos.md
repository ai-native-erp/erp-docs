---
layout: page
title: "Saudi Arabia - E-invoicing (Simplified) (l10n_sa_edi_pos)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_sa_edi_pos/
nav_order: 0
---
# Saudi Arabia - E-invoicing (Simplified) — `l10n_sa_edi_pos`

**Source:** [`agents/modules/generated/l10n_sa_edi_pos.yaml`](../../agents/modules/generated/l10n_sa_edi_pos.yaml) · **Wiki:** [`knowledge/modules/l10n_sa_edi_pos/overview.md`](../../knowledge/modules/l10n_sa_edi_pos/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_sa_edi_pos</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Saudi Arabia - E-invoicing (Simplified)</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_sa_edi_pos</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_sa_edi_pos"><code>126b5bd</code></a></div></div>
</div>
## Purpose

ZATCA E-Invoicing, support for PoS

## Direct dependencies

[`l10n_sa_edi`](l10n_sa_edi.md), [`l10n_sa_pos`](l10n_sa_pos.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.edi.xml.ubl_21.zatca</code></div><div class="role">extended by <code>l10n_sa_edi_pos</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>l10n_sa_edi_pos</code></div></div>
<div class="model"><div class="name"><code>pos.config</code></div><div class="role">extended by <code>l10n_sa_edi_pos</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.l10n_sa_edi` | depends_on, extends_model_from | `agents/modules/generated/l10n_sa_edi.yaml` |
| `module.l10n_sa_pos` | depends_on | `agents/modules/generated/l10n_sa_pos.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.point_of_sale` | extends_model_from | `agents/modules/generated/point_of_sale.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_sa_edi_pos`](../../../agents/modules/generated/l10n_sa_edi_pos.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/EDI
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_sa_edi_pos)
- Direct dependencies: [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_sa_pos`](../l10n_sa_pos/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_sa_edi_pos`](../../impact-graph.json)

## Purpose

ZATCA E-Invoicing, support for PoS

## Model relationships

- Extends `account.edi.xml.ubl_21.zatca` — defined by [`l10n_sa_edi`](../l10n_sa_edi/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `pos.config` — defined by [`point_of_sale`](../point_of_sale/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.l10n_sa_edi`](../../../agents/modules/generated/l10n_sa_edi.yaml) — depends_on, extends_model_from
- [`module.l10n_sa_pos`](../../../agents/modules/generated/l10n_sa_pos.yaml) — depends_on
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`sale`](../sale/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
