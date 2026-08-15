---
layout: page
title: "Mail Group (mail_group)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/mail_group/
nav_order: 0
---
# Mail Group — `mail_group`

**Source:** [`agents/modules/generated/mail_group.yaml`](../../agents/modules/generated/mail_group.yaml) · **Wiki:** [`knowledge/modules/mail_group/overview.md`](../../knowledge/modules/mail_group/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>mail_group</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Mail Group</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/mail_group</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mail_group"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Manage your mailing lists

## Direct dependencies

[`mail`](mail.md), [`portal`](portal.md)

## Reverse dependencies (modules that depend on this)

[`website_mail_group`](website_mail_group.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.group</code></div><div class="role">defined by <code>mail_group</code></div></div>
<div class="model"><div class="name"><code>mail.group.member</code></div><div class="role">defined by <code>mail_group</code></div></div>
<div class="model"><div class="name"><code>mail.group.message</code></div><div class="role">defined by <code>mail_group</code></div></div>
<div class="model"><div class="name"><code>mail.group.message.reject</code></div><div class="role">defined by <code>mail_group</code></div></div>
<div class="model"><div class="name"><code>mail.group.moderation</code></div><div class="role">defined by <code>mail_group</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.alias.mixin</code></div><div class="role">extended by <code>mail_group</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mail` | depends_on, extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.portal` | depends_on | `agents/modules/generated/portal.yaml` |
| `module.website_mail_group` | model_extended_by, required_by | `agents/modules/generated/website_mail_group.yaml` |

## Full wiki excerpt

- SME owner: [`module.mail_group`](../../../agents/modules/generated/mail_group.yaml)
- Domain: `platform_core`
- Category: Uncategorized
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mail_group)
- Direct dependencies: [`mail`](../mail/overview.md), [`portal`](../portal/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`website_mail_group`](../website_mail_group/overview.md)
- Impact graph: [`module:mail_group`](../../impact-graph.json)

## Purpose

Manage your mailing lists

## Model relationships

- `mail.group` — extended by [`website_mail_group`](../website_mail_group/overview.md)
- `mail.group.member`
- `mail.group.message`
- `mail.group.message.reject`
- `mail.group.moderation`
- Extends `mail.alias.mixin` — defined by [`mail`](../mail/overview.md)

## Related SME agents

- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — depends_on
- [`module.website_mail_group`](../../../agents/modules/generated/website_mail_group.yaml) — model_extended_by, required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`website_mail_group`](../website_mail_group/overview.md).
- Review model owners used by this module: [`mail`](../mail/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
