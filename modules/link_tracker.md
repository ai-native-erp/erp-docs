---
layout: page
title: "Link Tracker (link_tracker)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/link_tracker/
nav_order: 0
---
# Link Tracker — `link_tracker`

**Source:** [`agents/modules/generated/link_tracker.yaml`](../../agents/modules/generated/link_tracker.yaml) · **Wiki:** [`knowledge/modules/link_tracker/overview.md`](../../knowledge/modules/link_tracker/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>link_tracker</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Link Tracker</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/link_tracker</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/link_tracker"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`mail`](mail.md), [`utm`](utm.md)

## Reverse dependencies (modules that depend on this)

[`mass_mailing`](mass_mailing.md), [`website_links`](website_links.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>link.tracker</code></div><div class="role">defined by <code>link_tracker</code></div></div>
<div class="model"><div class="name"><code>link.tracker.click</code></div><div class="role">defined by <code>link_tracker</code></div></div>
<div class="model"><div class="name"><code>link.tracker.code</code></div><div class="role">defined by <code>link_tracker</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.render.mixin</code></div><div class="role">extended by <code>link_tracker</code></div></div>
<div class="model"><div class="name"><code>utm.campaign</code></div><div class="role">extended by <code>link_tracker</code></div></div>
<div class="model"><div class="name"><code>utm.mixin</code></div><div class="role">extended by <code>link_tracker</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mail` | depends_on, extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | model_extended_by, required_by | `agents/modules/generated/mass_mailing.yaml` |
| `module.utm` | depends_on, extends_model_from | `agents/modules/generated/utm.yaml` |
| `module.website_links` | model_extended_by, required_by | `agents/modules/generated/website_links.yaml` |

## Full wiki excerpt

- SME owner: [`module.link_tracker`](../../../agents/modules/generated/link_tracker.yaml)
- Domain: `platform_core`
- Category: Marketing
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/link_tracker)
- Direct dependencies: [`mail`](../mail/overview.md), [`utm`](../utm/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`mass_mailing`](../mass_mailing/overview.md), [`website_links`](../website_links/overview.md)
- Impact graph: [`module:link_tracker`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `link.tracker` — extended by [`mass_mailing`](../mass_mailing/overview.md), [`website_links`](../website_links/overview.md)
- `link.tracker.click` — extended by [`mass_mailing`](../mass_mailing/overview.md)
- `link.tracker.code`
- Extends `mail.render.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `utm.campaign` — defined by [`utm`](../utm/overview.md)
- Extends `utm.mixin` — defined by [`utm`](../utm/overview.md)

## Related SME agents

- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — model_extended_by, required_by
- [`module.utm`](../../../agents/modules/generated/utm.yaml) — depends_on, extends_model_from
- [`module.website_links`](../../../agents/modules/generated/website_links.yaml) — model_extended_by, required_by

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`mass_mailing`](../mass_mailing/overview.md), [`website_links`](../website_links/overview.md).
- Review model owners used by this module: [`mail`](../mail/overview.md), [`utm`](../utm/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
