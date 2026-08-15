---
layout: page
title: "Website Test (test_website)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_website/
nav_order: 0
---
# Website Test — `test_website`

**Source:** [`agents/modules/generated/test_website.yaml`](../../agents/modules/generated/test_website.yaml) · **Wiki:** [`knowledge/modules/test_website/overview.md`](../../knowledge/modules/test_website/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_website</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Website Test</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/test_website</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_website"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Website Test, mainly for module install/uninstall tests

## Direct dependencies

[`theme_default`](theme_default.md), [`web_unsplash`](web_unsplash.md), [`website`](website.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>test.model</code></div><div class="role">defined by <code>test_website</code></div></div>
<div class="model"><div class="name"><code>test.model.exposed</code></div><div class="role">defined by <code>test_website</code></div></div>
<div class="model"><div class="name"><code>test.model.multi.website</code></div><div class="role">defined by <code>test_website</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>test_website</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>test_website</code></div></div>
<div class="model"><div class="name"><code>website.published.mixin</code></div><div class="role">extended by <code>test_website</code></div></div>
<div class="model"><div class="name"><code>website.published.multi.mixin</code></div><div class="role">extended by <code>test_website</code></div></div>
<div class="model"><div class="name"><code>website.searchable.mixin</code></div><div class="role">extended by <code>test_website</code></div></div>
<div class="model"><div class="name"><code>website.seo.metadata</code></div><div class="role">extended by <code>test_website</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.theme_default` | depends_on | `agents/modules/generated/theme_default.yaml` |
| `module.web_unsplash` | depends_on | `agents/modules/generated/web_unsplash.yaml` |
| `module.website` | depends_on, extends_model_from | `agents/modules/generated/website.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_website`](../../../agents/modules/generated/test_website.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_website)
- Direct dependencies: [`theme_default`](../theme_default/overview.md), [`web_unsplash`](../web_unsplash/overview.md), [`website`](../website/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_website`](../../impact-graph.json)

## Purpose

Website Test, mainly for module install/uninstall tests

## Model relationships

- `test.model`
- `test.model.exposed`
- `test.model.multi.website`
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `website` — defined by [`website`](../website/overview.md)
- Extends `website.published.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.published.multi.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.searchable.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.seo.metadata` — defined by [`website`](../website/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.theme_default`](../../../agents/modules/generated/theme_default.yaml) — depends_on
- [`module.web_unsplash`](../../../agents/modules/generated/web_unsplash.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`website`](../website/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
