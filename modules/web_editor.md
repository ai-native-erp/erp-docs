---
layout: page
title: "Web Editor (web_editor)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/web_editor/
nav_order: 0
---
# Web Editor — `web_editor`

**Source:** [`agents/modules/generated/web_editor.yaml`](../../agents/modules/generated/web_editor.yaml) · **Wiki:** [`knowledge/modules/web_editor/overview.md`](../../knowledge/modules/web_editor/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>web_editor</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Web Editor</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/web_editor</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/web_editor"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`bus`](bus.md), [`web`](web.md)

## Reverse dependencies (modules that depend on this)

[`mass_mailing`](mass_mailing.md), [`point_of_sale`](point_of_sale.md), [`portal`](portal.md), [`test_html_field_history`](test_html_field_history.md), [`web_unsplash`](web_unsplash.md), [`website`](website.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>html.field.history.mixin</code></div><div class="role">defined by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field</code></div><div class="role">defined by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.contact</code></div><div class="role">defined by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.date</code></div><div class="role">defined by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.datetime</code></div><div class="role">defined by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.duration</code></div><div class="role">defined by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.float</code></div><div class="role">defined by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.html</code></div><div class="role">defined by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.image</code></div><div class="role">defined by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.integer</code></div><div class="role">defined by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.many2one</code></div><div class="role">defined by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.monetary</code></div><div class="role">defined by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.qweb</code></div><div class="role">defined by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.relative</code></div><div class="role">defined by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.selection</code></div><div class="role">defined by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.text</code></div><div class="role">defined by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>web_editor.assets</code></div><div class="role">defined by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>web_editor.converter.test</code></div><div class="role">defined by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>web_editor.converter.test.sub</code></div><div class="role">defined by <code>web_editor</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>base</code></div><div class="role">extended by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.attachment</code></div><div class="role">extended by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb</code></div><div class="role">extended by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field</code></div><div class="role">extended by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.contact</code></div><div class="role">extended by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.date</code></div><div class="role">extended by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.datetime</code></div><div class="role">extended by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.duration</code></div><div class="role">extended by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.float</code></div><div class="role">extended by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.html</code></div><div class="role">extended by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.image</code></div><div class="role">extended by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.integer</code></div><div class="role">extended by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.many2one</code></div><div class="role">extended by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.monetary</code></div><div class="role">extended by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.qweb</code></div><div class="role">extended by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.relative</code></div><div class="role">extended by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.selection</code></div><div class="role">extended by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.text</code></div><div class="role">extended by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.ui.view</code></div><div class="role">extended by <code>web_editor</code></div></div>
<div class="model"><div class="name"><code>ir.websocket</code></div><div class="role">extended by <code>web_editor</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from, model_extended_by | `agents/modules/generated/base.yaml` |
| `module.bus` | depends_on, extends_model_from | `agents/modules/generated/bus.yaml` |
| `module.mass_mailing` | required_by | `agents/modules/generated/mass_mailing.yaml` |
| `module.point_of_sale` | required_by | `agents/modules/generated/point_of_sale.yaml` |
| `module.portal` | required_by | `agents/modules/generated/portal.yaml` |
| `module.test_html_field_history` | model_extended_by, required_by | `agents/modules/generated/test_html_field_history.yaml` |
| `module.web` | depends_on, extends_model_from, model_extended_by | `agents/modules/generated/web.yaml` |
| `module.web_unsplash` | model_extended_by, required_by | `agents/modules/generated/web_unsplash.yaml` |
| `module.website` | extends_model_from, model_extended_by, required_by | `agents/modules/generated/website.yaml` |
| `module.website_blog` | model_extended_by | `agents/modules/generated/website_blog.yaml` |

## Full wiki excerpt

- SME owner: [`module.web_editor`](../../../agents/modules/generated/web_editor.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/web_editor)
- Direct dependencies: [`bus`](../bus/overview.md), [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`mass_mailing`](../mass_mailing/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`portal`](../portal/overview.md), [`test_html_field_history`](../test_html_field_history/overview.md), [`web_unsplash`](../web_unsplash/overview.md), [`website`](../website/overview.md)
- Impact graph: [`module:web_editor`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `html.field.history.mixin` — extended by [`test_html_field_history`](../test_html_field_history/overview.md)
- `ir.qweb.field` — extended by [`base`](../base/overview.md), [`website_blog`](../website_blog/overview.md)
- `ir.qweb.field.contact` — extended by [`website`](../website/overview.md)
- `ir.qweb.field.date`
- `ir.qweb.field.datetime`
- `ir.qweb.field.duration`
- `ir.qweb.field.float`
- `ir.qweb.field.html` — extended by [`website`](../website/overview.md)
- `ir.qweb.field.image` — extended by [`base`](../base/overview.md), [`web`](../web/overview.md), [`web_unsplash`](../web_unsplash/overview.md)
- `ir.qweb.field.integer`
- `ir.qweb.field.many2one` — extended by [`base`](../base/overview.md)
- `ir.qweb.field.monetary`
- `ir.qweb.field.qweb`
- `ir.qweb.field.relative`
- `ir.qweb.field.selection`
- `ir.qweb.field.text`
- `web_editor.assets` — extended by [`website`](../website/overview.md)
- `web_editor.converter.test`
- `web_editor.converter.test.sub`
- Extends `base` — defined by [`base`](../base/overview.md)
- Extends `ir.attachment` — defined by [`base`](../base/overview.md)
- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `ir.qweb` — defined by [`base`](../base/overview.md)
- Extends `ir.qweb.field` — defined by [`base`](../base/overview.md)
- Extends `ir.qweb.field.contact` — defined by [`base`](../base/overview.md)
- Extends `ir.qweb.field.date` — defined by [`base`](../base/overview.md)
- Extends `ir.qweb.field.datetime` — defined by [`base`](../base/overview.md)
- Extends `ir.qweb.field.duration` — defined by [`base`](../base/overview.md)
- Extends `ir.qweb.field.float` — defined by [`base`](../base/overview.md)
- Extends `ir.qweb.field.html` — defined by [`base`](../base/overview.md)
- Extends `ir.qweb.field.image` — defined by [`base`](../base/overview.md), [`web`](../web/overview.md)
- Extends `ir.qweb.field.integer` — defined by [`base`](../base/overview.md)
- Extends `ir.qweb.field.many2one` — defined by [`base`](../base/overview.md)
- Extends `ir.qweb.field.monetary` — defined by [`base`](../base/overview.md)
- Extends `ir.qweb.field.qweb` — defined by [`base`](../base/overview.md)
- Extends `ir.qweb.field.relative` — defined by [`base`](../base/overview.md)
- Extends `ir.qweb.field.selection` — defined by [`base`](../base/overview.md)
- Extends `ir.qweb.field.text` — defined by [`base`](../base/overview.md)
- Extends `ir.ui.view` — defined by [`website`](../website/overview.md)
- Extends `ir.websocket` — defined by [`bus`](../bus/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from, model_extended_by
- [`module.bus`](../../../agents/modules/generated/bus.yaml) — depends_on, extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — required_by
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — required_by
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — required_by
- [`module.test_html_field_history`](../../../agents/modules/generated/test_html_field_history.yaml) — model_extended_by, required_by
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.web_unsplash`](../../../agents/modules/generated/web_unsplash.yaml) — model_extended_by, required_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from, model_extended_by, required_by
- [`module.website_blog`](../../../agents/modules/generated/website_blog.yaml) — model_extended_by

## Regression impact checklist

- Review 6 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`base`](../base/overview.md), [`test_html_field_history`](../test_html_field_history/overview.md), [`web`](../web/overview.md), [`web_unsplash`](../web_unsplash/overview.md), [`website`](../website/overview.md), [`website_blog`](../website_blog/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md), [`bus`](../bus/overview.md), [`web`](../web/overview.md), [`website`](../website/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
