---
layout: page
title: "Website Mail Group (website_mail_group)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_mail_group/
nav_order: 0
---
# Website Mail Group — `website_mail_group`

**Source:** [`agents/modules/generated/website_mail_group.yaml`](../../agents/modules/generated/website_mail_group.yaml) · **Wiki:** [`knowledge/modules/website_mail_group/overview.md`](../../knowledge/modules/website_mail_group/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_mail_group</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Website Mail Group</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_mail_group</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_mail_group"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Add a website snippet for the mail groups.

## Direct dependencies

[`mail_group`](mail_group.md), [`website`](website.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.group</code></div><div class="role">defined by <code>website_mail_group</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.group</code></div><div class="role">extended by <code>website_mail_group</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mail_group` | depends_on, extends_model_from | `agents/modules/generated/mail_group.yaml` |
| `module.website` | depends_on | `agents/modules/generated/website.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_mail_group`](../../../agents/modules/generated/website_mail_group.yaml)
- Domain: `website_ecommerce`
- Category: Uncategorized
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_mail_group)
- Direct dependencies: [`mail_group`](../mail_group/overview.md), [`website`](../website/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:website_mail_group`](../../impact-graph.json)

## Purpose

Add a website snippet for the mail groups.

## Model relationships

- `mail.group`
- Extends `mail.group` — defined by [`mail_group`](../mail_group/overview.md)

## Related SME agents

- [`module.mail_group`](../../../agents/modules/generated/mail_group.yaml) — depends_on, extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`mail_group`](../mail_group/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
