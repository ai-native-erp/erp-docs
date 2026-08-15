---
layout: page
title: "Account Audit Trail (account_audit_trail)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/account_audit_trail/
nav_order: 0
---
# Account Audit Trail — `account_audit_trail`

**Source:** [`agents/modules/generated/account_audit_trail.yaml`](../../agents/modules/generated/account_audit_trail.yaml) · **Wiki:** [`knowledge/modules/account_audit_trail/overview.md`](../../knowledge/modules/account_audit_trail/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>account_audit_trail</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Account Audit Trail</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">accounting</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/account_audit_trail</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_audit_trail"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Account Audit Trail

## Direct dependencies

[`account`](account.md)

## Reverse dependencies (modules that depend on this)

[`l10n_de_audit_trail`](l10n_de_audit_trail.md), [`l10n_dk_audit_trail`](l10n_dk_audit_trail.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.bank.statement.line</code></div><div class="role">extended by <code>account_audit_trail</code></div></div>
<div class="model"><div class="name"><code>account.move</code></div><div class="role">extended by <code>account_audit_trail</code></div></div>
<div class="model"><div class="name"><code>base.partner.merge.automatic.wizard</code></div><div class="role">extended by <code>account_audit_trail</code></div></div>
<div class="model"><div class="name"><code>mail.message</code></div><div class="role">extended by <code>account_audit_trail</code></div></div>
<div class="model"><div class="name"><code>mail.tracking.value</code></div><div class="role">extended by <code>account_audit_trail</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>account_audit_trail</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>account_audit_trail</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | depends_on, extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.l10n_de_audit_trail` | required_by | `agents/modules/generated/l10n_de_audit_trail.yaml` |
| `module.l10n_dk_audit_trail` | required_by | `agents/modules/generated/l10n_dk_audit_trail.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.l10n_tr_nilvera_einvoice` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera_einvoice.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.partner_autocomplete` | extends_model_from | `agents/modules/generated/partner_autocomplete.yaml` |
| `module.sale` | extends_model_from | `agents/modules/generated/sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.account_audit_trail`](../../../agents/modules/generated/account_audit_trail.yaml)
- Domain: `accounting`
- Category: Accounting/Accounting
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/account_audit_trail)
- Direct dependencies: [`account`](../account/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`l10n_de_audit_trail`](../l10n_de_audit_trail/overview.md), [`l10n_dk_audit_trail`](../l10n_dk_audit_trail/overview.md)
- Impact graph: [`module:account_audit_trail`](../../impact-graph.json)

## Purpose

Account Audit Trail

## Model relationships

- Extends `account.bank.statement.line` — defined by [`account`](../account/overview.md)
- Extends `account.move` — defined by [`account`](../account/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`sale`](../sale/overview.md)
- Extends `base.partner.merge.automatic.wizard` — defined by [`base`](../base/overview.md)
- Extends `mail.message` — defined by [`mail`](../mail/overview.md)
- Extends `mail.tracking.value` — defined by [`mail`](../mail/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — depends_on, extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.l10n_de_audit_trail`](../../../agents/modules/generated/l10n_de_audit_trail.yaml) — required_by
- [`module.l10n_dk_audit_trail`](../../../agents/modules/generated/l10n_dk_audit_trail.yaml) — required_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — extends_model_from

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`sale`](../sale/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
