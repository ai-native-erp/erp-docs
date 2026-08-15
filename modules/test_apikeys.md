---
layout: page
title: "Tests flow of API keys (test_apikeys)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_apikeys/
nav_order: 0
---
# Tests flow of API keys — `test_apikeys`

**Source:** [`agents/modules/generated/test_apikeys.yaml`](../../agents/modules/generated/test_apikeys.yaml) · **Wiki:** [`knowledge/modules/test_apikeys/overview.md`](../../knowledge/modules/test_apikeys/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_apikeys</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Tests flow of API keys</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>odoo/addons/test_apikeys</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_apikeys"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`auth_totp`](auth_totp.md), [`web_tour`](web_tour.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.auth_totp` | depends_on | `agents/modules/generated/auth_totp.yaml` |
| `module.web_tour` | depends_on | `agents/modules/generated/web_tour.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_apikeys`](../../../agents/modules/generated/test_apikeys.yaml)
- Domain: `platform_core`
- Category: Tools
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_apikeys)
- Direct dependencies: [`auth_totp`](../auth_totp/overview.md), [`web_tour`](../web_tour/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_apikeys`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.auth_totp`](../../../agents/modules/generated/auth_totp.yaml) — depends_on
- [`module.web_tour`](../../../agents/modules/generated/web_tour.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
