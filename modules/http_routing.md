---
layout: page
title: "Web Routing (http_routing)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/http_routing/
nav_order: 0
---
# Web Routing — `http_routing`

**Source:** [`agents/modules/generated/http_routing.yaml`](../../agents/modules/generated/http_routing.yaml) · **Wiki:** [`knowledge/modules/http_routing/overview.md`](../../knowledge/modules/http_routing/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>http_routing</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Web Routing</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/http_routing</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/http_routing"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Web Routing

## Direct dependencies

[`web`](web.md)

## Reverse dependencies (modules that depend on this)

[`portal`](portal.md), [`pos_self_order`](pos_self_order.md), [`survey`](survey.md), [`website`](website.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>http_routing</code></div></div>
<div class="model"><div class="name"><code>ir.qweb</code></div><div class="role">extended by <code>http_routing</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.portal` | required_by | `agents/modules/generated/portal.yaml` |
| `module.pos_self_order` | required_by | `agents/modules/generated/pos_self_order.yaml` |
| `module.survey` | required_by | `agents/modules/generated/survey.yaml` |
| `module.web` | depends_on | `agents/modules/generated/web.yaml` |
| `module.website` | required_by | `agents/modules/generated/website.yaml` |

## Full wiki excerpt

- SME owner: [`module.http_routing`](../../../agents/modules/generated/http_routing.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/http_routing)
- Direct dependencies: [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`portal`](../portal/overview.md), [`pos_self_order`](../pos_self_order/overview.md), [`survey`](../survey/overview.md), [`website`](../website/overview.md)
- Impact graph: [`module:http_routing`](../../impact-graph.json)

## Purpose

Web Routing

## Model relationships

- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `ir.qweb` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — required_by
- [`module.pos_self_order`](../../../agents/modules/generated/pos_self_order.yaml) — required_by
- [`module.survey`](../../../agents/modules/generated/survey.yaml) — required_by
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — required_by

## Regression impact checklist

- Review 4 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
