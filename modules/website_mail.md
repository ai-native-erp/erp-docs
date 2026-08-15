---
layout: page
title: "Website Mail (website_mail)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_mail/
nav_order: 0
---
# Website Mail — `website_mail`

**Source:** [`agents/modules/generated/website_mail.yaml`](../../agents/modules/generated/website_mail.yaml) · **Wiki:** [`knowledge/modules/website_mail/overview.md`](../../knowledge/modules/website_mail/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_mail</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Website Mail</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_mail</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_mail"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Website Module for Mail

## Direct dependencies

[`mail`](mail.md), [`website`](website.md)

## Reverse dependencies (modules that depend on this)

[`website_blog`](website_blog.md), [`website_event`](website_event.md), [`website_forum`](website_forum.md), [`website_hr_recruitment`](website_hr_recruitment.md), [`website_sale`](website_sale.md), [`website_slides`](website_slides.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>publisher_warranty.contract</code></div><div class="role">extended by <code>website_mail</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mail` | depends_on, extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.website` | depends_on | `agents/modules/generated/website.yaml` |
| `module.website_blog` | required_by | `agents/modules/generated/website_blog.yaml` |
| `module.website_event` | required_by | `agents/modules/generated/website_event.yaml` |
| `module.website_forum` | required_by | `agents/modules/generated/website_forum.yaml` |
| `module.website_hr_recruitment` | required_by | `agents/modules/generated/website_hr_recruitment.yaml` |
| `module.website_sale` | required_by | `agents/modules/generated/website_sale.yaml` |
| `module.website_slides` | required_by | `agents/modules/generated/website_slides.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_mail`](../../../agents/modules/generated/website_mail.yaml)
- Domain: `website_ecommerce`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_mail)
- Direct dependencies: [`mail`](../mail/overview.md), [`website`](../website/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`website_blog`](../website_blog/overview.md), [`website_event`](../website_event/overview.md), [`website_forum`](../website_forum/overview.md), [`website_hr_recruitment`](../website_hr_recruitment/overview.md), [`website_sale`](../website_sale/overview.md), [`website_slides`](../website_slides/overview.md)
- Impact graph: [`module:website_mail`](../../impact-graph.json)

## Purpose

Website Module for Mail

## Model relationships

- Extends `publisher_warranty.contract` — defined by [`mail`](../mail/overview.md)

## Related SME agents

- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — depends_on
- [`module.website_blog`](../../../agents/modules/generated/website_blog.yaml) — required_by
- [`module.website_event`](../../../agents/modules/generated/website_event.yaml) — required_by
- [`module.website_forum`](../../../agents/modules/generated/website_forum.yaml) — required_by
- [`module.website_hr_recruitment`](../../../agents/modules/generated/website_hr_recruitment.yaml) — required_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — required_by
- [`module.website_slides`](../../../agents/modules/generated/website_slides.yaml) — required_by

## Regression impact checklist

- Review 6 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`mail`](../mail/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
