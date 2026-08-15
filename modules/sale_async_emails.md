---
layout: page
title: "Sales - Async Emails (sale_async_emails)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale_async_emails/
nav_order: 0
---
# Sales - Async Emails — `sale_async_emails`

**Source:** [`agents/modules/generated/sale_async_emails.yaml`](../../agents/modules/generated/sale_async_emails.yaml) · **Wiki:** [`knowledge/modules/sale_async_emails/overview.md`](../../knowledge/modules/sale_async_emails/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_async_emails</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sales - Async Emails</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale_async_emails</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_async_emails"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Send order status emails asynchronously

## Direct dependencies

[`sale`](sale.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>sale_async_emails</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.sale` | depends_on, extends_model_from | `agents/modules/generated/sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.sale_async_emails`](../../../agents/modules/generated/sale_async_emails.yaml)
- Domain: `sales_crm`
- Category: Sales/Sales
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sale_async_emails)
- Direct dependencies: [`sale`](../sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:sale_async_emails`](../../impact-graph.json)

## Purpose

Send order status emails asynchronously

## Model relationships

- Extends `sale.order` — defined by [`sale`](../sale/overview.md)

## Related SME agents

- [`module.sale`](../../../agents/modules/generated/sale.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`sale`](../sale/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
