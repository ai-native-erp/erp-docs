---
layout: page
title: "Google places autocompletion (website_sale_autocomplete)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_sale_autocomplete/
nav_order: 0
---
# Google places autocompletion — `website_sale_autocomplete`

**Source:** [`agents/modules/generated/website_sale_autocomplete.yaml`](../../agents/modules/generated/website_sale_autocomplete.yaml) · **Wiki:** [`knowledge/modules/website_sale_autocomplete/overview.md`](../../knowledge/modules/website_sale_autocomplete/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_sale_autocomplete</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Google places autocompletion</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_sale_autocomplete</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_sale_autocomplete"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Assist your users with automatic completion & suggestions when filling their address during checkout

## Direct dependencies

[`website_sale`](website_sale.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>website_sale_autocomplete</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>website_sale_autocomplete</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.website` | extends_model_from | `agents/modules/generated/website.yaml` |
| `module.website_sale` | depends_on | `agents/modules/generated/website_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_sale_autocomplete`](../../../agents/modules/generated/website_sale_autocomplete.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_sale_autocomplete)
- Direct dependencies: [`website_sale`](../website_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:website_sale_autocomplete`](../../impact-graph.json)

## Purpose

Assist your users with automatic completion & suggestions when filling their address during checkout

## Model relationships

- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `website` — defined by [`website`](../website/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`website`](../website/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
