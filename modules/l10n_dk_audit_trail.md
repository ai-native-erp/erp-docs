---
layout: page
title: "Denmark - audit trail (l10n_dk_audit_trail)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_dk_audit_trail/
nav_order: 0
---
# Denmark - audit trail — `l10n_dk_audit_trail`

**Source:** [`agents/modules/generated/l10n_dk_audit_trail.yaml`](../../agents/modules/generated/l10n_dk_audit_trail.yaml) · **Wiki:** [`knowledge/modules/l10n_dk_audit_trail/overview.md`](../../knowledge/modules/l10n_dk_audit_trail/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_dk_audit_trail</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Denmark - audit trail</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_dk_audit_trail</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_dk_audit_trail"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Audit trail

## Direct dependencies

[`account_audit_trail`](account_audit_trail.md), [`l10n_dk`](l10n_dk.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account_audit_trail` | depends_on | `agents/modules/generated/account_audit_trail.yaml` |
| `module.l10n_dk` | depends_on | `agents/modules/generated/l10n_dk.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_dk_audit_trail`](../../../agents/modules/generated/l10n_dk_audit_trail.yaml)
- Domain: `localization`
- Category: Uncategorized
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_dk_audit_trail)
- Direct dependencies: [`account_audit_trail`](../account_audit_trail/overview.md), [`l10n_dk`](../l10n_dk/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_dk_audit_trail`](../../impact-graph.json)

## Purpose

Audit trail

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.account_audit_trail`](../../../agents/modules/generated/account_audit_trail.yaml) — depends_on
- [`module.l10n_dk`](../../../agents/modules/generated/l10n_dk.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
