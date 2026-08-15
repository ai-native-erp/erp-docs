---
layout: page
title: "Test - Base Automation (test_base_automation)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_base_automation/
nav_order: 0
---
# Test - Base Automation — `test_base_automation`

**Source:** [`agents/modules/generated/test_base_automation.yaml`](../../agents/modules/generated/test_base_automation.yaml) · **Wiki:** [`knowledge/modules/test_base_automation/overview.md`](../../knowledge/modules/test_base_automation/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_base_automation</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Test - Base Automation</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/test_base_automation</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_base_automation"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Base Automation Tests: Ensure Flow Robustness

## Direct dependencies

[`base_automation`](base_automation.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>base.automation.lead.test</code></div><div class="role">defined by <code>test_base_automation</code></div></div>
<div class="model"><div class="name"><code>base.automation.lead.thread.test</code></div><div class="role">defined by <code>test_base_automation</code></div></div>
<div class="model"><div class="name"><code>base.automation.line.test</code></div><div class="role">defined by <code>test_base_automation</code></div></div>
<div class="model"><div class="name"><code>base.automation.link.test</code></div><div class="role">defined by <code>test_base_automation</code></div></div>
<div class="model"><div class="name"><code>base.automation.linked.test</code></div><div class="role">defined by <code>test_base_automation</code></div></div>
<div class="model"><div class="name"><code>base.automation.model.with.recname.char</code></div><div class="role">defined by <code>test_base_automation</code></div></div>
<div class="model"><div class="name"><code>base.automation.model.with.recname.m2o</code></div><div class="role">defined by <code>test_base_automation</code></div></div>
<div class="model"><div class="name"><code>test_base_automation.project</code></div><div class="role">defined by <code>test_base_automation</code></div></div>
<div class="model"><div class="name"><code>test_base_automation.stage</code></div><div class="role">defined by <code>test_base_automation</code></div></div>
<div class="model"><div class="name"><code>test_base_automation.tag</code></div><div class="role">defined by <code>test_base_automation</code></div></div>
<div class="model"><div class="name"><code>test_base_automation.task</code></div><div class="role">defined by <code>test_base_automation</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>base.automation.lead.test</code></div><div class="role">extended by <code>test_base_automation</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>test_base_automation</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base_automation` | depends_on | `agents/modules/generated/base_automation.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_base_automation`](../../../agents/modules/generated/test_base_automation.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_base_automation)
- Direct dependencies: [`base_automation`](../base_automation/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_base_automation`](../../impact-graph.json)

## Purpose

Base Automation Tests: Ensure Flow Robustness

## Model relationships

- `base.automation.lead.test`
- `base.automation.lead.thread.test`
- `base.automation.line.test`
- `base.automation.link.test`
- `base.automation.linked.test`
- `base.automation.model.with.recname.char`
- `base.automation.model.with.recname.m2o`
- `test_base_automation.project`
- `test_base_automation.stage`
- `test_base_automation.tag`
- `test_base_automation.task`
- Extends `base.automation.lead.test` — framework/dynamic owner
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)

## Related SME agents

- [`module.base_automation`](../../../agents/modules/generated/base_automation.yaml) — depends_on
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`mail`](../mail/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
