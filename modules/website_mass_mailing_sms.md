---
layout: page
title: "Newsletter Subscribe SMS Template (website_mass_mailing_sms)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_mass_mailing_sms/
nav_order: 0
---
# Newsletter Subscribe SMS Template — `website_mass_mailing_sms`

**Source:** [`agents/modules/generated/website_mass_mailing_sms.yaml`](../../agents/modules/generated/website_mass_mailing_sms.yaml) · **Wiki:** [`knowledge/modules/website_mass_mailing_sms/overview.md`](../../knowledge/modules/website_mass_mailing_sms/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_mass_mailing_sms</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Newsletter Subscribe SMS Template</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_mass_mailing_sms</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_mass_mailing_sms"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Attract visitors to subscribe to mailing lists

## Direct dependencies

[`mass_mailing_sms`](mass_mailing_sms.md), [`website_mass_mailing`](website_mass_mailing.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mass_mailing_sms` | depends_on | `agents/modules/generated/mass_mailing_sms.yaml` |
| `module.website_mass_mailing` | depends_on | `agents/modules/generated/website_mass_mailing.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_mass_mailing_sms`](../../../agents/modules/generated/website_mass_mailing_sms.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_mass_mailing_sms)
- Direct dependencies: [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`website_mass_mailing`](../website_mass_mailing/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:website_mass_mailing_sms`](../../impact-graph.json)

## Purpose

Attract visitors to subscribe to mailing lists

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — depends_on
- [`module.website_mass_mailing`](../../../agents/modules/generated/website_mass_mailing.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
