---
layout: page
title: "Romania - E-Transport (l10n_ro_edi_stock)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_ro_edi_stock/
nav_order: 0
---
# Romania - E-Transport — `l10n_ro_edi_stock`

**Source:** [`agents/modules/generated/l10n_ro_edi_stock.yaml`](../../agents/modules/generated/l10n_ro_edi_stock.yaml) · **Wiki:** [`knowledge/modules/l10n_ro_edi_stock/overview.md`](../../knowledge/modules/l10n_ro_edi_stock/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_ro_edi_stock</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Romania - E-Transport</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_ro_edi_stock</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_ro_edi_stock"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`l10n_ro_efactura`](l10n_ro_efactura.md), [`stock_delivery`](stock_delivery.md)

## Reverse dependencies (modules that depend on this)

[`l10n_ro_edi_stock_batch`](l10n_ro_edi_stock_batch.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>delivery.carrier</code></div><div class="role">extended by <code>l10n_ro_edi_stock</code></div></div>
<div class="model"><div class="name"><code>l10n_ro_edi.document</code></div><div class="role">extended by <code>l10n_ro_edi_stock</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.delivery` | extends_model_from | `agents/modules/generated/delivery.yaml` |
| `module.l10n_ro_edi_stock_batch` | required_by | `agents/modules/generated/l10n_ro_edi_stock_batch.yaml` |
| `module.l10n_ro_efactura` | depends_on, extends_model_from | `agents/modules/generated/l10n_ro_efactura.yaml` |
| `module.stock_delivery` | depends_on | `agents/modules/generated/stock_delivery.yaml` |
| `module.website_sale` | extends_model_from | `agents/modules/generated/website_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_ro_edi_stock`](../../../agents/modules/generated/l10n_ro_edi_stock.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/EDI
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_ro_edi_stock)
- Direct dependencies: [`l10n_ro_efactura`](../l10n_ro_efactura/overview.md), [`stock_delivery`](../stock_delivery/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_ro_edi_stock_batch`](../l10n_ro_edi_stock_batch/overview.md)
- Impact graph: [`module:l10n_ro_edi_stock`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `delivery.carrier` — defined by [`delivery`](../delivery/overview.md), [`website_sale`](../website_sale/overview.md)
- Extends `l10n_ro_edi.document` — defined by [`l10n_ro_efactura`](../l10n_ro_efactura/overview.md)

## Related SME agents

- [`module.delivery`](../../../agents/modules/generated/delivery.yaml) — extends_model_from
- [`module.l10n_ro_edi_stock_batch`](../../../agents/modules/generated/l10n_ro_edi_stock_batch.yaml) — required_by
- [`module.l10n_ro_efactura`](../../../agents/modules/generated/l10n_ro_efactura.yaml) — depends_on, extends_model_from
- [`module.stock_delivery`](../../../agents/modules/generated/stock_delivery.yaml) — depends_on
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`delivery`](../delivery/overview.md), [`l10n_ro_efactura`](../l10n_ro_efactura/overview.md), [`website_sale`](../website_sale/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
