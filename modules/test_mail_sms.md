---
layout: page
title: "SMS Tests (test_mail_sms)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_mail_sms/
nav_order: 0
---
# SMS Tests — `test_mail_sms`

**Source:** [`agents/modules/generated/test_mail_sms.yaml`](../../agents/modules/generated/test_mail_sms.yaml) · **Wiki:** [`knowledge/modules/test_mail_sms/overview.md`](../../knowledge/modules/test_mail_sms/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_mail_sms</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">SMS Tests</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/test_mail_sms</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_mail_sms"><code>126b5bd</code></a></div></div>
</div>
## Purpose

SMS Tests: performances and tests specific to SMS

## Direct dependencies

[`mail`](mail.md), [`sms`](sms.md), [`sms_twilio`](sms_twilio.md), [`test_performance`](test_performance.md)

## Reverse dependencies (modules that depend on this)

[`test_mail_full`](test_mail_full.md), [`test_mass_mailing`](test_mass_mailing.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.test.sms</code></div><div class="role">defined by <code>test_mail_sms</code></div></div>
<div class="model"><div class="name"><code>mail.test.sms.bl</code></div><div class="role">defined by <code>test_mail_sms</code></div></div>
<div class="model"><div class="name"><code>mail.test.sms.bl.activity</code></div><div class="role">defined by <code>test_mail_sms</code></div></div>
<div class="model"><div class="name"><code>mail.test.sms.bl.optout</code></div><div class="role">defined by <code>test_mail_sms</code></div></div>
<div class="model"><div class="name"><code>mail.test.sms.partner</code></div><div class="role">defined by <code>test_mail_sms</code></div></div>
<div class="model"><div class="name"><code>mail.test.sms.partner.2many</code></div><div class="role">defined by <code>test_mail_sms</code></div></div>
<div class="model"><div class="name"><code>sms.test.nothread</code></div><div class="role">defined by <code>test_mail_sms</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>test_mail_sms</code></div></div>
<div class="model"><div class="name"><code>mail.test.sms.bl</code></div><div class="role">extended by <code>test_mail_sms</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>test_mail_sms</code></div></div>
<div class="model"><div class="name"><code>mail.thread.phone</code></div><div class="role">extended by <code>test_mail_sms</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mail` | depends_on, extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.phone_validation` | extends_model_from | `agents/modules/generated/phone_validation.yaml` |
| `module.sms` | depends_on | `agents/modules/generated/sms.yaml` |
| `module.sms_twilio` | depends_on | `agents/modules/generated/sms_twilio.yaml` |
| `module.test_mail_full` | required_by | `agents/modules/generated/test_mail_full.yaml` |
| `module.test_mass_mailing` | required_by | `agents/modules/generated/test_mass_mailing.yaml` |
| `module.test_performance` | depends_on | `agents/modules/generated/test_performance.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_mail_sms`](../../../agents/modules/generated/test_mail_sms.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_mail_sms)
- Direct dependencies: [`mail`](../mail/overview.md), [`sms`](../sms/overview.md), [`sms_twilio`](../sms_twilio/overview.md), [`test_performance`](../test_performance/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_mail_full`](../test_mail_full/overview.md), [`test_mass_mailing`](../test_mass_mailing/overview.md)
- Impact graph: [`module:test_mail_sms`](../../impact-graph.json)

## Purpose

SMS Tests: performances and tests specific to SMS

## Model relationships

- `mail.test.sms`
- `mail.test.sms.bl`
- `mail.test.sms.bl.activity`
- `mail.test.sms.bl.optout`
- `mail.test.sms.partner`
- `mail.test.sms.partner.2many`
- `sms.test.nothread`
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.test.sms.bl` — framework/dynamic owner
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread.phone` — defined by [`phone_validation`](../phone_validation/overview.md)

## Related SME agents

- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — depends_on
- [`module.sms_twilio`](../../../agents/modules/generated/sms_twilio.yaml) — depends_on
- [`module.test_mail_full`](../../../agents/modules/generated/test_mail_full.yaml) — required_by
- [`module.test_mass_mailing`](../../../agents/modules/generated/test_mass_mailing.yaml) — required_by
- [`module.test_performance`](../../../agents/modules/generated/test_performance.yaml) — depends_on

## Regression impact checklist

- Review 2 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`mail`](../mail/overview.md), [`phone_validation`](../phone_validation/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
