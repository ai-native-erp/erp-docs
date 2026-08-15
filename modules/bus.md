---
layout: page
title: "IM Bus (bus)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/bus/
nav_order: 0
---
# IM Bus — `bus`

**Source:** [`agents/modules/generated/bus.yaml`](../../agents/modules/generated/bus.yaml) · **Wiki:** [`knowledge/modules/bus/overview.md`](../../knowledge/modules/bus/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>bus</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">IM Bus</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/bus</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/bus"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base`](base.md), [`web`](web.md)

## Reverse dependencies (modules that depend on this)

[`mail`](mail.md), [`sale_order_extension`](sale_order_extension.md), [`spreadsheet`](spreadsheet.md), [`web_editor`](web_editor.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>bus.bus</code></div><div class="role">defined by <code>bus</code></div></div>
<div class="model"><div class="name"><code>bus.presence</code></div><div class="role">defined by <code>bus</code></div></div>
<div class="model"><div class="name"><code>ir.websocket</code></div><div class="role">defined by <code>bus</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>bus</code></div></div>
<div class="model"><div class="name"><code>ir.model</code></div><div class="role">extended by <code>bus</code></div></div>
<div class="model"><div class="name"><code>ir.qweb</code></div><div class="role">extended by <code>bus</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>bus</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>bus</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | depends_on, extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.hr_presence` | model_extended_by | `agents/modules/generated/hr_presence.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.l10n_tr_nilvera` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera.yaml` |
| `module.mail` | extends_model_from, model_extended_by, required_by | `agents/modules/generated/mail.yaml` |

## Conversation learnings

- [`2026-08-10-sale-servicenow-patterns`](../../knowledge/conversations/2026-08-10-sale-servicenow-patterns.json)
- [`2026-08-12-odoo-17-customer-baseline`](../../knowledge/conversations/2026-08-12-odoo-17-customer-baseline.json)

## Full wiki excerpt

- SME owner: [`module.bus`](../../../agents/modules/generated/bus.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/bus)
- Direct dependencies: [`base`](../base/overview.md), [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`mail`](../mail/overview.md), [`sale_order_extension`](../sale_order_extension/overview.md), [`spreadsheet`](../spreadsheet/overview.md), [`web_editor`](../web_editor/overview.md)
- Impact graph: [`module:bus`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `bus.bus`
- `bus.presence` — extended by [`mail`](../mail/overview.md)
- `ir.websocket` — extended by [`hr_presence`](../hr_presence/overview.md), [`mail`](../mail/overview.md), [`web_editor`](../web_editor/overview.md)
- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `ir.model` — defined by [`base`](../base/overview.md), [`website`](../website/overview.md)
- Extends `ir.qweb` — defined by [`base`](../base/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on, extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.hr_presence`](../../../agents/modules/generated/hr_presence.yaml) — model_extended_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from, model_extended_by, required_by
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.sale_order_extension`](../../../agents/modules/generated/sale_order_extension.yaml) — required_by
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.spreadsheet`](../../../agents/modules/generated/spreadsheet.yaml) — required_by
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on
- [`module.web_editor`](../../../agents/modules/generated/web_editor.yaml) — model_extended_by, required_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from

## Regression impact checklist

- Review 4 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`hr_presence`](../hr_presence/overview.md), [`mail`](../mail/overview.md), [`web_editor`](../web_editor/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.

### Conversation-derived learnings

- [`2026-08-10-sale-servicenow-patterns`](../../conversations/2026-08-10-sale-servicenow-patterns.json)
- [`2026-08-12-odoo-17-customer-baseline`](../../conversations/2026-08-12-odoo-17-customer-baseline.json)
