---
layout: page
title: "POS Viva Wallet (pos_viva_wallet)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/pos_viva_wallet/
nav_order: 0
---
# POS Viva Wallet — `pos_viva_wallet`

**Source:** [`agents/modules/generated/pos_viva_wallet.yaml`](../../agents/modules/generated/pos_viva_wallet.yaml) · **Wiki:** [`knowledge/modules/pos_viva_wallet/overview.md`](../../knowledge/modules/pos_viva_wallet/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>pos_viva_wallet</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">POS Viva Wallet</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">point_of_sale</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/pos_viva_wallet</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_viva_wallet"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Integrate your POS with a Viva Wallet payment terminal

## Direct dependencies

[`point_of_sale`](point_of_sale.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>pos.payment.method</code></div><div class="role">extended by <code>pos_viva_wallet</code></div></div>
<div class="model"><div class="name"><code>pos.session</code></div><div class="role">extended by <code>pos_viva_wallet</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.point_of_sale` | depends_on, extends_model_from | `agents/modules/generated/point_of_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.pos_viva_wallet`](../../../agents/modules/generated/pos_viva_wallet.yaml)
- Domain: `point_of_sale`
- Category: Sales/Point of Sale
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/pos_viva_wallet)
- Direct dependencies: [`point_of_sale`](../point_of_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:pos_viva_wallet`](../../impact-graph.json)

## Purpose

Integrate your POS with a Viva Wallet payment terminal

## Model relationships

- Extends `pos.payment.method` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.session` — defined by [`point_of_sale`](../point_of_sale/overview.md)

## Related SME agents

- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`point_of_sale`](../point_of_sale/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
