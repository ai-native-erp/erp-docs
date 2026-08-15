---
layout: page
title: "Link Tracker (website_links)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_links/
nav_order: 0
---
# Link Tracker — `website_links`

**Source:** [`agents/modules/generated/website_links.yaml`](../../agents/modules/generated/website_links.yaml) · **Wiki:** [`knowledge/modules/website_links/overview.md`](../../knowledge/modules/website_links/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_links</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Link Tracker</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_links</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_links"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Generate trackable & short URLs

## Direct dependencies

[`link_tracker`](link_tracker.md), [`website`](website.md)

## Reverse dependencies (modules that depend on this)

[`website_sale_loyalty`](website_sale_loyalty.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>link.tracker</code></div><div class="role">extended by <code>website_links</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.link_tracker` | depends_on, extends_model_from | `agents/modules/generated/link_tracker.yaml` |
| `module.website` | depends_on | `agents/modules/generated/website.yaml` |
| `module.website_sale_loyalty` | required_by | `agents/modules/generated/website_sale_loyalty.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_links`](../../../agents/modules/generated/website_links.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_links)
- Direct dependencies: [`link_tracker`](../link_tracker/overview.md), [`website`](../website/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`website_sale_loyalty`](../website_sale_loyalty/overview.md)
- Impact graph: [`module:website_links`](../../impact-graph.json)

## Purpose

Generate trackable & short URLs

## Model relationships

- Extends `link.tracker` — defined by [`link_tracker`](../link_tracker/overview.md)

## Related SME agents

- [`module.link_tracker`](../../../agents/modules/generated/link_tracker.yaml) — depends_on, extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — depends_on
- [`module.website_sale_loyalty`](../../../agents/modules/generated/website_sale_loyalty.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`link_tracker`](../link_tracker/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
