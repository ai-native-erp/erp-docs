---
layout: page
title: "Newsletter Subscribe Button (website_mass_mailing)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/website_mass_mailing/
nav_order: 0
---
# Newsletter Subscribe Button — `website_mass_mailing`

**Source:** [`agents/modules/generated/website_mass_mailing.yaml`](../../agents/modules/generated/website_mass_mailing.yaml) · **Wiki:** [`knowledge/modules/website_mass_mailing/overview.md`](../../knowledge/modules/website_mass_mailing/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>website_mass_mailing</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Newsletter Subscribe Button</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">website_ecommerce</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/website_mass_mailing</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_mass_mailing"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Attract visitors to subscribe to mailing lists

## Direct dependencies

[`google_recaptcha`](google_recaptcha.md), [`mass_mailing`](mass_mailing.md), [`website`](website.md)

## Reverse dependencies (modules that depend on this)

[`website_mass_mailing_sms`](website_mass_mailing_sms.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>website_mass_mailing</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.google_recaptcha` | depends_on | `agents/modules/generated/google_recaptcha.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | depends_on | `agents/modules/generated/mass_mailing.yaml` |
| `module.partner_autocomplete` | extends_model_from | `agents/modules/generated/partner_autocomplete.yaml` |
| `module.website` | depends_on | `agents/modules/generated/website.yaml` |
| `module.website_mass_mailing_sms` | required_by | `agents/modules/generated/website_mass_mailing_sms.yaml` |

## Full wiki excerpt

- SME owner: [`module.website_mass_mailing`](../../../agents/modules/generated/website_mass_mailing.yaml)
- Domain: `website_ecommerce`
- Category: Website/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/website_mass_mailing)
- Direct dependencies: [`google_recaptcha`](../google_recaptcha/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`website`](../website/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`website_mass_mailing_sms`](../website_mass_mailing_sms/overview.md)
- Impact graph: [`module:website_mass_mailing`](../../impact-graph.json)

## Purpose

Attract visitors to subscribe to mailing lists

## Model relationships

- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.google_recaptcha`](../../../agents/modules/generated/google_recaptcha.yaml) — depends_on
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — depends_on
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — depends_on
- [`module.website_mass_mailing_sms`](../../../agents/modules/generated/website_mass_mailing_sms.yaml) — required_by

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
