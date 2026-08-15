---
layout: page
title: "France - FEC Export (l10n_fr_fec)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_fr_fec/
nav_order: 0
---
# France - FEC Export — `l10n_fr_fec`

**Source:** [`agents/modules/generated/l10n_fr_fec.yaml`](../../agents/modules/generated/l10n_fr_fec.yaml) · **Wiki:** [`knowledge/modules/l10n_fr_fec/overview.md`](../../knowledge/modules/l10n_fr_fec/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_fr_fec</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">France - FEC Export</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_fr_fec</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_fr_fec"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Fichier d'Échange Informatisé (FEC) for France

## Direct dependencies

[`account`](account.md), [`l10n_fr`](l10n_fr.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.fr.fec</code></div><div class="role">defined by <code>l10n_fr_fec</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on | `agents/modules/generated/account.yaml` |
| `module.l10n_fr` | depends_on | `agents/modules/generated/l10n_fr.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_fr_fec`](../../../agents/modules/generated/l10n_fr_fec.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/Reporting
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_fr_fec)
- Direct dependencies: [`account`](../account/overview.md), [`l10n_fr`](../l10n_fr/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_fr_fec`](../../impact-graph.json)

## Purpose

Fichier d'Échange Informatisé (FEC) for France

## Model relationships

- `account.fr.fec`

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on
- [`module.l10n_fr`](../../../agents/modules/generated/l10n_fr.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer, security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
