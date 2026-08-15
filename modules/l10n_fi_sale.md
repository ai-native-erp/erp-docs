---
layout: page
title: "Finland - Sale (l10n_fi_sale)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_fi_sale/
nav_order: 0
---
# Finland - Sale — `l10n_fi_sale`

**Source:** [`agents/modules/generated/l10n_fi_sale.yaml`](../../agents/modules/generated/l10n_fi_sale.yaml) · **Wiki:** [`knowledge/modules/l10n_fi_sale/overview.md`](../../knowledge/modules/l10n_fi_sale/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_fi_sale</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Finland - Sale</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_fi_sale</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_fi_sale"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`l10n_fi`](l10n_fi.md), [`sale`](sale.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>l10n_fi_sale</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.l10n_fi` | depends_on | `agents/modules/generated/l10n_fi.yaml` |
| `module.sale` | depends_on, extends_model_from | `agents/modules/generated/sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_fi_sale`](../../../agents/modules/generated/l10n_fi_sale.yaml)
- Domain: `localization`
- Category: Localization
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_fi_sale)
- Direct dependencies: [`l10n_fi`](../l10n_fi/overview.md), [`sale`](../sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_fi_sale`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `sale.order` — defined by [`sale`](../sale/overview.md)

## Related SME agents

- [`module.l10n_fi`](../../../agents/modules/generated/l10n_fi.yaml) — depends_on
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`sale`](../sale/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
