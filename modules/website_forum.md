---
layout: page
title: "Forum (website_forum)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_forum/
nav_order: 0
---
# Forum — `website_forum`

**Source:** [`agents/modules/generated/website_forum.yaml`](../../agents/modules/generated/website_forum.yaml) · **Wiki:** [`knowledge/modules/website_forum/overview.md`](../../knowledge/modules/website_forum/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_forum</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Forum</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_forum</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_forum"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Manage a forum with FAQ and Q&A

## Direct dependencies

[`auth_signup`](auth_signup.md), [`website_mail`](website_mail.md), [`website_profile`](website_profile.md)

## Reverse dependencies (modules that depend on this)

[`website_slides_forum`](website_slides_forum.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>forum.forum</code></div><div class="role">defined by <code>website_forum</code></div></div>
<div class="model"><div class="name"><code>forum.post</code></div><div class="role">defined by <code>website_forum</code></div></div>
<div class="model"><div class="name"><code>forum.post.reason</code></div><div class="role">defined by <code>website_forum</code></div></div>
<div class="model"><div class="name"><code>forum.post.vote</code></div><div class="role">defined by <code>website_forum</code></div></div>
<div class="model"><div class="name"><code>forum.tag</code></div><div class="role">defined by <code>website_forum</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>forum.forum</code></div><div class="role">extended by <code>website_forum</code></div></div>
<div class="model"><div class="name"><code>forum.post</code></div><div class="role">extended by <code>website_forum</code></div></div>
<div class="model"><div class="name"><code>gamification.challenge</code></div><div class="role">extended by <code>website_forum</code></div></div>
<div class="model"><div class="name"><code>gamification.karma.tracking</code></div><div class="role">extended by <code>website_forum</code></div></div>
<div class="model"><div class="name"><code>image.mixin</code></div><div class="role">extended by <code>website_forum</code></div></div>
<div class="model"><div class="name"><code>ir.attachment</code></div><div class="role">extended by <code>website_forum</code></div></div>
<div class="model"><div class="name"><code>mail.message</code></div><div class="role">extended by <code>website_forum</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>website_forum</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>website_forum</code></div></div>
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>website_forum</code></div></div>
<div class="model"><div class="name"><code>website.multi.mixin</code></div><div class="role">extended by <code>website_forum</code></div></div>
<div class="model"><div class="name"><code>website.searchable.mixin</code></div><div class="role">extended by <code>website_forum</code></div></div>
<div class="model"><div class="name"><code>website.seo.metadata</code></div><div class="role">extended by <code>website_forum</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.auth_signup` | depends_on | `agents/modules/generated/auth_signup.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.gamification` | extends_model_from | `agents/modules/generated/gamification.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |
| `module.website` | extends_model_from | `agents/modules/generated/website.yaml` |
| `module.website_mail` | depends_on | `agents/modules/generated/website_mail.yaml` |
| `module.website_profile` | depends_on | `agents/modules/generated/website_profile.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_forum`](../../../agents/modules/generated/website_forum.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_forum)
- Direct dependencies: [`auth_signup`](../auth_signup/overview.md), [`website_mail`](../website_mail/overview.md), [`website_profile`](../website_profile/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`website_slides_forum`](../website_slides_forum/overview.md)
- Impact graph: [`module:website_forum`](../../impact-graph.json)

## Purpose

Manage a forum with FAQ and Q&A

## Model relationships

- `forum.forum` — extended by [`website_slides_forum`](../website_slides_forum/overview.md)
- `forum.post`
- `forum.post.reason`
- `forum.post.vote`
- `forum.tag`
- Extends `forum.forum` — framework/dynamic owner
- Extends `forum.post` — framework/dynamic owner
- Extends `gamification.challenge` — defined by [`gamification`](../gamification/overview.md)
- Extends `gamification.karma.tracking` — defined by [`gamification`](../gamification/overview.md)
- Extends `image.mixin` — defined by [`base`](../base/overview.md)
- Extends `ir.attachment` — defined by [`base`](../base/overview.md)
- Extends `mail.message` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)
- Extends `website` — defined by [`website`](../website/overview.md)
- Extends `website.multi.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.searchable.mixin` — defined by [`website`](../website/overview.md)
- Extends `website.seo.metadata` — defined by [`website`](../website/overview.md)

## Related SME agents

- [`module.auth_signup`](../../../agents/modules/generated/auth_signup.yaml) — depends_on
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.gamification`](../../../agents/modules/generated/gamification.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_mail`](../../../agents/modules/generated/website_mail.yaml) — depends_on
- [`module.website_profile`](../../../agents/modules/generated/website_profile.yaml) — depends_on
- [`module.website_slides_forum`](../../../agents/modules/generated/website_slides_forum.yaml) — model_extended_by, required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`website_slides_forum`](../website_slides_forum/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`gamification`](../gamification/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`website`](../website/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
