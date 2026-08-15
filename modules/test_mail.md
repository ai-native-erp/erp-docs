---
layout: page
title: "Mail Tests (test_mail)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_mail/
nav_order: 0
---
# Mail Tests — `test_mail`

**Source:** [`agents/modules/generated/test_mail.yaml`](../../agents/modules/generated/test_mail.yaml) · **Wiki:** [`knowledge/modules/test_mail/overview.md`](../../knowledge/modules/test_mail/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_mail</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Mail Tests</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/test_mail</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_mail"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Mail Tests: performances and tests specific to mail

## Direct dependencies

[`mail`](mail.md), [`test_performance`](test_performance.md)

## Reverse dependencies (modules that depend on this)

[`test_mail_full`](test_mail_full.md), [`test_mass_mailing`](test_mass_mailing.md), [`test_xlsx_export`](test_xlsx_export.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.performance.thread</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.performance.tracking</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.access</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.access.custo</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.activity</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.alias.optional</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.cc</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.composer.mixin</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.composer.source</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.container</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.container.mc</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.field.type</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.gateway</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.gateway.company</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.gateway.groups</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.lang</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.mail.tracking.duration</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.multi.company</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.multi.company.read</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.multi.company.with.activity</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.nothread</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.properties</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.simple</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.simple.main.attachment</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.simple.unfollow</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.ticket</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.ticket.el</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.ticket.mc</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.track</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.track.all</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.track.all.m2m</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.track.all.o2m</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.track.compute</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.track.groups</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.track.monetary</code></div><div class="role">defined by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.track.selection</code></div><div class="role">defined by <code>test_mail</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.alias.mixin</code></div><div class="role">extended by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.alias.mixin.optional</code></div><div class="role">extended by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.composer.mixin</code></div><div class="role">extended by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.container</code></div><div class="role">extended by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.gateway</code></div><div class="role">extended by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.multi.company</code></div><div class="role">extended by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.simple</code></div><div class="role">extended by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.test.ticket</code></div><div class="role">extended by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.thread.blacklist</code></div><div class="role">extended by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.thread.cc</code></div><div class="role">extended by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.thread.main.attachment</code></div><div class="role">extended by <code>test_mail</code></div></div>
<div class="model"><div class="name"><code>mail.tracking.duration.mixin</code></div><div class="role">extended by <code>test_mail</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mail` | depends_on, extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.test_mail_full` | required_by | `agents/modules/generated/test_mail_full.yaml` |
| `module.test_mass_mailing` | required_by | `agents/modules/generated/test_mass_mailing.yaml` |
| `module.test_performance` | depends_on | `agents/modules/generated/test_performance.yaml` |
| `module.test_xlsx_export` | required_by | `agents/modules/generated/test_xlsx_export.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_mail`](../../../agents/modules/generated/test_mail.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_mail)
- Direct dependencies: [`mail`](../mail/overview.md), [`test_performance`](../test_performance/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_mail_full`](../test_mail_full/overview.md), [`test_mass_mailing`](../test_mass_mailing/overview.md), [`test_xlsx_export`](../test_xlsx_export/overview.md)
- Impact graph: [`module:test_mail`](../../impact-graph.json)

## Purpose

Mail Tests: performances and tests specific to mail

## Model relationships

- `mail.performance.thread`
- `mail.performance.tracking`
- `mail.test.access`
- `mail.test.access.custo`
- `mail.test.activity`
- `mail.test.alias.optional`
- `mail.test.cc`
- `mail.test.composer.mixin`
- `mail.test.composer.source`
- `mail.test.container`
- `mail.test.container.mc`
- `mail.test.field.type`
- `mail.test.gateway`
- `mail.test.gateway.company`
- `mail.test.gateway.groups`
- `mail.test.lang`
- `mail.test.mail.tracking.duration`
- `mail.test.multi.company`
- `mail.test.multi.company.read`
- `mail.test.multi.company.with.activity`
- `mail.test.nothread`
- `mail.test.properties`
- `mail.test.simple`
- `mail.test.simple.main.attachment`
- `mail.test.simple.unfollow`
- `mail.test.ticket`
- `mail.test.ticket.el`
- `mail.test.ticket.mc`
- `mail.test.track`
- `mail.test.track.all`
- `mail.test.track.all.m2m`
- `mail.test.track.all.o2m`
- `mail.test.track.compute`
- `mail.test.track.groups`
- `mail.test.track.monetary`
- `mail.test.track.selection`
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.alias.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.alias.mixin.optional` — defined by [`mail`](../mail/overview.md)
- Extends `mail.composer.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.test.container` — framework/dynamic owner
- Extends `mail.test.gateway` — framework/dynamic owner
- Extends `mail.test.multi.company` — framework/dynamic owner
- Extends `mail.test.simple` — framework/dynamic owner
- Extends `mail.test.ticket` — framework/dynamic owner
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread.blacklist` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread.cc` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread.main.attachment` — defined by [`mail`](../mail/overview.md)
- Extends `mail.tracking.duration.mixin` — defined by [`mail`](../mail/overview.md)

## Related SME agents

- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.test_mail_full`](../../../agents/modules/generated/test_mail_full.yaml) — required_by
- [`module.test_mass_mailing`](../../../agents/modules/generated/test_mass_mailing.yaml) — required_by
- [`module.test_performance`](../../../agents/modules/generated/test_performance.yaml) — depends_on
- [`module.test_xlsx_export`](../../../agents/modules/generated/test_xlsx_export.yaml) — required_by

## Regression impact checklist

- Review 3 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`mail`](../mail/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
