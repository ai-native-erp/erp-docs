---
layout: page
title: "Sales (sale_management)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale_management/
nav_order: 0
---
# Sales — `sale_management`

**Source:** [`agents/modules/generated/sale_management.yaml`](../../agents/modules/generated/sale_management.yaml) · **Wiki:** [`knowledge/modules/sale_management/overview.md`](../../knowledge/modules/sale_management/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_management</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sales</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale_management</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_management"><code>126b5bd</code></a></div></div>
</div>
## Purpose

From quotations to invoices

## Direct dependencies

[`digest`](digest.md), [`sale`](sale.md)

## Reverse dependencies (modules that depend on this)

[`event_sale`](event_sale.md), [`pos_sale`](pos_sale.md), [`repair`](repair.md), [`sale_expense`](sale_expense.md), [`sale_margin`](sale_margin.md), [`sale_pdf_quote_builder`](sale_pdf_quote_builder.md), [`sale_project`](sale_project.md), [`sale_service`](sale_service.md), [`test_sale_product_configurators`](test_sale_product_configurators.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>sale.order.option</code></div><div class="role">defined by <code>sale_management</code></div></div>
<div class="model"><div class="name"><code>sale.order.template</code></div><div class="role">defined by <code>sale_management</code></div></div>
<div class="model"><div class="name"><code>sale.order.template.line</code></div><div class="role">defined by <code>sale_management</code></div></div>
<div class="model"><div class="name"><code>sale.order.template.option</code></div><div class="role">defined by <code>sale_management</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>digest.digest</code></div><div class="role">extended by <code>sale_management</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>sale_management</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>sale_management</code></div></div>
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>sale_management</code></div></div>
<div class="model"><div class="name"><code>sale.order.line</code></div><div class="role">extended by <code>sale_management</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.digest` | depends_on, extends_model_from | `agents/modules/generated/digest.yaml` |
| `module.event_sale` | required_by | `agents/modules/generated/event_sale.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.partner_autocomplete` | extends_model_from | `agents/modules/generated/partner_autocomplete.yaml` |
| `module.pos_sale` | required_by | `agents/modules/generated/pos_sale.yaml` |
| `module.repair` | required_by | `agents/modules/generated/repair.yaml` |

## Full wiki excerpt

- SME owner: [`module.sale_management`](../../../agents/modules/generated/sale_management.yaml)
- Domain: `sales_crm`
- Category: Sales/Sales
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_management)
- Direct dependencies: [`digest`](../digest/overview.md), [`sale`](../sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`event_sale`](../event_sale/overview.md), [`pos_sale`](../pos_sale/overview.md), [`repair`](../repair/overview.md), [`sale_expense`](../sale_expense/overview.md), [`sale_margin`](../sale_margin/overview.md), [`sale_pdf_quote_builder`](../sale_pdf_quote_builder/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_service`](../sale_service/overview.md), [`test_sale_product_configurators`](../test_sale_product_configurators/overview.md)
- Impact graph: [`module:sale_management`](../../impact-graph.json)

## Purpose

From quotations to invoices

## Model relationships

- `sale.order.option`
- `sale.order.template` — extended by [`sale_pdf_quote_builder`](../sale_pdf_quote_builder/overview.md)
- `sale.order.template.line` — extended by [`sale_project`](../sale_project/overview.md)
- `sale.order.template.option`
- Extends `digest.digest` — defined by [`digest`](../digest/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `sale.order` — defined by [`sale`](../sale/overview.md)
- Extends `sale.order.line` — defined by [`sale`](../sale/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.digest`](../../../agents/modules/generated/digest.yaml) — depends_on, extends_model_from
- [`module.event_sale`](../../../agents/modules/generated/event_sale.yaml) — required_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.pos_sale`](../../../agents/modules/generated/pos_sale.yaml) — required_by
- [`module.repair`](../../../agents/modules/generated/repair.yaml) — required_by
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — depends_on, extends_model_from
- [`module.sale_expense`](../../../agents/modules/generated/sale_expense.yaml) — required_by
- [`module.sale_margin`](../../../agents/modules/generated/sale_margin.yaml) — required_by
- [`module.sale_pdf_quote_builder`](../../../agents/modules/generated/sale_pdf_quote_builder.yaml) — model_extended_by, required_by
- [`module.sale_project`](../../../agents/modules/generated/sale_project.yaml) — model_extended_by, required_by
- [`module.sale_service`](../../../agents/modules/generated/sale_service.yaml) — required_by
- [`module.test_sale_product_configurators`](../../../agents/modules/generated/test_sale_product_configurators.yaml) — required_by

## Regression impact checklist

- Review 9 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`sale_pdf_quote_builder`](../sale_pdf_quote_builder/overview.md), [`sale_project`](../sale_project/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`digest`](../digest/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`sale`](../sale/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
