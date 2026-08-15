---
layout: page
title: "Customer Rating (rating)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/rating/
nav_order: 0
---
# Customer Rating — `rating`

**Source:** [`agents/modules/generated/rating.yaml`](../../agents/modules/generated/rating.yaml) · **Wiki:** [`knowledge/modules/rating/overview.md`](../../knowledge/modules/rating/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>rating</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Customer Rating</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/rating</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/rating"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`mail`](mail.md)

## Reverse dependencies (modules that depend on this)

[`im_livechat`](im_livechat.md), [`portal_rating`](portal_rating.md), [`project`](project.md), [`test_mail_full`](test_mail_full.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>rating.mixin</code></div><div class="role">defined by <code>rating</code></div></div>
<div class="model"><div class="name"><code>rating.parent.mixin</code></div><div class="role">defined by <code>rating</code></div></div>
<div class="model"><div class="name"><code>rating.rating</code></div><div class="role">defined by <code>rating</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.message</code></div><div class="role">extended by <code>rating</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>rating</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.im_livechat` | model_extended_by, required_by | `agents/modules/generated/im_livechat.yaml` |
| `module.mail` | depends_on, extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.portal_rating` | model_extended_by, required_by | `agents/modules/generated/portal_rating.yaml` |
| `module.project` | model_extended_by, required_by | `agents/modules/generated/project.yaml` |
| `module.test_mail_full` | model_extended_by, required_by | `agents/modules/generated/test_mail_full.yaml` |
| `module.website_sale` | model_extended_by | `agents/modules/generated/website_sale.yaml` |
| `module.website_slides` | model_extended_by | `agents/modules/generated/website_slides.yaml` |

## Full wiki excerpt

- SME owner: [`module.rating`](../../../agents/modules/generated/rating.yaml)
- Domain: `platform_core`
- Category: Productivity
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/rating)
- Direct dependencies: [`mail`](../mail/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`im_livechat`](../im_livechat/overview.md), [`portal_rating`](../portal_rating/overview.md), [`project`](../project/overview.md), [`test_mail_full`](../test_mail_full/overview.md)
- Impact graph: [`module:rating`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `rating.mixin` — extended by [`im_livechat`](../im_livechat/overview.md), [`project`](../project/overview.md), [`test_mail_full`](../test_mail_full/overview.md), [`website_sale`](../website_sale/overview.md), [`website_slides`](../website_slides/overview.md)
- `rating.parent.mixin` — extended by [`im_livechat`](../im_livechat/overview.md), [`project`](../project/overview.md)
- `rating.rating` — extended by [`im_livechat`](../im_livechat/overview.md), [`portal_rating`](../portal_rating/overview.md)
- Extends `mail.message` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)

## Related SME agents

- [`module.im_livechat`](../../../agents/modules/generated/im_livechat.yaml) — model_extended_by, required_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.portal_rating`](../../../agents/modules/generated/portal_rating.yaml) — model_extended_by, required_by
- [`module.project`](../../../agents/modules/generated/project.yaml) — model_extended_by, required_by
- [`module.test_mail_full`](../../../agents/modules/generated/test_mail_full.yaml) — model_extended_by, required_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — model_extended_by
- [`module.website_slides`](../../../agents/modules/generated/website_slides.yaml) — model_extended_by

## Regression impact checklist

- Review 4 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`im_livechat`](../im_livechat/overview.md), [`portal_rating`](../portal_rating/overview.md), [`project`](../project/overview.md), [`test_mail_full`](../test_mail_full/overview.md), [`website_sale`](../website_sale/overview.md), [`website_slides`](../website_slides/overview.md).
- Review model owners used by this module: [`mail`](../mail/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
