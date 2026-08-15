---
layout: page
title: "Manufacturing Expiry (mrp_product_expiry)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/mrp_product_expiry/
nav_order: 0
---
# Manufacturing Expiry — `mrp_product_expiry`

**Source:** [`agents/modules/generated/mrp_product_expiry.yaml`](../../agents/modules/generated/mrp_product_expiry.yaml) · **Wiki:** [`knowledge/modules/mrp_product_expiry/overview.md`](../../knowledge/modules/mrp_product_expiry/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>mrp_product_expiry</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Manufacturing Expiry</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">manufacturing</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/mrp_product_expiry</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mrp_product_expiry"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Manufacturing Expiry

## Direct dependencies

[`mrp`](mrp.md), [`product_expiry`](product_expiry.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>expiry.picking.confirmation</code></div><div class="role">extended by <code>mrp_product_expiry</code></div></div>
<div class="model"><div class="name"><code>mrp.production</code></div><div class="role">extended by <code>mrp_product_expiry</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mrp` | depends_on, extends_model_from | `agents/modules/generated/mrp.yaml` |
| `module.mrp_account` | extends_model_from | `agents/modules/generated/mrp_account.yaml` |
| `module.product_expiry` | depends_on, extends_model_from | `agents/modules/generated/product_expiry.yaml` |

## Full wiki excerpt

- SME owner: [`module.mrp_product_expiry`](../../../agents/modules/generated/mrp_product_expiry.yaml)
- Domain: `manufacturing`
- Category: Manufacturing/Manufacturing
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mrp_product_expiry)
- Direct dependencies: [`mrp`](../mrp/overview.md), [`product_expiry`](../product_expiry/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:mrp_product_expiry`](../../impact-graph.json)

## Purpose

Manufacturing Expiry

## Model relationships

- Extends `expiry.picking.confirmation` — defined by [`product_expiry`](../product_expiry/overview.md)
- Extends `mrp.production` — defined by [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md)

## Related SME agents

- [`module.mrp`](../../../agents/modules/generated/mrp.yaml) — depends_on, extends_model_from
- [`module.mrp_account`](../../../agents/modules/generated/mrp_account.yaml) — extends_model_from
- [`module.product_expiry`](../../../agents/modules/generated/product_expiry.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`mrp`](../mrp/overview.md), [`mrp_account`](../mrp_account/overview.md), [`product_expiry`](../product_expiry/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
