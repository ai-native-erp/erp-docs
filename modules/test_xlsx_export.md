---
layout: page
title: "test xlsx export (test_xlsx_export)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_xlsx_export/
nav_order: 0
---
# test xlsx export — `test_xlsx_export`

**Source:** [`agents/modules/generated/test_xlsx_export.yaml`](../../agents/modules/generated/test_xlsx_export.yaml) · **Wiki:** [`knowledge/modules/test_xlsx_export/overview.md`](../../knowledge/modules/test_xlsx_export/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_xlsx_export</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">test xlsx export</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/test_xlsx_export</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_xlsx_export"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`test_mail`](test_mail.md), [`web`](web.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>export.group_operator</code></div><div class="role">defined by <code>test_xlsx_export</code></div></div>
<div class="model"><div class="name"><code>export.group_operator.one2many</code></div><div class="role">defined by <code>test_xlsx_export</code></div></div>
<div class="model"><div class="name"><code>export.integer</code></div><div class="role">defined by <code>test_xlsx_export</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.test_mail` | depends_on | `agents/modules/generated/test_mail.yaml` |
| `module.web` | depends_on | `agents/modules/generated/web.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_xlsx_export`](../../../agents/modules/generated/test_xlsx_export.yaml)
- Domain: `platform_core`
- Category: Hidden/Tests
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_xlsx_export)
- Direct dependencies: [`test_mail`](../test_mail/overview.md), [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_xlsx_export`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `export.group_operator`
- `export.group_operator.one2many`
- `export.integer`

## Related SME agents

- [`module.test_mail`](../../../agents/modules/generated/test_mail.yaml) — depends_on
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
