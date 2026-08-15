---
layout: page
title: "Vantiv Payment Services (pos_mercury)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/pos_mercury/
nav_order: 0
---
# Vantiv Payment Services — `pos_mercury`

**Source:** [`agents/modules/generated/pos_mercury.yaml`](../../agents/modules/generated/pos_mercury.yaml) · **Wiki:** [`knowledge/modules/pos_mercury/overview.md`](../../knowledge/modules/pos_mercury/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>pos_mercury</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Vantiv Payment Services</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">point_of_sale</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/pos_mercury</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_mercury"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Credit card support for Point Of Sale

## Direct dependencies

[`barcodes`](barcodes.md), [`point_of_sale`](point_of_sale.md), [`web`](web.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>pos_mercury.configuration</code></div><div class="role">defined by <code>pos_mercury</code></div></div>
<div class="model"><div class="name"><code>pos_mercury.mercury_transaction</code></div><div class="role">defined by <code>pos_mercury</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>barcode.rule</code></div><div class="role">extended by <code>pos_mercury</code></div></div>
<div class="model"><div class="name"><code>pos.order</code></div><div class="role">extended by <code>pos_mercury</code></div></div>
<div class="model"><div class="name"><code>pos.payment</code></div><div class="role">extended by <code>pos_mercury</code></div></div>
<div class="model"><div class="name"><code>pos.payment.method</code></div><div class="role">extended by <code>pos_mercury</code></div></div>
<div class="model"><div class="name"><code>pos.session</code></div><div class="role">extended by <code>pos_mercury</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.barcodes` | depends_on, extends_model_from | `agents/modules/generated/barcodes.yaml` |
| `module.l10n_ch_pos` | extends_model_from | `agents/modules/generated/l10n_ch_pos.yaml` |
| `module.point_of_sale` | depends_on, extends_model_from | `agents/modules/generated/point_of_sale.yaml` |
| `module.web` | depends_on | `agents/modules/generated/web.yaml` |

## Full wiki excerpt

- SME owner: [`module.pos_mercury`](../../../agents/modules/generated/pos_mercury.yaml)
- Domain: `point_of_sale`
- Category: Sales/Point of Sale
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_mercury)
- Direct dependencies: [`barcodes`](../barcodes/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:pos_mercury`](../../impact-graph.json)

## Purpose

Credit card support for Point Of Sale

## Model relationships

- `pos_mercury.configuration`
- `pos_mercury.mercury_transaction`
- Extends `barcode.rule` — defined by [`barcodes`](../barcodes/overview.md)
- Extends `pos.order` — defined by [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.payment` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.payment.method` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.session` — defined by [`point_of_sale`](../point_of_sale/overview.md)

## Related SME agents

- [`module.barcodes`](../../../agents/modules/generated/barcodes.yaml) — depends_on, extends_model_from
- [`module.l10n_ch_pos`](../../../agents/modules/generated/l10n_ch_pos.yaml) — extends_model_from
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — depends_on, extends_model_from
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`barcodes`](../barcodes/overview.md), [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`point_of_sale`](../point_of_sale/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
