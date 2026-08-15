---
layout: page
title: "Twilio SMS (sms_twilio)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/sms_twilio/
nav_order: 0
---
# Twilio SMS — `sms_twilio`

**Source:** [`agents/modules/generated/sms_twilio.yaml`](../../agents/modules/generated/sms_twilio.yaml) · **Wiki:** [`knowledge/modules/sms_twilio/overview.md`](../../knowledge/modules/sms_twilio/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>sms_twilio</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Twilio SMS</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">integrations</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/sms_twilio</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sms_twilio"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Send SMS messages using Twilio

## Direct dependencies

[`sms`](sms.md)

## Reverse dependencies (modules that depend on this)

[`test_mail_sms`](test_mail_sms.md), [`test_mass_mailing`](test_mass_mailing.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>sms.twilio.account.manage</code></div><div class="role">defined by <code>sms_twilio</code></div></div>
<div class="model"><div class="name"><code>sms.twilio.number</code></div><div class="role">defined by <code>sms_twilio</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.notification</code></div><div class="role">extended by <code>sms_twilio</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>sms_twilio</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>sms_twilio</code></div></div>
<div class="model"><div class="name"><code>sms.composer</code></div><div class="role">extended by <code>sms_twilio</code></div></div>
<div class="model"><div class="name"><code>sms.sms</code></div><div class="role">extended by <code>sms_twilio</code></div></div>
<div class="model"><div class="name"><code>sms.tracker</code></div><div class="role">extended by <code>sms_twilio</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.partner_autocomplete` | extends_model_from | `agents/modules/generated/partner_autocomplete.yaml` |
| `module.sms` | depends_on, extends_model_from | `agents/modules/generated/sms.yaml` |
| `module.test_mail_sms` | required_by | `agents/modules/generated/test_mail_sms.yaml` |
| `module.test_mass_mailing` | required_by | `agents/modules/generated/test_mass_mailing.yaml` |

## Full wiki excerpt

- SME owner: [`module.sms_twilio`](../../../agents/modules/generated/sms_twilio.yaml)
- Domain: `integrations`
- Category: Hidden/Tools
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/sms_twilio)
- Direct dependencies: [`sms`](../sms/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_mail_sms`](../test_mail_sms/overview.md), [`test_mass_mailing`](../test_mass_mailing/overview.md)
- Impact graph: [`module:sms_twilio`](../../impact-graph.json)

## Purpose

Send SMS messages using Twilio

## Model relationships

- `sms.twilio.account.manage`
- `sms.twilio.number`
- Extends `mail.notification` — defined by [`mail`](../mail/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `sms.composer` — defined by [`sms`](../sms/overview.md)
- Extends `sms.sms` — defined by [`sms`](../sms/overview.md)
- Extends `sms.tracker` — defined by [`sms`](../sms/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — depends_on, extends_model_from
- [`module.test_mail_sms`](../../../agents/modules/generated/test_mail_sms.yaml) — required_by
- [`module.test_mass_mailing`](../../../agents/modules/generated/test_mass_mailing.yaml) — required_by

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`sms`](../sms/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
