---
layout: page
title: "Sale Product Configurators Tests (test_sale_product_configurators)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_sale_product_configurators/
nav_order: 0
---
# Sale Product Configurators Tests — `test_sale_product_configurators`

**Source:** [`agents/modules/generated/test_sale_product_configurators.yaml`](../../agents/modules/generated/test_sale_product_configurators.yaml) · **Wiki:** [`knowledge/modules/test_sale_product_configurators/overview.md`](../../knowledge/modules/test_sale_product_configurators/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_sale_product_configurators</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Sale Product Configurators Tests</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/test_sale_product_configurators</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_sale_product_configurators"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Test Suite for Sale Product Configurator

## Direct dependencies

[`event_sale`](event_sale.md), [`sale_management`](sale_management.md), [`sale_product_configurator`](sale_product_configurator.md), [`sale_product_matrix`](sale_product_matrix.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.event_sale` | depends_on | `agents/modules/generated/event_sale.yaml` |
| `module.sale_management` | depends_on | `agents/modules/generated/sale_management.yaml` |
| `module.sale_product_configurator` | depends_on | `agents/modules/generated/sale_product_configurator.yaml` |
| `module.sale_product_matrix` | depends_on | `agents/modules/generated/sale_product_matrix.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_sale_product_configurators`](../../../agents/modules/generated/test_sale_product_configurators.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_sale_product_configurators)
- Direct dependencies: [`event_sale`](../event_sale/overview.md), [`sale_management`](../sale_management/overview.md), [`sale_product_configurator`](../sale_product_configurator/overview.md), [`sale_product_matrix`](../sale_product_matrix/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_sale_product_configurators`](../../impact-graph.json)

## Purpose

Test Suite for Sale Product Configurator

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.event_sale`](../../../agents/modules/generated/event_sale.yaml) — depends_on
- [`module.sale_management`](../../../agents/modules/generated/sale_management.yaml) — depends_on
- [`module.sale_product_configurator`](../../../agents/modules/generated/sale_product_configurator.yaml) — depends_on
- [`module.sale_product_matrix`](../../../agents/modules/generated/sale_product_matrix.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
