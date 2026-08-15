---
layout: page
title: "Unsplash Image Library (web_unsplash)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/web_unsplash/
nav_order: 0
---
# Unsplash Image Library — `web_unsplash`

**Source:** [`agents/modules/generated/web_unsplash.yaml`](../../agents/modules/generated/web_unsplash.yaml) · **Wiki:** [`knowledge/modules/web_unsplash/overview.md`](../../knowledge/modules/web_unsplash/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>web_unsplash</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Unsplash Image Library</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/web_unsplash</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/web_unsplash"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Find free high-resolution images from Unsplash

## Direct dependencies

[`base_setup`](base_setup.md), [`web_editor`](web_editor.md)

## Reverse dependencies (modules that depend on this)

[`test_website`](test_website.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.qweb.field.image</code></div><div class="role">extended by <code>web_unsplash</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>web_unsplash</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>web_unsplash</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.base_setup` | depends_on | `agents/modules/generated/base_setup.yaml` |
| `module.contacts` | extends_model_from | `agents/modules/generated/contacts.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | extends_model_from | `agents/modules/generated/mass_mailing_sms.yaml` |
| `module.test_website` | required_by | `agents/modules/generated/test_website.yaml` |
| `module.web` | extends_model_from | `agents/modules/generated/web.yaml` |
| `module.web_editor` | depends_on, extends_model_from | `agents/modules/generated/web_editor.yaml` |

## Full wiki excerpt

- SME owner: [`module.web_unsplash`](../../../agents/modules/generated/web_unsplash.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/web_unsplash)
- Direct dependencies: [`base_setup`](../base_setup/overview.md), [`web_editor`](../web_editor/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_website`](../test_website/overview.md)
- Impact graph: [`module:web_unsplash`](../../impact-graph.json)

## Purpose

Find free high-resolution images from Unsplash

## Model relationships

- Extends `ir.qweb.field.image` — defined by [`base`](../base/overview.md), [`web`](../web/overview.md), [`web_editor`](../web_editor/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.base_setup`](../../../agents/modules/generated/base_setup.yaml) — depends_on
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.test_website`](../../../agents/modules/generated/test_website.yaml) — required_by
- [`module.web`](../../../agents/modules/generated/web.yaml) — extends_model_from
- [`module.web_editor`](../../../agents/modules/generated/web_editor.yaml) — depends_on, extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`web`](../web/overview.md), [`web_editor`](../web_editor/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
