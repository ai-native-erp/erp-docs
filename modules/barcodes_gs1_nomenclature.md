---
layout: page
title: "Barcode - GS1 Nomenclature (barcodes_gs1_nomenclature)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/barcodes_gs1_nomenclature/
nav_order: 0
---
# Barcode - GS1 Nomenclature — `barcodes_gs1_nomenclature`

**Source:** [`agents/modules/generated/barcodes_gs1_nomenclature.yaml`](../../agents/modules/generated/barcodes_gs1_nomenclature.yaml) · **Wiki:** [`knowledge/modules/barcodes_gs1_nomenclature/overview.md`](../../knowledge/modules/barcodes_gs1_nomenclature/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>barcodes_gs1_nomenclature</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Barcode - GS1 Nomenclature</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">inventory_purchase</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/barcodes_gs1_nomenclature</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/barcodes_gs1_nomenclature"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Parse barcodes according to the GS1-128 specifications

## Direct dependencies

[`barcodes`](barcodes.md), [`uom`](uom.md)

## Reverse dependencies (modules that depend on this)

[`stock`](stock.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>barcode.nomenclature</code></div><div class="role">extended by <code>barcodes_gs1_nomenclature</code></div></div>
<div class="model"><div class="name"><code>barcode.rule</code></div><div class="role">extended by <code>barcodes_gs1_nomenclature</code></div></div>
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>barcodes_gs1_nomenclature</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.barcodes` | depends_on, extends_model_from | `agents/modules/generated/barcodes.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.stock` | required_by | `agents/modules/generated/stock.yaml` |
| `module.uom` | depends_on | `agents/modules/generated/uom.yaml` |

## Full wiki excerpt

- SME owner: [`module.barcodes_gs1_nomenclature`](../../../agents/modules/generated/barcodes_gs1_nomenclature.yaml)
- Domain: `inventory_purchase`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/barcodes_gs1_nomenclature)
- Direct dependencies: [`barcodes`](../barcodes/overview.md), [`uom`](../uom/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`stock`](../stock/overview.md)
- Impact graph: [`module:barcodes_gs1_nomenclature`](../../impact-graph.json)

## Purpose

Parse barcodes according to the GS1-128 specifications

## Model relationships

- Extends `barcode.nomenclature` — defined by [`barcodes`](../barcodes/overview.md)
- Extends `barcode.rule` — defined by [`barcodes`](../barcodes/overview.md)
- Extends `ir.http` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.barcodes`](../../../agents/modules/generated/barcodes.yaml) — depends_on, extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — required_by
- [`module.uom`](../../../agents/modules/generated/uom.yaml) — depends_on

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`barcodes`](../barcodes/overview.md), [`base`](../base/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
