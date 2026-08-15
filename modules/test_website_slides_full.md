---
layout: page
title: "Test Full eLearning Flow (test_website_slides_full)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_website_slides_full/
nav_order: 0
---
# Test Full eLearning Flow — `test_website_slides_full`

**Source:** [`agents/modules/generated/test_website_slides_full.yaml`](../../agents/modules/generated/test_website_slides_full.yaml) · **Wiki:** [`knowledge/modules/test_website_slides_full/overview.md`](../../knowledge/modules/test_website_slides_full/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_website_slides_full</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Test Full eLearning Flow</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/test_website_slides_full</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_website_slides_full"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`payment_demo`](payment_demo.md), [`website_sale_product_configurator`](website_sale_product_configurator.md), [`website_sale_slides`](website_sale_slides.md), [`website_slides_forum`](website_slides_forum.md), [`website_slides_survey`](website_slides_survey.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.payment_demo` | depends_on | `agents/modules/generated/payment_demo.yaml` |
| `module.website_sale_product_configurator` | depends_on | `agents/modules/generated/website_sale_product_configurator.yaml` |
| `module.website_sale_slides` | depends_on | `agents/modules/generated/website_sale_slides.yaml` |
| `module.website_slides_forum` | depends_on | `agents/modules/generated/website_slides_forum.yaml` |
| `module.website_slides_survey` | depends_on | `agents/modules/generated/website_slides_survey.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_website_slides_full`](../../../agents/modules/generated/test_website_slides_full.yaml)
- Domain: `platform_core`
- Category: Hidden/Tests
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_website_slides_full)
- Direct dependencies: [`payment_demo`](../payment_demo/overview.md), [`website_sale_product_configurator`](../website_sale_product_configurator/overview.md), [`website_sale_slides`](../website_sale_slides/overview.md), [`website_slides_forum`](../website_slides_forum/overview.md), [`website_slides_survey`](../website_slides_survey/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_website_slides_full`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.payment_demo`](../../../agents/modules/generated/payment_demo.yaml) — depends_on
- [`module.website_sale_product_configurator`](../../../agents/modules/generated/website_sale_product_configurator.yaml) — depends_on
- [`module.website_sale_slides`](../../../agents/modules/generated/website_sale_slides.yaml) — depends_on
- [`module.website_slides_forum`](../../../agents/modules/generated/website_slides_forum.yaml) — depends_on
- [`module.website_slides_survey`](../../../agents/modules/generated/website_slides_survey.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
