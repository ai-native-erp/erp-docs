---
layout: page
title: "Password Policy support for Signup (auth_password_policy_signup)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/auth_password_policy_signup/
nav_order: 0
---
# Password Policy support for Signup — `auth_password_policy_signup`

**Source:** [`agents/modules/generated/auth_password_policy_signup.yaml`](../../agents/modules/generated/auth_password_policy_signup.yaml) · **Wiki:** [`knowledge/modules/auth_password_policy_signup/overview.md`](../../knowledge/modules/auth_password_policy_signup/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>auth_password_policy_signup</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Password Policy support for Signup</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/auth_password_policy_signup</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/auth_password_policy_signup"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`auth_password_policy`](auth_password_policy.md), [`auth_signup`](auth_signup.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.auth_password_policy` | depends_on | `agents/modules/generated/auth_password_policy.yaml` |
| `module.auth_signup` | depends_on | `agents/modules/generated/auth_signup.yaml` |

## Full wiki excerpt

- SME owner: [`module.auth_password_policy_signup`](../../../agents/modules/generated/auth_password_policy_signup.yaml)
- Domain: `platform_core`
- Category: Hidden/Tools
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/auth_password_policy_signup)
- Direct dependencies: [`auth_password_policy`](../auth_password_policy/overview.md), [`auth_signup`](../auth_signup/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:auth_password_policy_signup`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.auth_password_policy`](../../../agents/modules/generated/auth_password_policy.yaml) — depends_on
- [`module.auth_signup`](../../../agents/modules/generated/auth_signup.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
