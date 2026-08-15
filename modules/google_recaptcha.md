---
layout: page
title: "Google reCAPTCHA integration (google_recaptcha)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/google_recaptcha/
nav_order: 0
---
# Google reCAPTCHA integration — `google_recaptcha`

**Source:** [`agents/modules/generated/google_recaptcha.yaml`](../../agents/modules/generated/google_recaptcha.yaml) · **Wiki:** [`knowledge/modules/google_recaptcha/overview.md`](../../knowledge/modules/google_recaptcha/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>google_recaptcha</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Google reCAPTCHA integration</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">integrations</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/google_recaptcha</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/google_recaptcha"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base_setup`](base_setup.md)

## Reverse dependencies (modules that depend on this)

[`website`](website.md), [`website_mass_mailing`](website_mass_mailing.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>google_recaptcha</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>google_recaptcha</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.base_setup` | depends_on | `agents/modules/generated/base_setup.yaml` |
| `module.website` | required_by | `agents/modules/generated/website.yaml` |
| `module.website_mass_mailing` | required_by | `agents/modules/generated/website_mass_mailing.yaml` |

## Full wiki excerpt

- SME owner: [`module.google_recaptcha`](../../../agents/modules/generated/google_recaptcha.yaml)
- Domain: `integrations`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/google_recaptcha)
- Direct dependencies: [`base_setup`](../base_setup/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`website`](../website/overview.md), [`website_mass_mailing`](../website_mass_mailing/overview.md)
- Impact graph: [`module:google_recaptcha`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.base_setup`](../../../agents/modules/generated/base_setup.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — required_by
- [`module.website_mass_mailing`](../../../agents/modules/generated/website_mass_mailing.yaml) — required_by

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md).
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
