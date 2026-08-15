---
layout: page
title: "Online Members Directory (website_membership)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_membership/
nav_order: 0
---
# Online Members Directory — `website_membership`

**Source:** [`agents/modules/generated/website_membership.yaml`](../../agents/modules/generated/website_membership.yaml) · **Wiki:** [`knowledge/modules/website_membership/overview.md`](../../knowledge/modules/website_membership/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_membership</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Online Members Directory</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_membership</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_membership"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Publish your members directory

## Direct dependencies

[`membership`](membership.md), [`website_google_map`](website_google_map.md), [`website_partner`](website_partner.md), [`website_sale`](website_sale.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>membership.membership_line</code></div><div class="role">extended by <code>website_membership</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>website_membership</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.membership` | depends_on, extends_model_from | `agents/modules/generated/membership.yaml` |
| `module.website` | extends_model_from | `agents/modules/generated/website.yaml` |
| `module.website_google_map` | depends_on | `agents/modules/generated/website_google_map.yaml` |
| `module.website_partner` | depends_on | `agents/modules/generated/website_partner.yaml` |
| `module.website_sale` | depends_on | `agents/modules/generated/website_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_membership`](../../../agents/modules/generated/website_membership.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_membership)
- Direct dependencies: [`membership`](../membership/overview.md), [`website_google_map`](../website_google_map/overview.md), [`website_partner`](../website_partner/overview.md), [`website_sale`](../website_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:website_membership`](../../impact-graph.json)

## Purpose

Publish your members directory

## Model relationships

- Extends `membership.membership_line` — defined by [`membership`](../membership/overview.md)
- Extends `website` — defined by [`website`](../website/overview.md)

## Related SME agents

- [`module.membership`](../../../agents/modules/generated/membership.yaml) — depends_on, extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_google_map`](../../../agents/modules/generated/website_google_map.yaml) — depends_on
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — depends_on
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`membership`](../membership/overview.md), [`website`](../website/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
