---
layout: page
title: "In-App Purchases (iap)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/iap/
nav_order: 0
---
# In-App Purchases — `iap`

**Source:** [`agents/modules/generated/iap.yaml`](../../agents/modules/generated/iap.yaml) · **Wiki:** [`knowledge/modules/iap/overview.md`](../../knowledge/modules/iap/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>iap</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">In-App Purchases</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">integrations</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/iap</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/iap"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Basic models and helpers to support In-App purchases.

## Direct dependencies

[`base_setup`](base_setup.md), [`web`](web.md)

## Reverse dependencies (modules that depend on this)

[`iap_mail`](iap_mail.md), [`l10n_fr_pdp`](l10n_fr_pdp.md), [`l10n_in_edi`](l10n_in_edi.md), [`mail_plugin`](mail_plugin.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>iap.account</code></div><div class="role">defined by <code>iap</code></div></div>
<div class="model"><div class="name"><code>iap.account.info</code></div><div class="role">defined by <code>iap</code></div></div>
<div class="model"><div class="name"><code>iap.enrich.api</code></div><div class="role">defined by <code>iap</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base_setup` | depends_on | `agents/modules/generated/base_setup.yaml` |
| `module.iap_mail` | model_extended_by, required_by | `agents/modules/generated/iap_mail.yaml` |
| `module.l10n_fr_pdp` | required_by | `agents/modules/generated/l10n_fr_pdp.yaml` |
| `module.l10n_in_edi` | required_by | `agents/modules/generated/l10n_in_edi.yaml` |
| `module.mail_plugin` | required_by | `agents/modules/generated/mail_plugin.yaml` |
| `module.web` | depends_on | `agents/modules/generated/web.yaml` |

## Full wiki excerpt

- SME owner: [`module.iap`](../../../agents/modules/generated/iap.yaml)
- Domain: `integrations`
- Category: Hidden/Tools
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/iap)
- Direct dependencies: [`base_setup`](../base_setup/overview.md), [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`iap_mail`](../iap_mail/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_in_edi`](../l10n_in_edi/overview.md), [`mail_plugin`](../mail_plugin/overview.md)
- Impact graph: [`module:iap`](../../impact-graph.json)

## Purpose

Basic models and helpers to support In-App purchases.

## Model relationships

- `iap.account` — extended by [`iap_mail`](../iap_mail/overview.md)
- `iap.account.info`
- `iap.enrich.api`

## Related SME agents

- [`module.base_setup`](../../../agents/modules/generated/base_setup.yaml) — depends_on
- [`module.iap_mail`](../../../agents/modules/generated/iap_mail.yaml) — model_extended_by, required_by
- [`module.l10n_fr_pdp`](../../../agents/modules/generated/l10n_fr_pdp.yaml) — required_by
- [`module.l10n_in_edi`](../../../agents/modules/generated/l10n_in_edi.yaml) — required_by
- [`module.mail_plugin`](../../../agents/modules/generated/mail_plugin.yaml) — required_by
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on

## Regression impact checklist

- Review 4 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`iap_mail`](../iap_mail/overview.md).
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
