---
layout: page
title: "Cloudflare Turnstile (website_cf_turnstile)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_cf_turnstile/
nav_order: 0
---
# Cloudflare Turnstile — `website_cf_turnstile`

**Source:** [`agents/modules/generated/website_cf_turnstile.yaml`](../../agents/modules/generated/website_cf_turnstile.yaml) · **Wiki:** [`knowledge/modules/website_cf_turnstile/overview.md`](../../knowledge/modules/website_cf_turnstile/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_cf_turnstile</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Cloudflare Turnstile</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_cf_turnstile</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_cf_turnstile"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`website`](website.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>website_cf_turnstile</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>website_cf_turnstile</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.website` | depends_on | `agents/modules/generated/website.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_cf_turnstile`](../../../agents/modules/generated/website_cf_turnstile.yaml)
- Domain: `website_ecommerce`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_cf_turnstile)
- Direct dependencies: [`website`](../website/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:website_cf_turnstile`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
