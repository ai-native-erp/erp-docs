---
layout: page
title: "Sales Order Extension Examples (sale_order_extension)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sale_order_extension/
nav_order: 0
---
# Sales Order Extension Examples — `sale_order_extension`

**Source:** [`agents/modules/generated/sale_order_extension.yaml`](../../agents/modules/generated/sale_order_extension.yaml) · **Wiki:** [`knowledge/modules/sale_order_extension/overview.md`](../../knowledge/modules/sale_order_extension/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sale_order_extension</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sales Order Extension Examples</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">sales_crm</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sale_order_extension</code></div></div>
<div class="meta-card"><div class="k">Source revision</div><div class="v"><code>local</code></div></div>
</div>
## Purpose

Approval workflow, rules, REST API, record events, jobs, and client behavior

## Direct dependencies

[`bus`](bus.md), [`mail`](mail.md), [`sale`](sale.md), [`web`](web.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>sale.order</code></div><div class="role">extended by <code>sale_order_extension</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.bus` | depends_on | `agents/modules/generated/bus.yaml` |
| `module.mail` | depends_on | `agents/modules/generated/mail.yaml` |
| `module.sale` | depends_on, extends_model_from | `agents/modules/generated/sale.yaml` |
| `module.web` | depends_on | `agents/modules/generated/web.yaml` |

## Conversation learnings

- [`2026-08-10-sale-servicenow-patterns`](../../knowledge/conversations/2026-08-10-sale-servicenow-patterns.json)
- [`2026-08-11-owl-component-fundamentals`](../../knowledge/conversations/2026-08-11-owl-component-fundamentals.json)
- [`2026-08-11-owl-orm-rpc-data-access`](../../knowledge/conversations/2026-08-11-owl-orm-rpc-data-access.json)
- [`2026-08-11-sale-order-workspace`](../../knowledge/conversations/2026-08-11-sale-order-workspace.json)
- [`2026-08-12-odoo-17-customer-baseline`](../../knowledge/conversations/2026-08-12-odoo-17-customer-baseline.json)

## Full wiki excerpt

- SME owner: [`module.sale_order_extension`](../../../agents/modules/generated/sale_order_extension.yaml)
- Source: custom/local addon
- Direct dependencies: [`bus`](../bus/overview.md), [`mail`](../mail/overview.md), [`sale`](../sale/overview.md), [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:sale_order_extension`](../../impact-graph.json)

## Purpose

Approval workflow, rules, REST API, record events, jobs, and client behavior

## Model relationships

- Extends `sale.order` — defined by [`sale`](../sale/overview.md)

## Related SME agents

- [`module.bus`](../../../agents/modules/generated/bus.yaml) — depends_on
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — depends_on, extends_model_from
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`sale`](../sale/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.

### Conversation-derived learnings

- [`2026-08-10-sale-servicenow-patterns`](../../conversations/2026-08-10-sale-servicenow-patterns.json)
- [`2026-08-11-owl-component-fundamentals`](../../conversations/2026-08-11-owl-component-fundamentals.json)
- [`2026-08-11-owl-orm-rpc-data-access`](../../conversations/2026-08-11-owl-orm-rpc-data-access.json)
- [`2026-08-11-sale-order-workspace`](../../conversations/2026-08-11-sale-order-workspace.json)
- [`2026-08-12-odoo-17-customer-baseline`](../../conversations/2026-08-12-odoo-17-customer-baseline.json)
