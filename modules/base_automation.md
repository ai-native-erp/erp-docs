---
layout: page
title: "Automation Rules (base_automation)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/base_automation/
nav_order: 0
---
# Automation Rules — `base_automation`

**Source:** [`agents/modules/generated/base_automation.yaml`](../../agents/modules/generated/base_automation.yaml) · **Wiki:** [`knowledge/modules/base_automation/overview.md`](../../knowledge/modules/base_automation/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base_automation</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Automation Rules</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/base_automation</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/base_automation"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base`](base.md), [`mail`](mail.md), [`resource`](resource.md), [`sms`](sms.md)

## Reverse dependencies (modules that depend on this)

[`test_base_automation`](test_base_automation.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>base.automation</code></div><div class="role">defined by <code>base_automation</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | depends_on | `agents/modules/generated/base.yaml` |
| `module.mail` | depends_on | `agents/modules/generated/mail.yaml` |
| `module.resource` | depends_on | `agents/modules/generated/resource.yaml` |
| `module.sms` | depends_on | `agents/modules/generated/sms.yaml` |
| `module.test_base_automation` | required_by | `agents/modules/generated/test_base_automation.yaml` |

## Full wiki excerpt

- SME owner: [`module.base_automation`](../../../agents/modules/generated/base_automation.yaml)
- Domain: `platform_core`
- Category: Sales/Sales
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/base_automation)
- Direct dependencies: [`base`](../base/overview.md), [`mail`](../mail/overview.md), [`resource`](../resource/overview.md), [`sms`](../sms/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_base_automation`](../test_base_automation/overview.md)
- Impact graph: [`module:base_automation`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `base.automation`

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on
- [`module.resource`](../../../agents/modules/generated/resource.yaml) — depends_on
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — depends_on
- [`module.test_base_automation`](../../../agents/modules/generated/test_base_automation.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
