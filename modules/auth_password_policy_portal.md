---
layout: page
title: "Password Policy support for Signup (auth_password_policy_portal)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/auth_password_policy_portal/
nav_order: 0
---
# Password Policy support for Signup — `auth_password_policy_portal`

**Source:** [`agents/modules/generated/auth_password_policy_portal.yaml`](../../agents/modules/generated/auth_password_policy_portal.yaml) · **Wiki:** [`knowledge/modules/auth_password_policy_portal/overview.md`](../../knowledge/modules/auth_password_policy_portal/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>auth_password_policy_portal</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Password Policy support for Signup</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/auth_password_policy_portal</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/auth_password_policy_portal"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`auth_password_policy`](auth_password_policy.md), [`portal`](portal.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.auth_password_policy` | depends_on | `agents/modules/generated/auth_password_policy.yaml` |
| `module.portal` | depends_on | `agents/modules/generated/portal.yaml` |

## Full wiki excerpt

- SME owner: [`module.auth_password_policy_portal`](../../../agents/modules/generated/auth_password_policy_portal.yaml)
- Domain: `platform_core`
- Category: Tools
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/auth_password_policy_portal)
- Direct dependencies: [`auth_password_policy`](../auth_password_policy/overview.md), [`portal`](../portal/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:auth_password_policy_portal`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.auth_password_policy`](../../../agents/modules/generated/auth_password_policy.yaml) — depends_on
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
