---
layout: page
title: "Product Availability Notifications (website_sale_comparison_wishlist)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_sale_comparison_wishlist/
nav_order: 0
---
# Product Availability Notifications — `website_sale_comparison_wishlist`

**Source:** [`agents/modules/generated/website_sale_comparison_wishlist.yaml`](../../agents/modules/generated/website_sale_comparison_wishlist.yaml) · **Wiki:** [`knowledge/modules/website_sale_comparison_wishlist/overview.md`](../../knowledge/modules/website_sale_comparison_wishlist/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_sale_comparison_wishlist</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Product Availability Notifications</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_sale_comparison_wishlist</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_sale_comparison_wishlist"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Bridge module for Website sale comparison and wishlist

## Direct dependencies

[`website_sale_comparison`](website_sale_comparison.md), [`website_sale_wishlist`](website_sale_wishlist.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.website_sale_comparison` | depends_on | `agents/modules/generated/website_sale_comparison.yaml` |
| `module.website_sale_wishlist` | depends_on | `agents/modules/generated/website_sale_wishlist.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_sale_comparison_wishlist`](../../../agents/modules/generated/website_sale_comparison_wishlist.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_sale_comparison_wishlist)
- Direct dependencies: [`website_sale_comparison`](../website_sale_comparison/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:website_sale_comparison_wishlist`](../../impact-graph.json)

## Purpose

Bridge module for Website sale comparison and wishlist

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.website_sale_comparison`](../../../agents/modules/generated/website_sale_comparison.yaml) — depends_on
- [`module.website_sale_wishlist`](../../../agents/modules/generated/website_sale_wishlist.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
