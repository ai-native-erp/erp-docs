---
layout: page
title: "Saudi Arabia - Point of Sale (l10n_sa_pos)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_sa_pos/
nav_order: 0
---
# Saudi Arabia - Point of Sale — `l10n_sa_pos`

**Source:** [`agents/modules/generated/l10n_sa_pos.yaml`](../../agents/modules/generated/l10n_sa_pos.yaml) · **Wiki:** [`knowledge/modules/l10n_sa_pos/overview.md`](../../knowledge/modules/l10n_sa_pos/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_sa_pos</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Saudi Arabia - Point of Sale</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_sa_pos</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_sa_pos"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`l10n_gcc_pos`](l10n_gcc_pos.md), [`l10n_sa`](l10n_sa.md)

## Reverse dependencies (modules that depend on this)

[`l10n_sa_edi_pos`](l10n_sa_edi_pos.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>pos.config</code></div><div class="role">extended by <code>l10n_sa_pos</code></div></div>
<div class="model"><div class="name"><code>pos.order</code></div><div class="role">extended by <code>l10n_sa_pos</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.l10n_ch_pos` | extends_model_from | `agents/modules/generated/l10n_ch_pos.yaml` |
| `module.l10n_gcc_pos` | depends_on | `agents/modules/generated/l10n_gcc_pos.yaml` |
| `module.l10n_sa` | depends_on | `agents/modules/generated/l10n_sa.yaml` |
| `module.l10n_sa_edi_pos` | required_by | `agents/modules/generated/l10n_sa_edi_pos.yaml` |
| `module.point_of_sale` | extends_model_from | `agents/modules/generated/point_of_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_sa_pos`](../../../agents/modules/generated/l10n_sa_pos.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/Point of Sale
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_sa_pos)
- Direct dependencies: [`l10n_gcc_pos`](../l10n_gcc_pos/overview.md), [`l10n_sa`](../l10n_sa/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_sa_edi_pos`](../l10n_sa_edi_pos/overview.md)
- Impact graph: [`module:l10n_sa_pos`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `pos.config` — defined by [`point_of_sale`](../point_of_sale/overview.md)
- Extends `pos.order` — defined by [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`point_of_sale`](../point_of_sale/overview.md)

## Related SME agents

- [`module.l10n_ch_pos`](../../../agents/modules/generated/l10n_ch_pos.yaml) — extends_model_from
- [`module.l10n_gcc_pos`](../../../agents/modules/generated/l10n_gcc_pos.yaml) — depends_on
- [`module.l10n_sa`](../../../agents/modules/generated/l10n_sa.yaml) — depends_on
- [`module.l10n_sa_edi_pos`](../../../agents/modules/generated/l10n_sa_edi_pos.yaml) — required_by
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`l10n_ch_pos`](../l10n_ch_pos/overview.md), [`point_of_sale`](../point_of_sale/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
