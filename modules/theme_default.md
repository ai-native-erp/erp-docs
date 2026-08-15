---
layout: page
title: "Default Theme (theme_default)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/theme_default/
nav_order: 0
---
# Default Theme — `theme_default`

**Source:** [`agents/modules/generated/theme_default.yaml`](../../agents/modules/generated/theme_default.yaml) · **Wiki:** [`knowledge/modules/theme_default/overview.md`](../../knowledge/modules/theme_default/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>theme_default</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Default Theme</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/theme_default</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/theme_default"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`website`](website.md)

## Reverse dependencies (modules that depend on this)

[`test_website`](test_website.md), [`test_website_modules`](test_website_modules.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.test_website` | required_by | `agents/modules/generated/test_website.yaml` |
| `module.test_website_modules` | required_by | `agents/modules/generated/test_website_modules.yaml` |
| `module.website` | depends_on | `agents/modules/generated/website.yaml` |

## Full wiki excerpt

- SME owner: [`module.theme_default`](../../../agents/modules/generated/theme_default.yaml)
- Domain: `website_ecommerce`
- Category: Theme
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/theme_default)
- Direct dependencies: [`website`](../website/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_website`](../test_website/overview.md), [`test_website_modules`](../test_website_modules/overview.md)
- Impact graph: [`module:theme_default`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.test_website`](../../../agents/modules/generated/test_website.yaml) — required_by
- [`module.test_website_modules`](../../../agents/modules/generated/test_website_modules.yaml) — required_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — depends_on

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
