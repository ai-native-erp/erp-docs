---
layout: page
title: "Google Maps (website_google_map)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_google_map/
nav_order: 0
---
# Google Maps — `website_google_map`

**Source:** [`agents/modules/generated/website_google_map.yaml`](../../agents/modules/generated/website_google_map.yaml) · **Wiki:** [`knowledge/modules/website_google_map/overview.md`](../../knowledge/modules/website_google_map/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_google_map</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Google Maps</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_google_map</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_google_map"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Show your company address on Google Maps

## Direct dependencies

[`base_geolocalize`](base_geolocalize.md), [`website_partner`](website_partner.md)

## Reverse dependencies (modules that depend on this)

[`website_crm_partner_assign`](website_crm_partner_assign.md), [`website_customer`](website_customer.md), [`website_membership`](website_membership.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base_geolocalize` | depends_on | `agents/modules/generated/base_geolocalize.yaml` |
| `module.website_crm_partner_assign` | required_by | `agents/modules/generated/website_crm_partner_assign.yaml` |
| `module.website_customer` | required_by | `agents/modules/generated/website_customer.yaml` |
| `module.website_membership` | required_by | `agents/modules/generated/website_membership.yaml` |
| `module.website_partner` | depends_on | `agents/modules/generated/website_partner.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_google_map`](../../../agents/modules/generated/website_google_map.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_google_map)
- Direct dependencies: [`base_geolocalize`](../base_geolocalize/overview.md), [`website_partner`](../website_partner/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`website_crm_partner_assign`](../website_crm_partner_assign/overview.md), [`website_customer`](../website_customer/overview.md), [`website_membership`](../website_membership/overview.md)
- Impact graph: [`module:website_google_map`](../../impact-graph.json)

## Purpose

Show your company address on Google Maps

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.base_geolocalize`](../../../agents/modules/generated/base_geolocalize.yaml) — depends_on
- [`module.website_crm_partner_assign`](../../../agents/modules/generated/website_crm_partner_assign.yaml) — required_by
- [`module.website_customer`](../../../agents/modules/generated/website_customer.yaml) — required_by
- [`module.website_membership`](../../../agents/modules/generated/website_membership.yaml) — required_by
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — depends_on

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
