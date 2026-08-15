---
layout: page
title: "China - City Data (l10n_cn_city)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_cn_city/
nav_order: 0
---
# China - City Data — `l10n_cn_city`

**Source:** [`agents/modules/generated/l10n_cn_city.yaml`](../../agents/modules/generated/l10n_cn_city.yaml) · **Wiki:** [`knowledge/modules/l10n_cn_city/overview.md`](../../knowledge/modules/l10n_cn_city/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_cn_city</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">China - City Data</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_cn_city</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_cn_city"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base_address_extended`](base_address_extended.md), [`l10n_cn`](l10n_cn.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base_address_extended` | depends_on | `agents/modules/generated/base_address_extended.yaml` |
| `module.l10n_cn` | depends_on | `agents/modules/generated/l10n_cn.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_cn_city`](../../../agents/modules/generated/l10n_cn_city.yaml)
- Domain: `localization`
- Category: Accounting/Localizations
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_cn_city)
- Direct dependencies: [`base_address_extended`](../base_address_extended/overview.md), [`l10n_cn`](../l10n_cn/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_cn_city`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.base_address_extended`](../../../agents/modules/generated/base_address_extended.yaml) — depends_on
- [`module.l10n_cn`](../../../agents/modules/generated/l10n_cn.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
