---
layout: page
title: "Google Gmail (google_gmail)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/google_gmail/
nav_order: 0
---
# Google Gmail — `google_gmail`

**Source:** [`agents/modules/generated/google_gmail.yaml`](../../agents/modules/generated/google_gmail.yaml) · **Wiki:** [`knowledge/modules/google_gmail/overview.md`](../../knowledge/modules/google_gmail/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>google_gmail</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Google Gmail</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">integrations</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/google_gmail</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/google_gmail"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`mail`](mail.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>fetchmail.server</code></div><div class="role">defined by <code>google_gmail</code></div></div>
<div class="model"><div class="name"><code>google.gmail.mixin</code></div><div class="role">defined by <code>google_gmail</code></div></div>
<div class="model"><div class="name"><code>ir.mail_server</code></div><div class="role">defined by <code>google_gmail</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>fetchmail.server</code></div><div class="role">extended by <code>google_gmail</code></div></div>
<div class="model"><div class="name"><code>google.gmail.mixin</code></div><div class="role">extended by <code>google_gmail</code></div></div>
<div class="model"><div class="name"><code>ir.mail_server</code></div><div class="role">extended by <code>google_gmail</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>google_gmail</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.mail` | depends_on, extends_model_from, model_extended_by | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | extends_model_from, model_extended_by | `agents/modules/generated/mass_mailing.yaml` |
| `module.microsoft_outlook` | extends_model_from, model_extended_by | `agents/modules/generated/microsoft_outlook.yaml` |

## Full wiki excerpt

- SME owner: [`module.google_gmail`](../../../agents/modules/generated/google_gmail.yaml)
- Domain: `integrations`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/google_gmail)
- Direct dependencies: [`mail`](../mail/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:google_gmail`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `fetchmail.server` — extended by [`microsoft_outlook`](../microsoft_outlook/overview.md)
- `google.gmail.mixin`
- `ir.mail_server` — extended by [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`microsoft_outlook`](../microsoft_outlook/overview.md)
- Extends `fetchmail.server` — defined by [`mail`](../mail/overview.md), [`microsoft_outlook`](../microsoft_outlook/overview.md)
- Extends `google.gmail.mixin` — framework/dynamic owner
- Extends `ir.mail_server` — defined by [`base`](../base/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`microsoft_outlook`](../microsoft_outlook/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from, model_extended_by
- [`module.microsoft_outlook`](../../../agents/modules/generated/microsoft_outlook.yaml) — extends_model_from, model_extended_by

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`microsoft_outlook`](../microsoft_outlook/overview.md).
- Review model owners used by this module: [`base`](../base/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`microsoft_outlook`](../microsoft_outlook/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
