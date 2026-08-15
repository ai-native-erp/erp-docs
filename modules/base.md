---
layout: page
title: "Base (base)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/base/
nav_order: 0
---
# Base — `base`

**Source:** [`agents/modules/generated/base.yaml`](../../agents/modules/generated/base.yaml) · **Wiki:** [`knowledge/modules/base/overview.md`](../../knowledge/modules/base/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>base</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Base</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>odoo/addons/base</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Reverse dependencies (modules that depend on this)

[`analytic`](analytic.md), [`auth_ldap`](auth_ldap.md), [`auth_oauth`](auth_oauth.md), [`base_address_extended`](base_address_extended.md), [`base_automation`](base_automation.md), [`base_setup`](base_setup.md), [`base_sparse_field`](base_sparse_field.md), [`bus`](bus.md), [`calendar`](calendar.md), [`contacts`](contacts.md), [`fleet`](fleet.md), [`l10n_ae`](l10n_ae.md), [`l10n_cn`](l10n_cn.md), [`l10n_ec`](l10n_ec.md), [`l10n_gt`](l10n_gt.md), [`l10n_hn`](l10n_hn.md), [`l10n_ma`](l10n_ma.md), [`l10n_mz`](l10n_mz.md), [`l10n_pt`](l10n_pt.md), [`mail`](mail.md), [`phone_validation`](phone_validation.md), [`product`](product.md), [`resource`](resource.md), [`sales_team`](sales_team.md), [`sms`](sms.md), [`social_media`](social_media.md), [`test_assetsbundle`](test_assetsbundle.md), [`test_converter`](test_converter.md), [`test_exceptions`](test_exceptions.md), [`test_http`](test_http.md), [`test_impex`](test_impex.md), [`test_inherit`](test_inherit.md), [`test_inherits`](test_inherits.md), [`test_limits`](test_limits.md), [`test_lint`](test_lint.md), [`test_new_api`](test_new_api.md), [`test_performance`](test_performance.md), [`test_populate`](test_populate.md), [`test_read_group`](test_read_group.md), [`test_rpc`](test_rpc.md), [`test_testing_utilities`](test_testing_utilities.md), [`test_translation_import`](test_translation_import.md), [`test_uninstall`](test_uninstall.md), [`transifex`](transifex.md), [`uom`](uom.md), [`utm`](utm.md), [`web`](web.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>_unknown</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>avatar.mixin</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>base</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>base.enable.profiling.wizard</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>base.language.export</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>base.language.import</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>base.language.install</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>base.module.uninstall</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>base.module.update</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>base.module.upgrade</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>base.partner.merge.automatic.wizard</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>base.partner.merge.line</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>change.password.own</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>change.password.user</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>change.password.wizard</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>decimal.precision</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>format.address.mixin</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>image.mixin</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.actions.act_url</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.actions.act_window</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.actions.act_window.view</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.actions.act_window_close</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.actions.actions</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.actions.client</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.actions.report</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.actions.server</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.actions.todo</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.asset</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.attachment</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.autovacuum</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.binary</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.config_parameter</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.cron</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.cron.trigger</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.default</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.demo</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.demo_failure</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.demo_failure.wizard</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.exports</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.exports.line</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.fields.converter</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.filters</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.logging</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.mail_server</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.model</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.model.access</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.model.constraint</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.model.data</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.model.fields</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.model.fields.selection</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.model.inherit</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.model.relation</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.module.category</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.module.module</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.module.module.dependency</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.module.module.exclusion</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.profile</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.property</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.barcode</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.contact</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.date</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.datetime</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.duration</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.float</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.float_time</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.html</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.image</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.image_url</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.integer</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.many2many</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.many2one</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.monetary</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.one2many</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.qweb</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.relative</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.selection</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.text</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.time</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.rule</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.sequence</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.sequence.date_range</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.ui.menu</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>report.base.report_irmodulereference</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>report.layout</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>report.paperformat</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.bank</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.config</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.config.installer</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.country</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.country.group</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.country.state</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.currency</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.currency.rate</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.groups</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.lang</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.partner.bank</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.partner.category</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.partner.industry</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.partner.title</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.users.apikeys</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.users.apikeys.description</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.users.apikeys.show</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.users.deletion</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.users.identitycheck</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.users.log</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.users.settings</code></div><div class="role">defined by <code>base</code></div></div>
<div class="model"><div class="name"><code>wizard.ir.model.menu.create</code></div><div class="role">defined by <code>base</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>avatar.mixin</code></div><div class="role">extended by <code>base</code></div></div>
<div class="model"><div class="name"><code>format.address.mixin</code></div><div class="role">extended by <code>base</code></div></div>
<div class="model"><div class="name"><code>image.mixin</code></div><div class="role">extended by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.actions.actions</code></div><div class="role">extended by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.filters</code></div><div class="role">extended by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.module.category</code></div><div class="role">extended by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field</code></div><div class="role">extended by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.image</code></div><div class="role">extended by <code>base</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.many2one</code></div><div class="role">extended by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.config</code></div><div class="role">extended by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.currency.rate</code></div><div class="role">extended by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.groups</code></div><div class="role">extended by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.partner.industry</code></div><div class="role">extended by <code>base</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>base</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from, model_extended_by | `agents/modules/generated/account.yaml` |
| `module.account_add_gln` | model_extended_by | `agents/modules/generated/account_add_gln.yaml` |
| `module.account_audit_trail` | model_extended_by | `agents/modules/generated/account_audit_trail.yaml` |
| `module.account_check_printing` | model_extended_by | `agents/modules/generated/account_check_printing.yaml` |
| `module.account_edi` | model_extended_by | `agents/modules/generated/account_edi.yaml` |
| `module.account_edi_proxy_client` | model_extended_by | `agents/modules/generated/account_edi_proxy_client.yaml` |
| `module.account_edi_ubl_cii` | model_extended_by | `agents/modules/generated/account_edi_ubl_cii.yaml` |
| `module.account_lock` | model_extended_by | `agents/modules/generated/account_lock.yaml` |
| `module.account_payment` | model_extended_by | `agents/modules/generated/account_payment.yaml` |
| `module.account_peppol` | model_extended_by | `agents/modules/generated/account_peppol.yaml` |

## Conversation learnings

- [`2026-08-10-odoo-customization-testing`](../../knowledge/conversations/2026-08-10-odoo-customization-testing.json)
- [`2026-08-10-odoo-postgres-mcp`](../../knowledge/conversations/2026-08-10-odoo-postgres-mcp.json)
- [`2026-08-11-odoo-licensing-product-architecture`](../../knowledge/conversations/2026-08-11-odoo-licensing-product-architecture.json)
- [`2026-08-11-repository-domain-extraction`](../../knowledge/conversations/2026-08-11-repository-domain-extraction.json)
- [`2026-08-12-cmr-backup-restore-capacity`](../../knowledge/conversations/2026-08-12-cmr-backup-restore-capacity.json)
- [`2026-08-12-cmr-endpoint-bootstrap-enterprise-gate`](../../knowledge/conversations/2026-08-12-cmr-endpoint-bootstrap-enterprise-gate.json)
- [`2026-08-12-cmr-ho-store-isolation`](../../knowledge/conversations/2026-08-12-cmr-ho-store-isolation.json)
- [`2026-08-13-customer-addon-mount-preflight`](../../knowledge/conversations/2026-08-13-customer-addon-mount-preflight.json)
- [`2026-08-13-external-colima-capacity`](../../knowledge/conversations/2026-08-13-external-colima-capacity.json)
- [`2026-08-13-ho-enterprise-source-gap`](../../knowledge/conversations/2026-08-13-ho-enterprise-source-gap.json)
- [`2026-08-13-ho-missing-enterprise-metadata-quarantine`](../../knowledge/conversations/2026-08-13-ho-missing-enterprise-metadata-quarantine.json)
- [`2026-08-13-ho-partial-registry-landing-repair`](../../knowledge/conversations/2026-08-13-ho-partial-registry-landing-repair.json)
- [`2026-08-13-odoo-service-manager-mcp`](../../knowledge/conversations/2026-08-13-odoo-service-manager-mcp.json)
- [`2026-08-14-ctl-fashion-isolated-restore`](../../knowledge/conversations/2026-08-14-ctl-fashion-isolated-restore.json)
- [`2026-08-14-customer-source-lossless-delta-consolidation`](../../knowledge/conversations/2026-08-14-customer-source-lossless-delta-consolidation.json)
- [`2026-08-14-ho-customer-schema-drift-upgrade`](../../knowledge/conversations/2026-08-14-ho-customer-schema-drift-upgrade.json)
- [`2026-08-14-ho-enterprise-source-restored`](../../knowledge/conversations/2026-08-14-ho-enterprise-source-restored.json)
- [`2026-08-14-ho-enterprise-view-compatibility`](../../knowledge/conversations/2026-08-14-ho-enterprise-view-compatibility.json)
- [`2026-08-14-local-proprietary-dependency-consolidation`](../../knowledge/conversations/2026-08-14-local-proprietary-dependency-consolidation.json)
- [`2026-08-14-portable-odoodata-layout`](../../knowledge/conversations/2026-08-14-portable-odoodata-layout.json)

## Full wiki excerpt

- SME owner: [`module.base`](../../../agents/modules/generated/base.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base)
- Direct dependencies: None
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`analytic`](../analytic/overview.md), [`auth_ldap`](../auth_ldap/overview.md), [`auth_oauth`](../auth_oauth/overview.md), [`base_address_extended`](../base_address_extended/overview.md), [`base_automation`](../base_automation/overview.md), [`base_setup`](../base_setup/overview.md), [`base_sparse_field`](../base_sparse_field/overview.md), [`bus`](../bus/overview.md), [`calendar`](../calendar/overview.md), [`contacts`](../contacts/overview.md), [`fleet`](../fleet/overview.md), [`l10n_ae`](../l10n_ae/overview.md), [`l10n_cn`](../l10n_cn/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_gt`](../l10n_gt/overview.md), [`l10n_hn`](../l10n_hn/overview.md), [`l10n_ma`](../l10n_ma/overview.md), [`l10n_mz`](../l10n_mz/overview.md), [`l10n_pt`](../l10n_pt/overview.md), [`mail`](../mail/overview.md), [`phone_validation`](../phone_validation/overview.md), [`product`](../product/overview.md), [`resource`](../resource/overview.md), [`sales_team`](../sales_team/overview.md), [`sms`](../sms/overview.md), [`social_media`](../social_media/overview.md), [`test_assetsbundle`](../test_assetsbundle/overview.md), [`test_converter`](../test_converter/overview.md), [`test_exceptions`](../test_exceptions/overview.md), [`test_http`](../test_http/overview.md), [`test_impex`](../test_impex/overview.md), [`test_inherit`](../test_inherit/overview.md), [`test_inherits`](../test_inherits/overview.md), [`test_limits`](../test_limits/overview.md), [`test_lint`](../test_lint/overview.md), [`test_new_api`](../test_new_api/overview.md), [`test_performance`](../test_performance/overview.md), [`test_populate`](../test_populate/overview.md), [`test_read_group`](../test_read_group/overview.md), [`test_rpc`](../test_rpc/overview.md), [`test_testing_utilities`](../test_testing_utilities/overview.md), [`test_translation_import`](../test_translation_import/overview.md), [`test_uninstall`](../test_uninstall/overview.md), [`transifex`](../transifex/overview.md), [`uom`](../uom/overview.md), [`utm`](../utm/overview.md), [`web`](../web/overview.md)
- Impact graph: [`module:base`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `_unknown`
- `avatar.mixin` — extended by [`fleet`](../fleet/overview.md), [`hr`](../hr/overview.md), [`mail`](../mail/overview.md)
- `base` — extended by [`base_import`](../base_import/overview.md), [`base_sparse_field`](../base_sparse_field/overview.md), [`hr`](../hr/overview.md), [`mail`](../mail/overview.md), [`phone_validation`](../phone_validation/overview.md), [`sms`](../sms/overview.md), [`transifex`](../transifex/overview.md), [`web`](../web/overview.md), [`web_editor`](../web_editor/overview.md), [`web_hierarchy`](../web_hierarchy/overview.md), [`website`](../website/overview.md)
- `base.enable.profiling.wizard`
- `base.language.export`
- `base.language.import`
- `base.language.install` — extended by [`website`](../website/overview.md)
- `base.module.uninstall` — extended by [`base_import_module`](../base_import_module/overview.md), [`mail`](../mail/overview.md)
- `base.module.update`
- `base.module.upgrade`
- `base.partner.merge.automatic.wizard` — extended by [`account`](../account/overview.md), [`account_audit_trail`](../account_audit_trail/overview.md), [`mail`](../mail/overview.md), [`website`](../website/overview.md), [`website_slides`](../website_slides/overview.md)
- `base.partner.merge.line`
- `change.password.own`
- `change.password.user`
- `change.password.wizard`
- `decimal.precision` — extended by [`account`](../account/overview.md), [`product`](../product/overview.md)
- `format.address.mixin` — extended by [`crm`](../crm/overview.md)
- `image.mixin` — extended by [`event_booth`](../event_booth/overview.md), [`gamification`](../gamification/overview.md), [`im_livechat`](../im_livechat/overview.md), [`lunch`](../lunch/overview.md), [`product`](../product/overview.md), [`website_forum`](../website_forum/overview.md), [`website_sale`](../website_sale/overview.md), [`website_slides`](../website_slides/overview.md)
- `ir.actions.act_url`
- `ir.actions.act_window`
- `ir.actions.act_window.view` — extended by [`mail`](../mail/overview.md), [`web_hierarchy`](../web_hierarchy/overview.md)
- `ir.actions.act_window_close`
- `ir.actions.actions`
- `ir.actions.client`
- `ir.actions.report` — extended by [`account`](../account/overview.md), [`account_edi`](../account_edi/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_ch`](../l10n_ch/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_th`](../l10n_th/overview.md), [`sale_pdf_quote_builder`](../sale_pdf_quote_builder/overview.md), [`snailmail`](../snailmail/overview.md), [`stock`](../stock/overview.md)
- `ir.actions.server` — extended by [`mail`](../mail/overview.md), [`sms`](../sms/overview.md), [`website`](../website/overview.md)
- `ir.actions.todo`
- `ir.asset` — extended by [`website`](../website/overview.md)
- `ir.attachment` — extended by [`account`](../account/overview.md), [`account_edi`](../account_edi/overview.md), [`attachment_indexation`](../attachment_indexation/overview.md), [`hr_expense`](../hr_expense/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_es_edi_tbai`](../l10n_es_edi_tbai/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_jo_edi`](../l10n_jo_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`mail`](../mail/overview.md), [`mrp`](../mrp/overview.md), [`product`](../product/overview.md), [`web_editor`](../web_editor/overview.md), [`website`](../website/overview.md), [`website_forum`](../website_forum/overview.md)
- `ir.autovacuum`
- `ir.binary` — extended by [`website`](../website/overview.md), [`website_slides`](../website_slides/overview.md)
- `ir.config_parameter` — extended by [`analytic`](../analytic/overview.md), [`auth_oauth`](../auth_oauth/overview.md), [`crm`](../crm/overview.md), [`mail`](../mail/overview.md), [`sale`](../sale/overview.md)
- `ir.cron`
- `ir.cron.trigger` — extended by [`product_images`](../product_images/overview.md)
- `ir.default`
- `ir.demo`
- `ir.demo_failure`
- `ir.demo_failure.wizard`
- `ir.exports`
- `ir.exports.line`
- `ir.fields.converter`
- `ir.filters`
- `ir.http` — extended by [`account`](../account/overview.md), [`auth_signup`](../auth_signup/overview.md), [`auth_totp`](../auth_totp/overview.md), [`barcodes`](../barcodes/overview.md), [`barcodes_gs1_nomenclature`](../barcodes_gs1_nomenclature/overview.md), [`base_setup`](../base_setup/overview.md), [`bus`](../bus/overview.md), [`calendar`](../calendar/overview.md), [`google_recaptcha`](../google_recaptcha/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`http_routing`](../http_routing/overview.md), [`mail`](../mail/overview.md), [`mail_bot`](../mail_bot/overview.md), [`mail_plugin`](../mail_plugin/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`payment`](../payment/overview.md), [`portal`](../portal/overview.md), [`portal_rating`](../portal_rating/overview.md), [`pos_self_order`](../pos_self_order/overview.md), [`survey`](../survey/overview.md), [`test_auth_custom`](../test_auth_custom/overview.md), [`utm`](../utm/overview.md), [`web`](../web/overview.md), [`web_editor`](../web_editor/overview.md), [`web_tour`](../web_tour/overview.md), [`website`](../website/overview.md), [`website_cf_turnstile`](../website_cf_turnstile/overview.md), [`website_crm_iap_reveal`](../website_crm_iap_reveal/overview.md), [`website_livechat`](../website_livechat/overview.md), [`website_sale`](../website_sale/overview.md)
- `ir.logging`
- `ir.mail_server` — extended by [`google_gmail`](../google_gmail/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`microsoft_outlook`](../microsoft_outlook/overview.md)
- `ir.model` — extended by [`bus`](../bus/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`sms`](../sms/overview.md), [`web`](../web/overview.md), [`website`](../website/overview.md)
- `ir.model.access`
- `ir.model.constraint`
- `ir.model.data` — extended by [`website`](../website/overview.md)
- `ir.model.fields` — extended by [`base_sparse_field`](../base_sparse_field/overview.md), [`mail`](../mail/overview.md), [`website`](../website/overview.md)
- `ir.model.fields.selection`
- `ir.model.inherit`
- `ir.model.relation`
- `ir.module.category`
- `ir.module.module` — extended by [`account`](../account/overview.md), [`base_import_module`](../base_import_module/overview.md), [`base_install_request`](../base_install_request/overview.md)
- `ir.module.module.dependency`
- `ir.module.module.exclusion`
- `ir.profile`
- `ir.property`
- `ir.qweb` — extended by [`bus`](../bus/overview.md), [`http_routing`](../http_routing/overview.md), [`im_livechat`](../im_livechat/overview.md), [`mail`](../mail/overview.md), [`portal`](../portal/overview.md), [`test_assetsbundle`](../test_assetsbundle/overview.md), [`test_mass_mailing`](../test_mass_mailing/overview.md), [`web_editor`](../web_editor/overview.md), [`website`](../website/overview.md)
- `ir.qweb.field` — extended by [`web_editor`](../web_editor/overview.md), [`website_blog`](../website_blog/overview.md)
- `ir.qweb.field.barcode`
- `ir.qweb.field.contact` — extended by [`web_editor`](../web_editor/overview.md), [`website`](../website/overview.md)
- `ir.qweb.field.date` — extended by [`web_editor`](../web_editor/overview.md)
- `ir.qweb.field.datetime` — extended by [`web_editor`](../web_editor/overview.md)
- `ir.qweb.field.duration` — extended by [`web_editor`](../web_editor/overview.md)
- `ir.qweb.field.float` — extended by [`web_editor`](../web_editor/overview.md)
- `ir.qweb.field.float_time`
- `ir.qweb.field.html` — extended by [`web_editor`](../web_editor/overview.md), [`website`](../website/overview.md)
- `ir.qweb.field.image` — extended by [`web`](../web/overview.md), [`web_editor`](../web_editor/overview.md), [`web_unsplash`](../web_unsplash/overview.md)
- `ir.qweb.field.image_url` — extended by [`web`](../web/overview.md)
- `ir.qweb.field.integer` — extended by [`web_editor`](../web_editor/overview.md)
- `ir.qweb.field.many2many`
- `ir.qweb.field.many2one` — extended by [`web_editor`](../web_editor/overview.md)
- `ir.qweb.field.monetary` — extended by [`web_editor`](../web_editor/overview.md)
- `ir.qweb.field.one2many`
- `ir.qweb.field.qweb` — extended by [`web_editor`](../web_editor/overview.md)
- `ir.qweb.field.relative` — extended by [`web_editor`](../web_editor/overview.md)
- `ir.qweb.field.selection` — extended by [`web_editor`](../web_editor/overview.md)
- `ir.qweb.field.text` — extended by [`web_editor`](../web_editor/overview.md)
- `ir.qweb.field.time`
- `ir.rule` — extended by [`website`](../website/overview.md)
- `ir.sequence`
- `ir.sequence.date_range`
- `ir.ui.menu` — extended by [`hr`](../hr/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`hr_timesheet_attendance`](../hr_timesheet_attendance/overview.md), [`project`](../project/overview.md), [`web`](../web/overview.md), [`website`](../website/overview.md)
- `report.base.report_irmodulereference`
- `report.layout`
- `report.paperformat`
- `res.bank` — extended by [`l10n_cl`](../l10n_cl/overview.md), [`l10n_mx`](../l10n_mx/overview.md)
- `res.company` — extended by [`account`](../account/overview.md), [`account_audit_trail`](../account_audit_trail/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_edi_proxy_client`](../account_edi_proxy_client/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_lock`](../account_lock/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_response`](../account_peppol_response/overview.md), [`auth_ldap`](../auth_ldap/overview.md), [`barcodes`](../barcodes/overview.md), [`base_vat`](../base_vat/overview.md), [`hr`](../hr/overview.md), [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_holidays_attendance`](../hr_holidays_attendance/overview.md), [`hr_presence`](../hr_presence/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ar_withholding`](../l10n_ar_withholding/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_ca`](../l10n_ca/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_cz`](../l10n_cz/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_sii`](../l10n_es_edi_sii/overview.md), [`l10n_es_edi_tbai`](../l10n_es_edi_tbai/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_es_edi_verifactu_pos`](../l10n_es_edi_verifactu_pos/overview.md), [`l10n_es_pos_tbai`](../l10n_es_pos_tbai/overview.md), [`l10n_eu_oss`](../l10n_eu_oss/overview.md), [`l10n_fr`](../l10n_fr/overview.md), [`l10n_fr_hr_holidays`](../l10n_fr_hr_holidays/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_fr_pdp_pos`](../l10n_fr_pdp_pos/overview.md), [`l10n_fr_pos_cert`](../l10n_fr_pos_cert/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_in_edi`](../l10n_in_edi/overview.md), [`l10n_in_edi_ewaybill`](../l10n_in_edi_ewaybill/overview.md), [`l10n_in_withholding`](../l10n_in_withholding/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_jo_edi`](../l10n_jo_edi/overview.md), [`l10n_jo_edi_extended`](../l10n_jo_edi_extended/overview.md), [`l10n_ke`](../l10n_ke/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_latam_base`](../l10n_latam_base/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_ubl_pint`](../l10n_my_ubl_pint/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro_efactura`](../l10n_ro_efactura/overview.md), [`l10n_ro_efactura_synchronize`](../l10n_ro_efactura_synchronize/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_sk`](../l10n_sk/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`lunch`](../lunch/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mrp`](../mrp/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`mrp_subcontracting_dropshipping`](../mrp_subcontracting_dropshipping/overview.md), [`onboarding`](../onboarding/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`payment`](../payment/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`product`](../product/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`resource`](../resource/overview.md), [`sale`](../sale/overview.md), [`sale_management`](../sale_management/overview.md), [`sale_pdf_quote_builder`](../sale_pdf_quote_builder/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sms`](../sms/overview.md), [`sms_twilio`](../sms_twilio/overview.md), [`snailmail`](../snailmail/overview.md), [`snailmail_account`](../snailmail_account/overview.md), [`social_media`](../social_media/overview.md), [`spreadsheet_account`](../spreadsheet_account/overview.md), [`stock`](../stock/overview.md), [`stock_dropshipping`](../stock_dropshipping/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`stock_sms`](../stock_sms/overview.md), [`web`](../web/overview.md), [`website`](../website/overview.md), [`website_mass_mailing`](../website_mass_mailing/overview.md), [`website_sale`](../website_sale/overview.md)
- `res.config`
- `res.config.installer`
- `res.config.settings` — extended by [`account`](../account/overview.md), [`account_audit_trail`](../account_audit_trail/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_payment`](../account_payment/overview.md), [`account_peppol`](../account_peppol/overview.md), [`analytic`](../analytic/overview.md), [`auth_ldap`](../auth_ldap/overview.md), [`auth_oauth`](../auth_oauth/overview.md), [`auth_password_policy`](../auth_password_policy/overview.md), [`auth_signup`](../auth_signup/overview.md), [`auth_totp_mail_enforce`](../auth_totp_mail_enforce/overview.md), [`base_geolocalize`](../base_geolocalize/overview.md), [`base_setup`](../base_setup/overview.md), [`base_vat`](../base_vat/overview.md), [`crm`](../crm/overview.md), [`crm_iap_enrich`](../crm_iap_enrich/overview.md), [`digest`](../digest/overview.md), [`event`](../event/overview.md), [`fleet`](../fleet/overview.md), [`google_calendar`](../google_calendar/overview.md), [`google_gmail`](../google_gmail/overview.md), [`google_recaptcha`](../google_recaptcha/overview.md), [`hr`](../hr/overview.md), [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`l10n_ar_withholding`](../l10n_ar_withholding/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es_edi_sii`](../l10n_es_edi_sii/overview.md), [`l10n_es_edi_tbai`](../l10n_es_edi_tbai/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_es_pos`](../l10n_es_pos/overview.md), [`l10n_eu_oss`](../l10n_eu_oss/overview.md), [`l10n_fr_hr_holidays`](../l10n_fr_hr_holidays/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur`](../l10n_id_efaktur/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_in_edi`](../l10n_in_edi/overview.md), [`l10n_in_edi_ewaybill`](../l10n_in_edi_ewaybill/overview.md), [`l10n_in_withholding`](../l10n_in_withholding/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_jo_edi`](../l10n_jo_edi/overview.md), [`l10n_jo_edi_extended`](../l10n_jo_edi_extended/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_mx`](../l10n_mx/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro_efactura`](../l10n_ro_efactura/overview.md), [`l10n_ro_efactura_synchronize`](../l10n_ro_efactura_synchronize/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`lunch`](../lunch/overview.md), [`mail`](../mail/overview.md), [`maintenance`](../maintenance/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md), [`microsoft_outlook`](../microsoft_outlook/overview.md), [`mrp`](../mrp/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`portal`](../portal/overview.md), [`pos_adyen`](../pos_adyen/overview.md), [`pos_discount`](../pos_discount/overview.md), [`pos_epson_printer`](../pos_epson_printer/overview.md), [`pos_hr`](../pos_hr/overview.md), [`pos_loyalty`](../pos_loyalty/overview.md), [`pos_online_payment_self_order`](../pos_online_payment_self_order/overview.md), [`pos_restaurant`](../pos_restaurant/overview.md), [`pos_sale`](../pos_sale/overview.md), [`pos_self_order`](../pos_self_order/overview.md), [`pos_self_order_sale`](../pos_self_order_sale/overview.md), [`product`](../product/overview.md), [`product_expiry`](../product_expiry/overview.md), [`product_images`](../product_images/overview.md), [`project`](../project/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`sale_management`](../sale_management/overview.md), [`sale_pdf_quote_builder`](../sale_pdf_quote_builder/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`sms_twilio`](../sms_twilio/overview.md), [`snailmail`](../snailmail/overview.md), [`snailmail_account`](../snailmail_account/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`stock_sms`](../stock_sms/overview.md), [`test_testing_utilities`](../test_testing_utilities/overview.md), [`test_website`](../test_website/overview.md), [`web`](../web/overview.md), [`web_unsplash`](../web_unsplash/overview.md), [`website`](../website/overview.md), [`website_cf_turnstile`](../website_cf_turnstile/overview.md), [`website_event_jitsi`](../website_event_jitsi/overview.md), [`website_event_track`](../website_event_track/overview.md), [`website_livechat`](../website_livechat/overview.md), [`website_payment`](../website_payment/overview.md), [`website_payment_authorize`](../website_payment_authorize/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_autocomplete`](../website_sale_autocomplete/overview.md), [`website_sale_picking`](../website_sale_picking/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md), [`website_slides`](../website_slides/overview.md), [`website_twitter`](../website_twitter/overview.md)
- `res.country` — extended by [`base_address_extended`](../base_address_extended/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`website_payment`](../website_payment/overview.md), [`website_sale`](../website_sale/overview.md)
- `res.country.group` — extended by [`product`](../product/overview.md)
- `res.country.state` — extended by [`l10n_in`](../l10n_in/overview.md)
- `res.currency` — extended by [`account`](../account/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`product`](../product/overview.md), [`spreadsheet`](../spreadsheet/overview.md)
- `res.currency.rate` — extended by [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`spreadsheet`](../spreadsheet/overview.md)
- `res.groups` — extended by [`account`](../account/overview.md), [`mail`](../mail/overview.md), [`website_slides`](../website_slides/overview.md)
- `res.lang` — extended by [`spreadsheet`](../spreadsheet/overview.md), [`website`](../website/overview.md)
- `res.partner` — extended by [`account`](../account/overview.md), [`account_add_gln`](../account_add_gln/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_response`](../account_peppol_response/overview.md), [`auth_signup`](../auth_signup/overview.md), [`base_address_extended`](../base_address_extended/overview.md), [`base_geolocalize`](../base_geolocalize/overview.md), [`base_vat`](../base_vat/overview.md), [`bus`](../bus/overview.md), [`calendar`](../calendar/overview.md), [`crm`](../crm/overview.md), [`delivery`](../delivery/overview.md), [`delivery_mondialrelay`](../delivery_mondialrelay/overview.md), [`event`](../event/overview.md), [`fleet`](../fleet/overview.md), [`hr`](../hr/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`im_livechat`](../im_livechat/overview.md), [`l10n_anz_ubl_pint`](../l10n_anz_ubl_pint/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ar_pos`](../l10n_ar_pos/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_ca`](../l10n_ca/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_co`](../l10n_co/overview.md), [`l10n_dk`](../l10n_dk/overview.md), [`l10n_dk_oioubl`](../l10n_dk_oioubl/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_facturae_adm_centers`](../l10n_es_edi_facturae_adm_centers/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_fr`](../l10n_fr/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_hu`](../l10n_hu/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur`](../l10n_id_efaktur/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_jp_ubl_pint`](../l10n_jp_ubl_pint/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_latam_base`](../l10n_latam_base/overview.md), [`l10n_ma`](../l10n_ma/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_edi_extended`](../l10n_my_edi_extended/overview.md), [`l10n_my_ubl_pint`](../l10n_my_ubl_pint/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_pe_pos`](../l10n_pe_pos/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro`](../l10n_ro/overview.md), [`l10n_ro_edi`](../l10n_ro_edi/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md), [`l10n_th`](../l10n_th/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_tr_nilvera_edispatch`](../l10n_tr_nilvera_edispatch/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`loyalty`](../loyalty/overview.md), [`mail`](../mail/overview.md), [`mail_plugin`](../mail_plugin/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`membership`](../membership/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`payment`](../payment/overview.md), [`phone_validation`](../phone_validation/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`portal`](../portal/overview.md), [`privacy_lookup`](../privacy_lookup/overview.md), [`product`](../product/overview.md), [`project`](../project/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`sale`](../sale/overview.md), [`sales_team`](../sales_team/overview.md), [`sms`](../sms/overview.md), [`snailmail`](../snailmail/overview.md), [`stock`](../stock/overview.md), [`survey`](../survey/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`test_inherit`](../test_inherit/overview.md), [`web`](../web/overview.md), [`website`](../website/overview.md), [`website_crm_partner_assign`](../website_crm_partner_assign/overview.md), [`website_customer`](../website_customer/overview.md), [`website_partner`](../website_partner/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_mondialrelay`](../website_sale_mondialrelay/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md), [`website_slides`](../website_slides/overview.md)
- `res.partner.bank` — extended by [`account`](../account/overview.md), [`account_qr_code_emv`](../account_qr_code_emv/overview.md), [`account_qr_code_sepa`](../account_qr_code_sepa/overview.md), [`base_iban`](../base_iban/overview.md), [`hr`](../hr/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_au`](../l10n_au/overview.md), [`l10n_br_pix`](../l10n_br_pix/overview.md), [`l10n_ch`](../l10n_ch/overview.md), [`l10n_hk`](../l10n_hk/overview.md), [`l10n_mx`](../l10n_mx/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_th`](../l10n_th/overview.md), [`l10n_us`](../l10n_us/overview.md), [`l10n_vn`](../l10n_vn/overview.md)
- `res.partner.category` — extended by [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md)
- `res.partner.industry`
- `res.partner.title`
- `res.users` — extended by [`auth_ldap`](../auth_ldap/overview.md), [`auth_oauth`](../auth_oauth/overview.md), [`auth_password_policy`](../auth_password_policy/overview.md), [`auth_signup`](../auth_signup/overview.md), [`auth_totp`](../auth_totp/overview.md), [`auth_totp_mail`](../auth_totp_mail/overview.md), [`auth_totp_mail_enforce`](../auth_totp_mail_enforce/overview.md), [`auth_totp_portal`](../auth_totp_portal/overview.md), [`base_import`](../base_import/overview.md), [`base_setup`](../base_setup/overview.md), [`bus`](../bus/overview.md), [`calendar`](../calendar/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`digest`](../digest/overview.md), [`gamification`](../gamification/overview.md), [`google_calendar`](../google_calendar/overview.md), [`hr`](../hr/overview.md), [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_fleet`](../hr_fleet/overview.md), [`hr_gamification`](../hr_gamification/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_holidays_attendance`](../hr_holidays_attendance/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`hr_maintenance`](../hr_maintenance/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`hr_skills`](../hr_skills/overview.md), [`im_livechat`](../im_livechat/overview.md), [`im_livechat_mail_bot`](../im_livechat_mail_bot/overview.md), [`lunch`](../lunch/overview.md), [`mail`](../mail/overview.md), [`mail_bot`](../mail_bot/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`microsoft_account`](../microsoft_account/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md), [`phone_validation`](../phone_validation/overview.md), [`resource`](../resource/overview.md), [`sale_crm`](../sale_crm/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sales_team`](../sales_team/overview.md), [`stock`](../stock/overview.md), [`test_uninstall`](../test_uninstall/overview.md), [`web`](../web/overview.md), [`web_unsplash`](../web_unsplash/overview.md), [`website`](../website/overview.md), [`website_forum`](../website_forum/overview.md), [`website_profile`](../website_profile/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md), [`website_slides`](../website_slides/overview.md)
- `res.users.apikeys` — extended by [`auth_totp`](../auth_totp/overview.md)
- `res.users.apikeys.description` — extended by [`portal`](../portal/overview.md)
- `res.users.apikeys.show`
- `res.users.deletion`
- `res.users.identitycheck`
- `res.users.log` — extended by [`hr_presence`](../hr_presence/overview.md)
- `res.users.settings` — extended by [`im_livechat`](../im_livechat/overview.md), [`mail`](../mail/overview.md)
- `wizard.ir.model.menu.create`
- Extends `avatar.mixin` — framework/dynamic owner
- Extends `format.address.mixin` — framework/dynamic owner
- Extends `image.mixin` — framework/dynamic owner
- Extends `ir.actions.actions` — framework/dynamic owner
- Extends `ir.filters` — framework/dynamic owner
- Extends `ir.module.category` — framework/dynamic owner
- Extends `ir.qweb.field` — defined by [`web_editor`](../web_editor/overview.md)
- Extends `ir.qweb.field.image` — defined by [`web`](../web/overview.md), [`web_editor`](../web_editor/overview.md)
- Extends `ir.qweb.field.many2one` — defined by [`web_editor`](../web_editor/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config` — framework/dynamic owner
- Extends `res.currency.rate` — framework/dynamic owner
- Extends `res.groups` — framework/dynamic owner
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `res.partner.industry` — framework/dynamic owner
- Extends `res.users` — defined by [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from, model_extended_by
- [`module.account_add_gln`](../../../agents/modules/generated/account_add_gln.yaml) — model_extended_by
- [`module.account_audit_trail`](../../../agents/modules/generated/account_audit_trail.yaml) — model_extended_by
- [`module.account_check_printing`](../../../agents/modules/generated/account_check_printing.yaml) — model_extended_by
- [`module.account_edi`](../../../agents/modules/generated/account_edi.yaml) — model_extended_by
- [`module.account_edi_proxy_client`](../../../agents/modules/generated/account_edi_proxy_client.yaml) — model_extended_by
- [`module.account_edi_ubl_cii`](../../../agents/modules/generated/account_edi_ubl_cii.yaml) — model_extended_by
- [`module.account_lock`](../../../agents/modules/generated/account_lock.yaml) — model_extended_by
- [`module.account_payment`](../../../agents/modules/generated/account_payment.yaml) — model_extended_by
- [`module.account_peppol`](../../../agents/modules/generated/account_peppol.yaml) — model_extended_by
- [`module.account_peppol_response`](../../../agents/modules/generated/account_peppol_response.yaml) — model_extended_by
- [`module.account_qr_code_emv`](../../../agents/modules/generated/account_qr_code_emv.yaml) — model_extended_by
- [`module.account_qr_code_sepa`](../../../agents/modules/generated/account_qr_code_sepa.yaml) — model_extended_by
- [`module.analytic`](../../../agents/modules/generated/analytic.yaml) — model_extended_by, required_by
- [`module.attachment_indexation`](../../../agents/modules/generated/attachment_indexation.yaml) — model_extended_by
- [`module.auth_ldap`](../../../agents/modules/generated/auth_ldap.yaml) — model_extended_by, required_by
- [`module.auth_oauth`](../../../agents/modules/generated/auth_oauth.yaml) — model_extended_by, required_by
- [`module.auth_password_policy`](../../../agents/modules/generated/auth_password_policy.yaml) — model_extended_by
- [`module.auth_signup`](../../../agents/modules/generated/auth_signup.yaml) — model_extended_by
- [`module.auth_totp`](../../../agents/modules/generated/auth_totp.yaml) — model_extended_by
- [`module.auth_totp_mail`](../../../agents/modules/generated/auth_totp_mail.yaml) — model_extended_by
- [`module.auth_totp_mail_enforce`](../../../agents/modules/generated/auth_totp_mail_enforce.yaml) — model_extended_by
- [`module.auth_totp_portal`](../../../agents/modules/generated/auth_totp_portal.yaml) — model_extended_by
- [`module.barcodes`](../../../agents/modules/generated/barcodes.yaml) — model_extended_by
- [`module.barcodes_gs1_nomenclature`](../../../agents/modules/generated/barcodes_gs1_nomenclature.yaml) — model_extended_by
- [`module.base_address_extended`](../../../agents/modules/generated/base_address_extended.yaml) — model_extended_by, required_by
- [`module.base_automation`](../../../agents/modules/generated/base_automation.yaml) — required_by
- [`module.base_geolocalize`](../../../agents/modules/generated/base_geolocalize.yaml) — model_extended_by
- [`module.base_iban`](../../../agents/modules/generated/base_iban.yaml) — model_extended_by
- [`module.base_import`](../../../agents/modules/generated/base_import.yaml) — model_extended_by
- [`module.base_import_module`](../../../agents/modules/generated/base_import_module.yaml) — model_extended_by
- [`module.base_install_request`](../../../agents/modules/generated/base_install_request.yaml) — model_extended_by
- [`module.base_setup`](../../../agents/modules/generated/base_setup.yaml) — model_extended_by, required_by
- [`module.base_sparse_field`](../../../agents/modules/generated/base_sparse_field.yaml) — model_extended_by, required_by
- [`module.base_vat`](../../../agents/modules/generated/base_vat.yaml) — model_extended_by
- [`module.bus`](../../../agents/modules/generated/bus.yaml) — model_extended_by, required_by
- [`module.calendar`](../../../agents/modules/generated/calendar.yaml) — model_extended_by, required_by
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from, model_extended_by, required_by
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from, model_extended_by
- [`module.crm_iap_enrich`](../../../agents/modules/generated/crm_iap_enrich.yaml) — model_extended_by
- [`module.delivery`](../../../agents/modules/generated/delivery.yaml) — model_extended_by
- [`module.delivery_mondialrelay`](../../../agents/modules/generated/delivery_mondialrelay.yaml) — model_extended_by
- [`module.digest`](../../../agents/modules/generated/digest.yaml) — model_extended_by
- [`module.event`](../../../agents/modules/generated/event.yaml) — model_extended_by
- [`module.event_booth`](../../../agents/modules/generated/event_booth.yaml) — model_extended_by
- [`module.fleet`](../../../agents/modules/generated/fleet.yaml) — model_extended_by, required_by
- [`module.gamification`](../../../agents/modules/generated/gamification.yaml) — model_extended_by
- [`module.google_calendar`](../../../agents/modules/generated/google_calendar.yaml) — model_extended_by
- [`module.google_gmail`](../../../agents/modules/generated/google_gmail.yaml) — model_extended_by
- [`module.google_recaptcha`](../../../agents/modules/generated/google_recaptcha.yaml) — model_extended_by
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — model_extended_by
- [`module.hr_attendance`](../../../agents/modules/generated/hr_attendance.yaml) — model_extended_by
- [`module.hr_contract`](../../../agents/modules/generated/hr_contract.yaml) — model_extended_by
- [`module.hr_expense`](../../../agents/modules/generated/hr_expense.yaml) — model_extended_by
- [`module.hr_fleet`](../../../agents/modules/generated/hr_fleet.yaml) — model_extended_by
- [`module.hr_gamification`](../../../agents/modules/generated/hr_gamification.yaml) — model_extended_by
- [`module.hr_holidays`](../../../agents/modules/generated/hr_holidays.yaml) — model_extended_by
- [`module.hr_holidays_attendance`](../../../agents/modules/generated/hr_holidays_attendance.yaml) — model_extended_by
- [`module.hr_homeworking`](../../../agents/modules/generated/hr_homeworking.yaml) — model_extended_by
- [`module.hr_maintenance`](../../../agents/modules/generated/hr_maintenance.yaml) — model_extended_by
- [`module.hr_presence`](../../../agents/modules/generated/hr_presence.yaml) — model_extended_by
- [`module.hr_recruitment`](../../../agents/modules/generated/hr_recruitment.yaml) — model_extended_by
- [`module.hr_skills`](../../../agents/modules/generated/hr_skills.yaml) — model_extended_by
- [`module.hr_timesheet`](../../../agents/modules/generated/hr_timesheet.yaml) — model_extended_by
- [`module.hr_timesheet_attendance`](../../../agents/modules/generated/hr_timesheet_attendance.yaml) — model_extended_by
- [`module.http_routing`](../../../agents/modules/generated/http_routing.yaml) — model_extended_by
- [`module.im_livechat`](../../../agents/modules/generated/im_livechat.yaml) — model_extended_by
- [`module.im_livechat_mail_bot`](../../../agents/modules/generated/im_livechat_mail_bot.yaml) — model_extended_by
- [`module.l10n_ae`](../../../agents/modules/generated/l10n_ae.yaml) — required_by
- [`module.l10n_anz_ubl_pint`](../../../agents/modules/generated/l10n_anz_ubl_pint.yaml) — model_extended_by
- [`module.l10n_ar`](../../../agents/modules/generated/l10n_ar.yaml) — model_extended_by
- [`module.l10n_ar_pos`](../../../agents/modules/generated/l10n_ar_pos.yaml) — model_extended_by
- [`module.l10n_ar_withholding`](../../../agents/modules/generated/l10n_ar_withholding.yaml) — model_extended_by
- [`module.l10n_au`](../../../agents/modules/generated/l10n_au.yaml) — model_extended_by
- [`module.l10n_be`](../../../agents/modules/generated/l10n_be.yaml) — model_extended_by
- [`module.l10n_br`](../../../agents/modules/generated/l10n_br.yaml) — model_extended_by
- [`module.l10n_br_pix`](../../../agents/modules/generated/l10n_br_pix.yaml) — model_extended_by
- [`module.l10n_ca`](../../../agents/modules/generated/l10n_ca.yaml) — model_extended_by
- [`module.l10n_ch`](../../../agents/modules/generated/l10n_ch.yaml) — model_extended_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from, model_extended_by
- [`module.l10n_cn`](../../../agents/modules/generated/l10n_cn.yaml) — required_by
- [`module.l10n_co`](../../../agents/modules/generated/l10n_co.yaml) — model_extended_by
- [`module.l10n_cz`](../../../agents/modules/generated/l10n_cz.yaml) — model_extended_by
- [`module.l10n_de`](../../../agents/modules/generated/l10n_de.yaml) — model_extended_by
- [`module.l10n_dk`](../../../agents/modules/generated/l10n_dk.yaml) — model_extended_by
- [`module.l10n_dk_oioubl`](../../../agents/modules/generated/l10n_dk_oioubl.yaml) — model_extended_by
- [`module.l10n_ec`](../../../agents/modules/generated/l10n_ec.yaml) — model_extended_by, required_by
- [`module.l10n_eg_edi_eta`](../../../agents/modules/generated/l10n_eg_edi_eta.yaml) — model_extended_by
- [`module.l10n_es`](../../../agents/modules/generated/l10n_es.yaml) — model_extended_by
- [`module.l10n_es_edi_facturae`](../../../agents/modules/generated/l10n_es_edi_facturae.yaml) — model_extended_by
- [`module.l10n_es_edi_facturae_adm_centers`](../../../agents/modules/generated/l10n_es_edi_facturae_adm_centers.yaml) — model_extended_by
- [`module.l10n_es_edi_sii`](../../../agents/modules/generated/l10n_es_edi_sii.yaml) — model_extended_by
- [`module.l10n_es_edi_tbai`](../../../agents/modules/generated/l10n_es_edi_tbai.yaml) — model_extended_by
- [`module.l10n_es_edi_verifactu`](../../../agents/modules/generated/l10n_es_edi_verifactu.yaml) — model_extended_by
- [`module.l10n_es_edi_verifactu_pos`](../../../agents/modules/generated/l10n_es_edi_verifactu_pos.yaml) — model_extended_by
- [`module.l10n_es_pos`](../../../agents/modules/generated/l10n_es_pos.yaml) — model_extended_by
- [`module.l10n_es_pos_tbai`](../../../agents/modules/generated/l10n_es_pos_tbai.yaml) — model_extended_by
- [`module.l10n_eu_oss`](../../../agents/modules/generated/l10n_eu_oss.yaml) — model_extended_by
- [`module.l10n_fr`](../../../agents/modules/generated/l10n_fr.yaml) — model_extended_by
- [`module.l10n_fr_hr_holidays`](../../../agents/modules/generated/l10n_fr_hr_holidays.yaml) — model_extended_by
- [`module.l10n_fr_pdp`](../../../agents/modules/generated/l10n_fr_pdp.yaml) — model_extended_by
- [`module.l10n_fr_pdp_pos`](../../../agents/modules/generated/l10n_fr_pdp_pos.yaml) — model_extended_by
- [`module.l10n_fr_pos_cert`](../../../agents/modules/generated/l10n_fr_pos_cert.yaml) — model_extended_by
- [`module.l10n_gt`](../../../agents/modules/generated/l10n_gt.yaml) — required_by
- [`module.l10n_hk`](../../../agents/modules/generated/l10n_hk.yaml) — model_extended_by
- [`module.l10n_hn`](../../../agents/modules/generated/l10n_hn.yaml) — required_by
- [`module.l10n_hu`](../../../agents/modules/generated/l10n_hu.yaml) — model_extended_by
- [`module.l10n_hu_edi`](../../../agents/modules/generated/l10n_hu_edi.yaml) — model_extended_by
- [`module.l10n_id_efaktur`](../../../agents/modules/generated/l10n_id_efaktur.yaml) — model_extended_by
- [`module.l10n_id_efaktur_coretax`](../../../agents/modules/generated/l10n_id_efaktur_coretax.yaml) — model_extended_by
- [`module.l10n_in`](../../../agents/modules/generated/l10n_in.yaml) — model_extended_by
- [`module.l10n_in_edi`](../../../agents/modules/generated/l10n_in_edi.yaml) — model_extended_by
- [`module.l10n_in_edi_ewaybill`](../../../agents/modules/generated/l10n_in_edi_ewaybill.yaml) — model_extended_by
- [`module.l10n_in_withholding`](../../../agents/modules/generated/l10n_in_withholding.yaml) — model_extended_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from, model_extended_by
- [`module.l10n_it_edi_doi`](../../../agents/modules/generated/l10n_it_edi_doi.yaml) — model_extended_by
- [`module.l10n_jo_edi`](../../../agents/modules/generated/l10n_jo_edi.yaml) — model_extended_by
- [`module.l10n_jo_edi_extended`](../../../agents/modules/generated/l10n_jo_edi_extended.yaml) — model_extended_by
- [`module.l10n_jp_ubl_pint`](../../../agents/modules/generated/l10n_jp_ubl_pint.yaml) — model_extended_by
- [`module.l10n_ke`](../../../agents/modules/generated/l10n_ke.yaml) — model_extended_by
- [`module.l10n_ke_edi_tremol`](../../../agents/modules/generated/l10n_ke_edi_tremol.yaml) — model_extended_by
- [`module.l10n_latam_base`](../../../agents/modules/generated/l10n_latam_base.yaml) — model_extended_by
- [`module.l10n_latam_invoice_document`](../../../agents/modules/generated/l10n_latam_invoice_document.yaml) — model_extended_by
- [`module.l10n_ma`](../../../agents/modules/generated/l10n_ma.yaml) — model_extended_by, required_by
- [`module.l10n_mx`](../../../agents/modules/generated/l10n_mx.yaml) — model_extended_by
- [`module.l10n_my_edi`](../../../agents/modules/generated/l10n_my_edi.yaml) — model_extended_by
- [`module.l10n_my_edi_extended`](../../../agents/modules/generated/l10n_my_edi_extended.yaml) — model_extended_by
- [`module.l10n_my_ubl_pint`](../../../agents/modules/generated/l10n_my_ubl_pint.yaml) — model_extended_by
- [`module.l10n_mz`](../../../agents/modules/generated/l10n_mz.yaml) — required_by
- [`module.l10n_no`](../../../agents/modules/generated/l10n_no.yaml) — model_extended_by
- [`module.l10n_pe`](../../../agents/modules/generated/l10n_pe.yaml) — model_extended_by
- [`module.l10n_pe_pos`](../../../agents/modules/generated/l10n_pe_pos.yaml) — model_extended_by
- [`module.l10n_ph`](../../../agents/modules/generated/l10n_ph.yaml) — model_extended_by
- [`module.l10n_pl`](../../../agents/modules/generated/l10n_pl.yaml) — model_extended_by
- [`module.l10n_pt`](../../../agents/modules/generated/l10n_pt.yaml) — required_by
- [`module.l10n_ro`](../../../agents/modules/generated/l10n_ro.yaml) — model_extended_by
- [`module.l10n_ro_edi`](../../../agents/modules/generated/l10n_ro_edi.yaml) — model_extended_by
- [`module.l10n_ro_efactura`](../../../agents/modules/generated/l10n_ro_efactura.yaml) — model_extended_by
- [`module.l10n_ro_efactura_synchronize`](../../../agents/modules/generated/l10n_ro_efactura_synchronize.yaml) — model_extended_by
- [`module.l10n_rs_edi`](../../../agents/modules/generated/l10n_rs_edi.yaml) — model_extended_by
- [`module.l10n_sa_edi`](../../../agents/modules/generated/l10n_sa_edi.yaml) — model_extended_by
- [`module.l10n_se`](../../../agents/modules/generated/l10n_se.yaml) — model_extended_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from, model_extended_by
- [`module.l10n_sg_ubl_pint`](../../../agents/modules/generated/l10n_sg_ubl_pint.yaml) — model_extended_by
- [`module.l10n_sk`](../../../agents/modules/generated/l10n_sk.yaml) — model_extended_by
- [`module.l10n_th`](../../../agents/modules/generated/l10n_th.yaml) — model_extended_by
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from, model_extended_by
- [`module.l10n_tr_nilvera_edispatch`](../../../agents/modules/generated/l10n_tr_nilvera_edispatch.yaml) — model_extended_by
- [`module.l10n_tr_nilvera_einvoice`](../../../agents/modules/generated/l10n_tr_nilvera_einvoice.yaml) — model_extended_by
- [`module.l10n_us`](../../../agents/modules/generated/l10n_us.yaml) — model_extended_by
- [`module.l10n_uy`](../../../agents/modules/generated/l10n_uy.yaml) — model_extended_by
- [`module.l10n_vn`](../../../agents/modules/generated/l10n_vn.yaml) — model_extended_by
- [`module.l10n_vn_edi_viettel`](../../../agents/modules/generated/l10n_vn_edi_viettel.yaml) — model_extended_by
- [`module.loyalty`](../../../agents/modules/generated/loyalty.yaml) — model_extended_by
- [`module.lunch`](../../../agents/modules/generated/lunch.yaml) — model_extended_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from, model_extended_by, required_by
- [`module.mail_bot`](../../../agents/modules/generated/mail_bot.yaml) — model_extended_by
- [`module.mail_plugin`](../../../agents/modules/generated/mail_plugin.yaml) — model_extended_by
- [`module.maintenance`](../../../agents/modules/generated/maintenance.yaml) — model_extended_by
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from, model_extended_by
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from, model_extended_by
- [`module.membership`](../../../agents/modules/generated/membership.yaml) — model_extended_by
- [`module.microsoft_account`](../../../agents/modules/generated/microsoft_account.yaml) — model_extended_by
- [`module.microsoft_calendar`](../../../agents/modules/generated/microsoft_calendar.yaml) — model_extended_by
- [`module.microsoft_outlook`](../../../agents/modules/generated/microsoft_outlook.yaml) — model_extended_by
- [`module.mrp`](../../../agents/modules/generated/mrp.yaml) — model_extended_by
- [`module.mrp_subcontracting`](../../../agents/modules/generated/mrp_subcontracting.yaml) — model_extended_by
- [`module.mrp_subcontracting_dropshipping`](../../../agents/modules/generated/mrp_subcontracting_dropshipping.yaml) — model_extended_by
- [`module.onboarding`](../../../agents/modules/generated/onboarding.yaml) — model_extended_by
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from, model_extended_by
- [`module.payment`](../../../agents/modules/generated/payment.yaml) — model_extended_by
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from, model_extended_by, required_by
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — model_extended_by
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — model_extended_by
- [`module.portal_rating`](../../../agents/modules/generated/portal_rating.yaml) — model_extended_by
- [`module.pos_adyen`](../../../agents/modules/generated/pos_adyen.yaml) — model_extended_by
- [`module.pos_discount`](../../../agents/modules/generated/pos_discount.yaml) — model_extended_by
- [`module.pos_epson_printer`](../../../agents/modules/generated/pos_epson_printer.yaml) — model_extended_by
- [`module.pos_hr`](../../../agents/modules/generated/pos_hr.yaml) — model_extended_by
- [`module.pos_loyalty`](../../../agents/modules/generated/pos_loyalty.yaml) — model_extended_by
- [`module.pos_online_payment_self_order`](../../../agents/modules/generated/pos_online_payment_self_order.yaml) — model_extended_by
- [`module.pos_restaurant`](../../../agents/modules/generated/pos_restaurant.yaml) — model_extended_by
- [`module.pos_sale`](../../../agents/modules/generated/pos_sale.yaml) — model_extended_by
- [`module.pos_self_order`](../../../agents/modules/generated/pos_self_order.yaml) — model_extended_by
- [`module.pos_self_order_sale`](../../../agents/modules/generated/pos_self_order_sale.yaml) — model_extended_by
- [`module.privacy_lookup`](../../../agents/modules/generated/privacy_lookup.yaml) — model_extended_by
- [`module.product`](../../../agents/modules/generated/product.yaml) — model_extended_by, required_by
- [`module.product_expiry`](../../../agents/modules/generated/product_expiry.yaml) — model_extended_by
- [`module.product_images`](../../../agents/modules/generated/product_images.yaml) — model_extended_by
- [`module.project`](../../../agents/modules/generated/project.yaml) — model_extended_by
- [`module.project_timesheet_holidays`](../../../agents/modules/generated/project_timesheet_holidays.yaml) — model_extended_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from, model_extended_by
- [`module.purchase_stock`](../../../agents/modules/generated/purchase_stock.yaml) — model_extended_by
- [`module.resource`](../../../agents/modules/generated/resource.yaml) — model_extended_by, required_by
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — model_extended_by
- [`module.sale_crm`](../../../agents/modules/generated/sale_crm.yaml) — model_extended_by
- [`module.sale_management`](../../../agents/modules/generated/sale_management.yaml) — model_extended_by
- [`module.sale_pdf_quote_builder`](../../../agents/modules/generated/sale_pdf_quote_builder.yaml) — model_extended_by
- [`module.sale_project`](../../../agents/modules/generated/sale_project.yaml) — model_extended_by
- [`module.sale_stock`](../../../agents/modules/generated/sale_stock.yaml) — model_extended_by
- [`module.sale_timesheet`](../../../agents/modules/generated/sale_timesheet.yaml) — model_extended_by
- [`module.sales_team`](../../../agents/modules/generated/sales_team.yaml) — model_extended_by, required_by
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from, model_extended_by, required_by
- [`module.sms_twilio`](../../../agents/modules/generated/sms_twilio.yaml) — model_extended_by
- [`module.snailmail`](../../../agents/modules/generated/snailmail.yaml) — model_extended_by
- [`module.snailmail_account`](../../../agents/modules/generated/snailmail_account.yaml) — model_extended_by
- [`module.social_media`](../../../agents/modules/generated/social_media.yaml) — model_extended_by, required_by
- [`module.spreadsheet`](../../../agents/modules/generated/spreadsheet.yaml) — model_extended_by
- [`module.spreadsheet_account`](../../../agents/modules/generated/spreadsheet_account.yaml) — model_extended_by
- [`module.stock`](../../../agents/modules/generated/stock.yaml) — model_extended_by
- [`module.stock_account`](../../../agents/modules/generated/stock_account.yaml) — model_extended_by
- [`module.stock_dropshipping`](../../../agents/modules/generated/stock_dropshipping.yaml) — model_extended_by
- [`module.stock_landed_costs`](../../../agents/modules/generated/stock_landed_costs.yaml) — model_extended_by
- [`module.stock_sms`](../../../agents/modules/generated/stock_sms.yaml) — model_extended_by
- [`module.survey`](../../../agents/modules/generated/survey.yaml) — model_extended_by
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from, model_extended_by
- [`module.test_assetsbundle`](../../../agents/modules/generated/test_assetsbundle.yaml) — model_extended_by, required_by
- [`module.test_auth_custom`](../../../agents/modules/generated/test_auth_custom.yaml) — model_extended_by
- [`module.test_converter`](../../../agents/modules/generated/test_converter.yaml) — required_by
- [`module.test_exceptions`](../../../agents/modules/generated/test_exceptions.yaml) — required_by
- [`module.test_http`](../../../agents/modules/generated/test_http.yaml) — required_by
- [`module.test_impex`](../../../agents/modules/generated/test_impex.yaml) — required_by
- [`module.test_inherit`](../../../agents/modules/generated/test_inherit.yaml) — model_extended_by, required_by
- [`module.test_inherits`](../../../agents/modules/generated/test_inherits.yaml) — required_by
- [`module.test_limits`](../../../agents/modules/generated/test_limits.yaml) — required_by
- [`module.test_lint`](../../../agents/modules/generated/test_lint.yaml) — required_by
- [`module.test_mass_mailing`](../../../agents/modules/generated/test_mass_mailing.yaml) — model_extended_by
- [`module.test_new_api`](../../../agents/modules/generated/test_new_api.yaml) — required_by
- [`module.test_performance`](../../../agents/modules/generated/test_performance.yaml) — required_by
- [`module.test_populate`](../../../agents/modules/generated/test_populate.yaml) — required_by
- [`module.test_read_group`](../../../agents/modules/generated/test_read_group.yaml) — required_by
- [`module.test_rpc`](../../../agents/modules/generated/test_rpc.yaml) — required_by
- [`module.test_testing_utilities`](../../../agents/modules/generated/test_testing_utilities.yaml) — model_extended_by, required_by
- [`module.test_translation_import`](../../../agents/modules/generated/test_translation_import.yaml) — required_by
- [`module.test_uninstall`](../../../agents/modules/generated/test_uninstall.yaml) — model_extended_by, required_by
- [`module.test_website`](../../../agents/modules/generated/test_website.yaml) — model_extended_by
- [`module.transifex`](../../../agents/modules/generated/transifex.yaml) — model_extended_by, required_by
- [`module.uom`](../../../agents/modules/generated/uom.yaml) — required_by
- [`module.utm`](../../../agents/modules/generated/utm.yaml) — model_extended_by, required_by
- [`module.web`](../../../agents/modules/generated/web.yaml) — extends_model_from, model_extended_by, required_by
- [`module.web_editor`](../../../agents/modules/generated/web_editor.yaml) — extends_model_from, model_extended_by
- [`module.web_hierarchy`](../../../agents/modules/generated/web_hierarchy.yaml) — model_extended_by
- [`module.web_tour`](../../../agents/modules/generated/web_tour.yaml) — model_extended_by
- [`module.web_unsplash`](../../../agents/modules/generated/web_unsplash.yaml) — model_extended_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from, model_extended_by
- [`module.website_blog`](../../../agents/modules/generated/website_blog.yaml) — model_extended_by
- [`module.website_cf_turnstile`](../../../agents/modules/generated/website_cf_turnstile.yaml) — model_extended_by
- [`module.website_crm_iap_reveal`](../../../agents/modules/generated/website_crm_iap_reveal.yaml) — model_extended_by
- [`module.website_crm_partner_assign`](../../../agents/modules/generated/website_crm_partner_assign.yaml) — model_extended_by
- [`module.website_customer`](../../../agents/modules/generated/website_customer.yaml) — model_extended_by
- [`module.website_event_jitsi`](../../../agents/modules/generated/website_event_jitsi.yaml) — model_extended_by
- [`module.website_event_track`](../../../agents/modules/generated/website_event_track.yaml) — model_extended_by
- [`module.website_forum`](../../../agents/modules/generated/website_forum.yaml) — model_extended_by
- [`module.website_livechat`](../../../agents/modules/generated/website_livechat.yaml) — model_extended_by
- [`module.website_mass_mailing`](../../../agents/modules/generated/website_mass_mailing.yaml) — model_extended_by
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from, model_extended_by
- [`module.website_payment`](../../../agents/modules/generated/website_payment.yaml) — model_extended_by
- [`module.website_payment_authorize`](../../../agents/modules/generated/website_payment_authorize.yaml) — model_extended_by
- [`module.website_profile`](../../../agents/modules/generated/website_profile.yaml) — model_extended_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — model_extended_by
- [`module.website_sale_autocomplete`](../../../agents/modules/generated/website_sale_autocomplete.yaml) — model_extended_by
- [`module.website_sale_mondialrelay`](../../../agents/modules/generated/website_sale_mondialrelay.yaml) — model_extended_by
- [`module.website_sale_picking`](../../../agents/modules/generated/website_sale_picking.yaml) — model_extended_by
- [`module.website_sale_stock`](../../../agents/modules/generated/website_sale_stock.yaml) — model_extended_by
- [`module.website_sale_wishlist`](../../../agents/modules/generated/website_sale_wishlist.yaml) — model_extended_by
- [`module.website_slides`](../../../agents/modules/generated/website_slides.yaml) — model_extended_by
- [`module.website_twitter`](../../../agents/modules/generated/website_twitter.yaml) — model_extended_by

## Regression impact checklist

- Review 47 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account`](../account/overview.md), [`account_add_gln`](../account_add_gln/overview.md), [`account_audit_trail`](../account_audit_trail/overview.md), [`account_check_printing`](../account_check_printing/overview.md), [`account_edi`](../account_edi/overview.md), [`account_edi_proxy_client`](../account_edi_proxy_client/overview.md), [`account_edi_ubl_cii`](../account_edi_ubl_cii/overview.md), [`account_lock`](../account_lock/overview.md), [`account_payment`](../account_payment/overview.md), [`account_peppol`](../account_peppol/overview.md), [`account_peppol_response`](../account_peppol_response/overview.md), [`account_qr_code_emv`](../account_qr_code_emv/overview.md), [`account_qr_code_sepa`](../account_qr_code_sepa/overview.md), [`analytic`](../analytic/overview.md), [`attachment_indexation`](../attachment_indexation/overview.md), [`auth_ldap`](../auth_ldap/overview.md), [`auth_oauth`](../auth_oauth/overview.md), [`auth_password_policy`](../auth_password_policy/overview.md), [`auth_signup`](../auth_signup/overview.md), [`auth_totp`](../auth_totp/overview.md), [`auth_totp_mail`](../auth_totp_mail/overview.md), [`auth_totp_mail_enforce`](../auth_totp_mail_enforce/overview.md), [`auth_totp_portal`](../auth_totp_portal/overview.md), [`barcodes`](../barcodes/overview.md), [`barcodes_gs1_nomenclature`](../barcodes_gs1_nomenclature/overview.md), [`base_address_extended`](../base_address_extended/overview.md), [`base_geolocalize`](../base_geolocalize/overview.md), [`base_iban`](../base_iban/overview.md), [`base_import`](../base_import/overview.md), [`base_import_module`](../base_import_module/overview.md), [`base_install_request`](../base_install_request/overview.md), [`base_setup`](../base_setup/overview.md), [`base_sparse_field`](../base_sparse_field/overview.md), [`base_vat`](../base_vat/overview.md), [`bus`](../bus/overview.md), [`calendar`](../calendar/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`crm_iap_enrich`](../crm_iap_enrich/overview.md), [`delivery`](../delivery/overview.md), [`delivery_mondialrelay`](../delivery_mondialrelay/overview.md), [`digest`](../digest/overview.md), [`event`](../event/overview.md), [`event_booth`](../event_booth/overview.md), [`fleet`](../fleet/overview.md), [`gamification`](../gamification/overview.md), [`google_calendar`](../google_calendar/overview.md), [`google_gmail`](../google_gmail/overview.md), [`google_recaptcha`](../google_recaptcha/overview.md), [`hr`](../hr/overview.md), [`hr_attendance`](../hr_attendance/overview.md), [`hr_contract`](../hr_contract/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_fleet`](../hr_fleet/overview.md), [`hr_gamification`](../hr_gamification/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_holidays_attendance`](../hr_holidays_attendance/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`hr_maintenance`](../hr_maintenance/overview.md), [`hr_presence`](../hr_presence/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`hr_skills`](../hr_skills/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`hr_timesheet_attendance`](../hr_timesheet_attendance/overview.md), [`http_routing`](../http_routing/overview.md), [`im_livechat`](../im_livechat/overview.md), [`im_livechat_mail_bot`](../im_livechat_mail_bot/overview.md), [`l10n_anz_ubl_pint`](../l10n_anz_ubl_pint/overview.md), [`l10n_ar`](../l10n_ar/overview.md), [`l10n_ar_pos`](../l10n_ar_pos/overview.md), [`l10n_ar_withholding`](../l10n_ar_withholding/overview.md), [`l10n_au`](../l10n_au/overview.md), [`l10n_be`](../l10n_be/overview.md), [`l10n_br`](../l10n_br/overview.md), [`l10n_br_pix`](../l10n_br_pix/overview.md), [`l10n_ca`](../l10n_ca/overview.md), [`l10n_ch`](../l10n_ch/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_co`](../l10n_co/overview.md), [`l10n_cz`](../l10n_cz/overview.md), [`l10n_de`](../l10n_de/overview.md), [`l10n_dk`](../l10n_dk/overview.md), [`l10n_dk_oioubl`](../l10n_dk_oioubl/overview.md), [`l10n_ec`](../l10n_ec/overview.md), [`l10n_eg_edi_eta`](../l10n_eg_edi_eta/overview.md), [`l10n_es`](../l10n_es/overview.md), [`l10n_es_edi_facturae`](../l10n_es_edi_facturae/overview.md), [`l10n_es_edi_facturae_adm_centers`](../l10n_es_edi_facturae_adm_centers/overview.md), [`l10n_es_edi_sii`](../l10n_es_edi_sii/overview.md), [`l10n_es_edi_tbai`](../l10n_es_edi_tbai/overview.md), [`l10n_es_edi_verifactu`](../l10n_es_edi_verifactu/overview.md), [`l10n_es_edi_verifactu_pos`](../l10n_es_edi_verifactu_pos/overview.md), [`l10n_es_pos`](../l10n_es_pos/overview.md), [`l10n_es_pos_tbai`](../l10n_es_pos_tbai/overview.md), [`l10n_eu_oss`](../l10n_eu_oss/overview.md), [`l10n_fr`](../l10n_fr/overview.md), [`l10n_fr_hr_holidays`](../l10n_fr_hr_holidays/overview.md), [`l10n_fr_pdp`](../l10n_fr_pdp/overview.md), [`l10n_fr_pdp_pos`](../l10n_fr_pdp_pos/overview.md), [`l10n_fr_pos_cert`](../l10n_fr_pos_cert/overview.md), [`l10n_hk`](../l10n_hk/overview.md), [`l10n_hu`](../l10n_hu/overview.md), [`l10n_hu_edi`](../l10n_hu_edi/overview.md), [`l10n_id_efaktur`](../l10n_id_efaktur/overview.md), [`l10n_id_efaktur_coretax`](../l10n_id_efaktur_coretax/overview.md), [`l10n_in`](../l10n_in/overview.md), [`l10n_in_edi`](../l10n_in_edi/overview.md), [`l10n_in_edi_ewaybill`](../l10n_in_edi_ewaybill/overview.md), [`l10n_in_withholding`](../l10n_in_withholding/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_it_edi_doi`](../l10n_it_edi_doi/overview.md), [`l10n_jo_edi`](../l10n_jo_edi/overview.md), [`l10n_jo_edi_extended`](../l10n_jo_edi_extended/overview.md), [`l10n_jp_ubl_pint`](../l10n_jp_ubl_pint/overview.md), [`l10n_ke`](../l10n_ke/overview.md), [`l10n_ke_edi_tremol`](../l10n_ke_edi_tremol/overview.md), [`l10n_latam_base`](../l10n_latam_base/overview.md), [`l10n_latam_invoice_document`](../l10n_latam_invoice_document/overview.md), [`l10n_ma`](../l10n_ma/overview.md), [`l10n_mx`](../l10n_mx/overview.md), [`l10n_my_edi`](../l10n_my_edi/overview.md), [`l10n_my_edi_extended`](../l10n_my_edi_extended/overview.md), [`l10n_my_ubl_pint`](../l10n_my_ubl_pint/overview.md), [`l10n_no`](../l10n_no/overview.md), [`l10n_pe`](../l10n_pe/overview.md), [`l10n_pe_pos`](../l10n_pe_pos/overview.md), [`l10n_ph`](../l10n_ph/overview.md), [`l10n_pl`](../l10n_pl/overview.md), [`l10n_ro`](../l10n_ro/overview.md), [`l10n_ro_edi`](../l10n_ro_edi/overview.md), [`l10n_ro_efactura`](../l10n_ro_efactura/overview.md), [`l10n_ro_efactura_synchronize`](../l10n_ro_efactura_synchronize/overview.md), [`l10n_rs_edi`](../l10n_rs_edi/overview.md), [`l10n_sa_edi`](../l10n_sa_edi/overview.md), [`l10n_se`](../l10n_se/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_sg_ubl_pint`](../l10n_sg_ubl_pint/overview.md), [`l10n_sk`](../l10n_sk/overview.md), [`l10n_th`](../l10n_th/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`l10n_tr_nilvera_edispatch`](../l10n_tr_nilvera_edispatch/overview.md), [`l10n_tr_nilvera_einvoice`](../l10n_tr_nilvera_einvoice/overview.md), [`l10n_us`](../l10n_us/overview.md), [`l10n_uy`](../l10n_uy/overview.md), [`l10n_vn`](../l10n_vn/overview.md), [`l10n_vn_edi_viettel`](../l10n_vn_edi_viettel/overview.md), [`loyalty`](../loyalty/overview.md), [`lunch`](../lunch/overview.md), [`mail`](../mail/overview.md), [`mail_bot`](../mail_bot/overview.md), [`mail_plugin`](../mail_plugin/overview.md), [`maintenance`](../maintenance/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`membership`](../membership/overview.md), [`microsoft_account`](../microsoft_account/overview.md), [`microsoft_calendar`](../microsoft_calendar/overview.md), [`microsoft_outlook`](../microsoft_outlook/overview.md), [`mrp`](../mrp/overview.md), [`mrp_subcontracting`](../mrp_subcontracting/overview.md), [`mrp_subcontracting_dropshipping`](../mrp_subcontracting_dropshipping/overview.md), [`onboarding`](../onboarding/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`payment`](../payment/overview.md), [`phone_validation`](../phone_validation/overview.md), [`point_of_sale`](../point_of_sale/overview.md), [`portal`](../portal/overview.md), [`portal_rating`](../portal_rating/overview.md), [`pos_adyen`](../pos_adyen/overview.md), [`pos_discount`](../pos_discount/overview.md), [`pos_epson_printer`](../pos_epson_printer/overview.md), [`pos_hr`](../pos_hr/overview.md), [`pos_loyalty`](../pos_loyalty/overview.md), [`pos_online_payment_self_order`](../pos_online_payment_self_order/overview.md), [`pos_restaurant`](../pos_restaurant/overview.md), [`pos_sale`](../pos_sale/overview.md), [`pos_self_order`](../pos_self_order/overview.md), [`pos_self_order_sale`](../pos_self_order_sale/overview.md), [`privacy_lookup`](../privacy_lookup/overview.md), [`product`](../product/overview.md), [`product_expiry`](../product_expiry/overview.md), [`product_images`](../product_images/overview.md), [`project`](../project/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md), [`purchase`](../purchase/overview.md), [`purchase_stock`](../purchase_stock/overview.md), [`resource`](../resource/overview.md), [`sale`](../sale/overview.md), [`sale_crm`](../sale_crm/overview.md), [`sale_management`](../sale_management/overview.md), [`sale_pdf_quote_builder`](../sale_pdf_quote_builder/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_stock`](../sale_stock/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md), [`sales_team`](../sales_team/overview.md), [`sms`](../sms/overview.md), [`sms_twilio`](../sms_twilio/overview.md), [`snailmail`](../snailmail/overview.md), [`snailmail_account`](../snailmail_account/overview.md), [`social_media`](../social_media/overview.md), [`spreadsheet`](../spreadsheet/overview.md), [`spreadsheet_account`](../spreadsheet_account/overview.md), [`stock`](../stock/overview.md), [`stock_account`](../stock_account/overview.md), [`stock_dropshipping`](../stock_dropshipping/overview.md), [`stock_landed_costs`](../stock_landed_costs/overview.md), [`stock_sms`](../stock_sms/overview.md), [`survey`](../survey/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`test_assetsbundle`](../test_assetsbundle/overview.md), [`test_auth_custom`](../test_auth_custom/overview.md), [`test_inherit`](../test_inherit/overview.md), [`test_mass_mailing`](../test_mass_mailing/overview.md), [`test_testing_utilities`](../test_testing_utilities/overview.md), [`test_uninstall`](../test_uninstall/overview.md), [`test_website`](../test_website/overview.md), [`transifex`](../transifex/overview.md), [`utm`](../utm/overview.md), [`web`](../web/overview.md), [`web_editor`](../web_editor/overview.md), [`web_hierarchy`](../web_hierarchy/overview.md), [`web_tour`](../web_tour/overview.md), [`web_unsplash`](../web_unsplash/overview.md), [`website`](../website/overview.md), [`website_blog`](../website_blog/overview.md), [`website_cf_turnstile`](../website_cf_turnstile/overview.md), [`website_crm_iap_reveal`](../website_crm_iap_reveal/overview.md), [`website_crm_partner_assign`](../website_crm_partner_assign/overview.md), [`website_customer`](../website_customer/overview.md), [`website_event_jitsi`](../website_event_jitsi/overview.md), [`website_event_track`](../website_event_track/overview.md), [`website_forum`](../website_forum/overview.md), [`website_livechat`](../website_livechat/overview.md), [`website_mass_mailing`](../website_mass_mailing/overview.md), [`website_partner`](../website_partner/overview.md), [`website_payment`](../website_payment/overview.md), [`website_payment_authorize`](../website_payment_authorize/overview.md), [`website_profile`](../website_profile/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_autocomplete`](../website_sale_autocomplete/overview.md), [`website_sale_mondialrelay`](../website_sale_mondialrelay/overview.md), [`website_sale_picking`](../website_sale_picking/overview.md), [`website_sale_stock`](../website_sale_stock/overview.md), [`website_sale_wishlist`](../website_sale_wishlist/overview.md), [`website_slides`](../website_slides/overview.md), [`website_twitter`](../website_twitter/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`web`](../web/overview.md), [`web_editor`](../web_editor/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.

### Conversation-derived learnings

- [`2026-08-10-odoo-customization-testing`](../../conversations/2026-08-10-odoo-customization-testing.json)
- [`2026-08-10-odoo-postgres-mcp`](../../conversations/2026-08-10-odoo-postgres-mcp.json)
- [`2026-08-11-odoo-licensing-product-architecture`](../../conversations/2026-08-11-odoo-licensing-product-architecture.json)
- [`2026-08-11-repository-domain-extraction`](../../conversations/2026-08-11-repository-domain-extraction.json)
- [`2026-08-12-cmr-backup-restore-capacity`](../../conversations/2026-08-12-cmr-backup-restore-capacity.json)
- [`2026-08-12-cmr-endpoint-bootstrap-enterprise-gate`](../../conversations/2026-08-12-cmr-endpoint-bootstrap-enterprise-gate.json)
- [`2026-08-12-cmr-ho-store-isolation`](../../conversations/2026-08-12-cmr-ho-store-isolation.json)
- [`2026-08-13-customer-addon-mount-preflight`](../../conversations/2026-08-13-customer-addon-mount-preflight.json)
- [`2026-08-13-external-colima-capacity`](../../conversations/2026-08-13-external-colima-capacity.json)
- [`2026-08-13-ho-enterprise-source-gap`](../../conversations/2026-08-13-ho-enterprise-source-gap.json)
- [`2026-08-13-ho-missing-enterprise-metadata-quarantine`](../../conversations/2026-08-13-ho-missing-enterprise-metadata-quarantine.json)
- [`2026-08-13-ho-partial-registry-landing-repair`](../../conversations/2026-08-13-ho-partial-registry-landing-repair.json)
- [`2026-08-13-odoo-service-manager-mcp`](../../conversations/2026-08-13-odoo-service-manager-mcp.json)
- [`2026-08-14-ctl-fashion-isolated-restore`](../../conversations/2026-08-14-ctl-fashion-isolated-restore.json)
- [`2026-08-14-customer-source-lossless-delta-consolidation`](../../conversations/2026-08-14-customer-source-lossless-delta-consolidation.json)
- [`2026-08-14-ho-customer-schema-drift-upgrade`](../../conversations/2026-08-14-ho-customer-schema-drift-upgrade.json)
- [`2026-08-14-ho-enterprise-source-restored`](../../conversations/2026-08-14-ho-enterprise-source-restored.json)
- [`2026-08-14-ho-enterprise-view-compatibility`](../../conversations/2026-08-14-ho-enterprise-view-compatibility.json)
- [`2026-08-14-local-proprietary-dependency-consolidation`](../../conversations/2026-08-14-local-proprietary-dependency-consolidation.json)
- [`2026-08-14-portable-odoodata-layout`](../../conversations/2026-08-14-portable-odoodata-layout.json)
