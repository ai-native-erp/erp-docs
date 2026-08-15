---
layout: page
title: "Test Performance (test_performance)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_performance/
nav_order: 0
---
# Test Performance — `test_performance`

**Source:** [`agents/modules/generated/test_performance.yaml`](../../agents/modules/generated/test_performance.yaml) · **Wiki:** [`knowledge/modules/test_performance/overview.md`](../../knowledge/modules/test_performance/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_performance</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Test Performance</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>odoo/addons/test_performance</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_performance"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base`](base.md)

## Reverse dependencies (modules that depend on this)

[`test_mail`](test_mail.md), [`test_mail_sms`](test_mail_sms.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>test_performance.bacon</code></div><div class="role">defined by <code>test_performance</code></div></div>
<div class="model"><div class="name"><code>test_performance.base</code></div><div class="role">defined by <code>test_performance</code></div></div>
<div class="model"><div class="name"><code>test_performance.eggs</code></div><div class="role">defined by <code>test_performance</code></div></div>
<div class="model"><div class="name"><code>test_performance.line</code></div><div class="role">defined by <code>test_performance</code></div></div>
<div class="model"><div class="name"><code>test_performance.mozzarella</code></div><div class="role">defined by <code>test_performance</code></div></div>
<div class="model"><div class="name"><code>test_performance.tag</code></div><div class="role">defined by <code>test_performance</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | depends_on | `agents/modules/generated/base.yaml` |
| `module.test_mail` | required_by | `agents/modules/generated/test_mail.yaml` |
| `module.test_mail_sms` | required_by | `agents/modules/generated/test_mail_sms.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_performance`](../../../agents/modules/generated/test_performance.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_performance)
- Direct dependencies: [`base`](../base/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_mail`](../test_mail/overview.md), [`test_mail_sms`](../test_mail_sms/overview.md)
- Impact graph: [`module:test_performance`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `test_performance.bacon`
- `test_performance.base`
- `test_performance.eggs`
- `test_performance.line`
- `test_performance.mozzarella`
- `test_performance.tag`

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on
- [`module.test_mail`](../../../agents/modules/generated/test_mail.yaml) — required_by
- [`module.test_mail_sms`](../../../agents/modules/generated/test_mail_sms.yaml) — required_by

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
