---
layout: page
title: "Website Modules Test (test_website_modules)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_website_modules/
nav_order: 0
---
# Website Modules Test — `test_website_modules`

**Source:** [`agents/modules/generated/test_website_modules.yaml`](../../agents/modules/generated/test_website_modules.yaml) · **Wiki:** [`knowledge/modules/test_website_modules/overview.md`](../../knowledge/modules/test_website_modules/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_website_modules</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Website Modules Test</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/test_website_modules</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_website_modules"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`theme_default`](theme_default.md), [`website`](website.md), [`website_blog`](website_blog.md), [`website_event_sale`](website_event_sale.md), [`website_slides`](website_slides.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.theme_default` | depends_on | `agents/modules/generated/theme_default.yaml` |
| `module.website` | depends_on | `agents/modules/generated/website.yaml` |
| `module.website_blog` | depends_on | `agents/modules/generated/website_blog.yaml` |
| `module.website_event_sale` | depends_on | `agents/modules/generated/website_event_sale.yaml` |
| `module.website_slides` | depends_on | `agents/modules/generated/website_slides.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_website_modules`](../../../agents/modules/generated/test_website_modules.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_website_modules)
- Direct dependencies: [`theme_default`](../theme_default/overview.md), [`website`](../website/overview.md), [`website_blog`](../website_blog/overview.md), [`website_event_sale`](../website_event_sale/overview.md), [`website_slides`](../website_slides/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_website_modules`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.theme_default`](../../../agents/modules/generated/theme_default.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — depends_on
- [`module.website_blog`](../../../agents/modules/generated/website_blog.yaml) — depends_on
- [`module.website_event_sale`](../../../agents/modules/generated/website_event_sale.yaml) — depends_on
- [`module.website_slides`](../../../agents/modules/generated/website_slides.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
