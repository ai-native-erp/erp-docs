---
layout: page
title: "l10n_be_pos_sale (l10n_be_pos_sale)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_be_pos_sale/
nav_order: 0
---
# l10n_be_pos_sale — `l10n_be_pos_sale`

**Source:** [`agents/modules/generated/l10n_be_pos_sale.yaml`](../../agents/modules/generated/l10n_be_pos_sale.yaml) · **Wiki:** [`knowledge/modules/l10n_be_pos_sale/overview.md`](../../knowledge/modules/l10n_be_pos_sale/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_be_pos_sale</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">l10n_be_pos_sale</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_be_pos_sale</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_be_pos_sale"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Link module between pos_sale and l10n_be

## Direct dependencies

[`l10n_be`](l10n_be.md), [`pos_sale`](pos_sale.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>pos.session</code></div><div class="role">extended by <code>l10n_be_pos_sale</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.l10n_be` | depends_on | `agents/modules/generated/l10n_be.yaml` |
| `module.point_of_sale` | extends_model_from | `agents/modules/generated/point_of_sale.yaml` |
| `module.pos_sale` | depends_on | `agents/modules/generated/pos_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_be_pos_sale`](../../../agents/modules/generated/l10n_be_pos_sale.yaml)
- Domain: `localization`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_be_pos_sale)
- Direct dependencies: [`l10n_be`](../l10n_be/overview.md), [`pos_sale`](../pos_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_be_pos_sale`](../../impact-graph.json)

## Purpose

Link module between pos_sale and l10n_be

## Model relationships

- Extends `pos.session` — defined by [`point_of_sale`](../point_of_sale/overview.md)

## Related SME agents

- [`module.l10n_be`](../../../agents/modules/generated/l10n_be.yaml) — depends_on
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — extends_model_from
- [`module.pos_sale`](../../../agents/modules/generated/pos_sale.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`point_of_sale`](../point_of_sale/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
