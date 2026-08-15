---
layout: page
title: "Malta - Point of Sale (l10n_mt_pos)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_mt_pos/
nav_order: 0
---
# Malta - Point of Sale — `l10n_mt_pos`

**Source:** [`agents/modules/generated/l10n_mt_pos.yaml`](../../agents/modules/generated/l10n_mt_pos.yaml) · **Wiki:** [`knowledge/modules/l10n_mt_pos/overview.md`](../../knowledge/modules/l10n_mt_pos/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_mt_pos</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Malta - Point of Sale</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_mt_pos</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_mt_pos"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`point_of_sale`](point_of_sale.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>compliance.letter.wizard</code></div><div class="role">defined by <code>l10n_mt_pos</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.point_of_sale` | depends_on | `agents/modules/generated/point_of_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_mt_pos`](../../../agents/modules/generated/l10n_mt_pos.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/Point of Sale
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_mt_pos)
- Direct dependencies: [`point_of_sale`](../point_of_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_mt_pos`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `compliance.letter.wizard`

## Related SME agents

- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
