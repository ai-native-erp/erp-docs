---
layout: page
title: "Portal Rating (portal_rating)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/portal_rating/
nav_order: 0
---
# Portal Rating — `portal_rating`

**Source:** [`agents/modules/generated/portal_rating.yaml`](../../agents/modules/generated/portal_rating.yaml) · **Wiki:** [`knowledge/modules/portal_rating/overview.md`](../../knowledge/modules/portal_rating/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>portal_rating</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Portal Rating</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/portal_rating</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/portal_rating"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`portal`](portal.md), [`rating`](rating.md)

## Reverse dependencies (modules that depend on this)

[`website_sale`](website_sale.md), [`website_slides`](website_slides.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>portal_rating</code></div></div>
<div class="model"><div class="name"><code>mail.message</code></div><div class="role">extended by <code>portal_rating</code></div></div>
<div class="model"><div class="name"><code>rating.rating</code></div><div class="role">extended by <code>portal_rating</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.portal` | depends_on | `agents/modules/generated/portal.yaml` |
| `module.rating` | depends_on, extends_model_from | `agents/modules/generated/rating.yaml` |
| `module.website_sale` | required_by | `agents/modules/generated/website_sale.yaml` |
| `module.website_slides` | required_by | `agents/modules/generated/website_slides.yaml` |

## Full wiki excerpt

- SME owner: [`module.portal_rating`](../../../agents/modules/generated/portal_rating.yaml)
- Domain: `website_ecommerce`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/portal_rating)
- Direct dependencies: [`portal`](../portal/overview.md), [`rating`](../rating/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`website_sale`](../website_sale/overview.md), [`website_slides`](../website_slides/overview.md)
- Impact graph: [`module:portal_rating`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `mail.message` — defined by [`mail`](../mail/overview.md)
- Extends `rating.rating` — defined by [`rating`](../rating/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — depends_on
- [`module.rating`](../../../agents/modules/generated/rating.yaml) — depends_on, extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — required_by
- [`module.website_slides`](../../../agents/modules/generated/website_slides.yaml) — required_by

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`mail`](../mail/overview.md), [`rating`](../rating/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
