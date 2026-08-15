---
layout: page
title: "Mass Mail Tests (test_mass_mailing)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_mass_mailing/
nav_order: 0
---
# Mass Mail Tests — `test_mass_mailing`

**Source:** [`agents/modules/generated/test_mass_mailing.yaml`](../../agents/modules/generated/test_mass_mailing.yaml) · **Wiki:** [`knowledge/modules/test_mass_mailing/overview.md`](../../knowledge/modules/test_mass_mailing/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_mass_mailing</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Mass Mail Tests</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/test_mass_mailing</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_mass_mailing"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Mass Mail Tests: feature and performance tests for mass mailing

## Direct dependencies

[`mass_mailing`](mass_mailing.md), [`mass_mailing_sms`](mass_mailing_sms.md), [`sms_twilio`](sms_twilio.md), [`test_mail`](test_mail.md), [`test_mail_sms`](test_mail_sms.md)

## Reverse dependencies (modules that depend on this)

[`test_mail_full`](test_mail_full.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>mailing.performance</code></div><div class="role">defined by <code>test_mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.performance.blacklist</code></div><div class="role">defined by <code>test_mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.test.blacklist</code></div><div class="role">defined by <code>test_mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.test.customer</code></div><div class="role">defined by <code>test_mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.test.optout</code></div><div class="role">defined by <code>test_mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.test.partner</code></div><div class="role">defined by <code>test_mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.test.partner.unstored</code></div><div class="role">defined by <code>test_mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.test.simple</code></div><div class="role">defined by <code>test_mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mailing.test.utm</code></div><div class="role">defined by <code>test_mass_mailing</code></div></div>
<div class="model"><div class="name"><code>utm.test.source.mixin</code></div><div class="role">defined by <code>test_mass_mailing</code></div></div>
<div class="model"><div class="name"><code>utm.test.source.mixin.other</code></div><div class="role">defined by <code>test_mass_mailing</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.qweb</code></div><div class="role">extended by <code>test_mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>test_mass_mailing</code></div></div>
<div class="model"><div class="name"><code>mail.thread.blacklist</code></div><div class="role">extended by <code>test_mass_mailing</code></div></div>
<div class="model"><div class="name"><code>utm.mixin</code></div><div class="role">extended by <code>test_mass_mailing</code></div></div>
<div class="model"><div class="name"><code>utm.source.mixin</code></div><div class="role">extended by <code>test_mass_mailing</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | depends_on | `agents/modules/generated/mass_mailing.yaml` |
| `module.mass_mailing_sms` | depends_on | `agents/modules/generated/mass_mailing_sms.yaml` |
| `module.sms_twilio` | depends_on | `agents/modules/generated/sms_twilio.yaml` |
| `module.test_mail` | depends_on | `agents/modules/generated/test_mail.yaml` |
| `module.test_mail_full` | required_by | `agents/modules/generated/test_mail_full.yaml` |
| `module.test_mail_sms` | depends_on | `agents/modules/generated/test_mail_sms.yaml` |
| `module.utm` | extends_model_from | `agents/modules/generated/utm.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_mass_mailing`](../../../agents/modules/generated/test_mass_mailing.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_mass_mailing)
- Direct dependencies: [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`sms_twilio`](../sms_twilio/overview.md), [`test_mail`](../test_mail/overview.md), [`test_mail_sms`](../test_mail_sms/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`test_mail_full`](../test_mail_full/overview.md)
- Impact graph: [`module:test_mass_mailing`](../../impact-graph.json)

## Purpose

Mass Mail Tests: feature and performance tests for mass mailing

## Model relationships

- `mailing.performance`
- `mailing.performance.blacklist`
- `mailing.test.blacklist`
- `mailing.test.customer`
- `mailing.test.optout`
- `mailing.test.partner`
- `mailing.test.partner.unstored`
- `mailing.test.simple`
- `mailing.test.utm`
- `utm.test.source.mixin`
- `utm.test.source.mixin.other`
- Extends `ir.qweb` — defined by [`base`](../base/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread.blacklist` — defined by [`mail`](../mail/overview.md)
- Extends `utm.mixin` — defined by [`utm`](../utm/overview.md)
- Extends `utm.source.mixin` — defined by [`utm`](../utm/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — depends_on
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — depends_on
- [`module.sms_twilio`](../../../agents/modules/generated/sms_twilio.yaml) — depends_on
- [`module.test_mail`](../../../agents/modules/generated/test_mail.yaml) — depends_on
- [`module.test_mail_full`](../../../agents/modules/generated/test_mail_full.yaml) — required_by
- [`module.test_mail_sms`](../../../agents/modules/generated/test_mail_sms.yaml) — depends_on
- [`module.utm`](../../../agents/modules/generated/utm.yaml) — extends_model_from

## Regression impact checklist

- Review 1 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md), [`mail`](../mail/overview.md), [`utm`](../utm/overview.md).
- Required specialist reviewers: security_reviewer.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
