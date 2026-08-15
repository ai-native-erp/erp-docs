---
layout: page
title: "Twitter Snippet (website_twitter)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_twitter/
nav_order: 0
---
# Twitter Snippet — `website_twitter`

**Source:** [`agents/modules/generated/website_twitter.yaml`](../../agents/modules/generated/website_twitter.yaml) · **Wiki:** [`knowledge/modules/website_twitter/overview.md`](../../knowledge/modules/website_twitter/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_twitter</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Twitter Snippet</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_twitter</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_twitter"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Twitter scroller snippet in website

## Direct dependencies

[`website`](website.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>website.twitter.tweet</code></div><div class="role">defined by <code>website_twitter</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>website_twitter</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>website_twitter</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.website` | depends_on, extends_model_from | `agents/modules/generated/website.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_twitter`](../../../agents/modules/generated/website_twitter.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_twitter)
- Direct dependencies: [`website`](../website/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:website_twitter`](../../impact-graph.json)

## Purpose

Twitter scroller snippet in website

## Model relationships

- `website.twitter.tweet`
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `website` — defined by [`website`](../website/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`website`](../website/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
