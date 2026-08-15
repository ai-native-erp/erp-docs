---
layout: page
title: "test-inherit (test_inherit)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_inherit/
nav_order: 0
---
# test-inherit — `test_inherit`

**Source:** [`agents/modules/generated/test_inherit.yaml`](../../agents/modules/generated/test_inherit.yaml) · **Wiki:** [`knowledge/modules/test_inherit/overview.md`](../../knowledge/modules/test_inherit/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_inherit</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">test-inherit</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>odoo/addons/test_inherit</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_inherit"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base`](base.md), [`test_new_api`](test_new_api.md)

## Reverse dependencies (modules that depend on this)

[`test_inherit_depends`](test_inherit_depends.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>test.inherit.child</code></div><div class="role">defined by <code>test_inherit</code></div></div>
<div class="model"><div class="name"><code>test.inherit.daughter</code></div><div class="role">defined by <code>test_inherit</code></div></div>
<div class="model"><div class="name"><code>test.inherit.mother</code></div><div class="role">defined by <code>test_inherit</code></div></div>
<div class="model"><div class="name"><code>test.inherit.parent</code></div><div class="role">defined by <code>test_inherit</code></div></div>
<div class="model"><div class="name"><code>test.inherit.property</code></div><div class="role">defined by <code>test_inherit</code></div></div>
<div class="model"><div class="name"><code>test_inherit.mixin</code></div><div class="role">defined by <code>test_inherit</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>test_inherit</code></div></div>
<div class="model"><div class="name"><code>test.inherit.daughter</code></div><div class="role">extended by <code>test_inherit</code></div></div>
<div class="model"><div class="name"><code>test.inherit.mother</code></div><div class="role">extended by <code>test_inherit</code></div></div>
<div class="model"><div class="name"><code>test.inherit.parent</code></div><div class="role">extended by <code>test_inherit</code></div></div>
<div class="model"><div class="name"><code>test.inherit.property</code></div><div class="role">extended by <code>test_inherit</code></div></div>
<div class="model"><div class="name"><code>test_new_api.message</code></div><div class="role">extended by <code>test_inherit</code></div></div>
<div class="model"><div class="name"><code>test_new_api.selection</code></div><div class="role">extended by <code>test_inherit</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | depends_on, extends_model_from | `agents/modules/generated/base.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.l10n_tr_nilvera` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.partner_autocomplete` | extends_model_from | `agents/modules/generated/partner_autocomplete.yaml` |
| `module.phone_validation` | extends_model_from | `agents/modules/generated/phone_validation.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_inherit`](../../../agents/modules/generated/test_inherit.yaml)
- Domain: `platform_core`
- Category: Hidden/Tests
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/test_inherit)
- Direct dependencies: [`base`](../base/overview.md), [`test_new_api`](../test_new_api/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_inherit_depends`](../test_inherit_depends/overview.md)
- Impact graph: [`module:test_inherit`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `test.inherit.child`
- `test.inherit.daughter`
- `test.inherit.mother`
- `test.inherit.parent`
- `test.inherit.property`
- `test_inherit.mixin` — extended by [`test_inherit_depends`](../test_inherit_depends/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `test.inherit.daughter` — framework/dynamic owner
- Extends `test.inherit.mother` — framework/dynamic owner
- Extends `test.inherit.parent` — framework/dynamic owner
- Extends `test.inherit.property` — framework/dynamic owner
- Extends `test_new_api.message` — defined by [`test_new_api`](../test_new_api/overview.md)
- Extends `test_new_api.selection` — defined by [`test_new_api`](../test_new_api/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on, extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.test_inherit_depends`](../../../agents/modules/generated/test_inherit_depends.yaml) — model_extended_by, required_by
- [`module.test_new_api`](../../../agents/modules/generated/test_new_api.yaml) — depends_on, extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`test_inherit_depends`](../test_inherit_depends/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`test_new_api`](../test_new_api/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
