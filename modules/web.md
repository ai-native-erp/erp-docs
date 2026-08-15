---
layout: page
title: "Web (web)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/web/
nav_order: 0
---
# Web — `web`

**Source:** [`agents/modules/generated/web.yaml`](../../agents/modules/generated/web.yaml) · **Wiki:** [`knowledge/modules/web/overview.md`](../../knowledge/modules/web/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>web</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Web</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/web</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/web"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`base`](base.md)

## Reverse dependencies (modules that depend on this)

[`attachment_indexation`](attachment_indexation.md), [`auth_oauth`](auth_oauth.md), [`auth_password_policy`](auth_password_policy.md), [`auth_signup`](auth_signup.md), [`auth_totp`](auth_totp.md), [`barcodes`](barcodes.md), [`base_iban`](base_iban.md), [`base_import`](base_import.md), [`base_import_module`](base_import_module.md), [`base_setup`](base_setup.md), [`bus`](bus.md), [`hr`](hr.md), [`http_routing`](http_routing.md), [`iap`](iap.md), [`mail_plugin`](mail_plugin.md), [`onboarding`](onboarding.md), [`portal`](portal.md), [`pos_mercury`](pos_mercury.md), [`project`](project.md), [`resource`](resource.md), [`sale_order_extension`](sale_order_extension.md), [`spreadsheet`](spreadsheet.md), [`test_http`](test_http.md), [`test_new_api`](test_new_api.md), [`test_rpc`](test_rpc.md), [`test_search_panel`](test_search_panel.md), [`test_testing_utilities`](test_testing_utilities.md), [`test_xlsx_export`](test_xlsx_export.md), [`transifex`](transifex.md), [`utm`](utm.md), [`web_editor`](web_editor.md), [`web_hierarchy`](web_hierarchy.md), [`web_tour`](web_tour.md), [`website`](website.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>base.document.layout</code></div><div class="role">defined by <code>web</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.image</code></div><div class="role">defined by <code>web</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>base</code></div><div class="role">extended by <code>web</code></div></div>
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>web</code></div></div>
<div class="model"><div class="name"><code>ir.model</code></div><div class="role">extended by <code>web</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.image</code></div><div class="role">extended by <code>web</code></div></div>
<div class="model"><div class="name"><code>ir.qweb.field.image_url</code></div><div class="role">extended by <code>web</code></div></div>
<div class="model"><div class="name"><code>ir.ui.menu</code></div><div class="role">extended by <code>web</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>web</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>web</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>web</code></div></div>
<div class="model"><div class="name"><code>res.users</code></div><div class="role">extended by <code>web</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from, model_extended_by | `agents/modules/generated/account.yaml` |
| `module.attachment_indexation` | required_by | `agents/modules/generated/attachment_indexation.yaml` |
| `module.auth_oauth` | required_by | `agents/modules/generated/auth_oauth.yaml` |
| `module.auth_password_policy` | required_by | `agents/modules/generated/auth_password_policy.yaml` |
| `module.auth_signup` | required_by | `agents/modules/generated/auth_signup.yaml` |
| `module.auth_totp` | required_by | `agents/modules/generated/auth_totp.yaml` |
| `module.barcodes` | required_by | `agents/modules/generated/barcodes.yaml` |
| `module.base` | depends_on, extends_model_from, model_extended_by | `agents/modules/generated/base.yaml` |
| `module.base_iban` | required_by | `agents/modules/generated/base_iban.yaml` |
| `module.base_import` | required_by | `agents/modules/generated/base_import.yaml` |

## Conversation learnings

- [`2026-08-10-sale-servicenow-patterns`](../../knowledge/conversations/2026-08-10-sale-servicenow-patterns.json)
- [`2026-08-11-owl-component-fundamentals`](../../knowledge/conversations/2026-08-11-owl-component-fundamentals.json)
- [`2026-08-11-owl-orm-rpc-data-access`](../../knowledge/conversations/2026-08-11-owl-orm-rpc-data-access.json)
- [`2026-08-11-sale-order-workspace`](../../knowledge/conversations/2026-08-11-sale-order-workspace.json)
- [`2026-08-12-cmr-backup-restore-capacity`](../../knowledge/conversations/2026-08-12-cmr-backup-restore-capacity.json)
- [`2026-08-12-cmr-endpoint-bootstrap-enterprise-gate`](../../knowledge/conversations/2026-08-12-cmr-endpoint-bootstrap-enterprise-gate.json)
- [`2026-08-12-cmr-ho-store-isolation`](../../knowledge/conversations/2026-08-12-cmr-ho-store-isolation.json)
- [`2026-08-12-odoo-17-customer-baseline`](../../knowledge/conversations/2026-08-12-odoo-17-customer-baseline.json)
- [`2026-08-13-ho-missing-enterprise-metadata-quarantine`](../../knowledge/conversations/2026-08-13-ho-missing-enterprise-metadata-quarantine.json)
- [`2026-08-13-ho-partial-registry-landing-repair`](../../knowledge/conversations/2026-08-13-ho-partial-registry-landing-repair.json)
- [`2026-08-13-webclient-stale-view-after-quarantine`](../../knowledge/conversations/2026-08-13-webclient-stale-view-after-quarantine.json)
- [`2026-08-14-ho-enterprise-source-restored`](../../knowledge/conversations/2026-08-14-ho-enterprise-source-restored.json)
- [`2026-08-14-ho-enterprise-view-compatibility`](../../knowledge/conversations/2026-08-14-ho-enterprise-view-compatibility.json)

## Full wiki excerpt

- SME owner: [`module.web`](../../../agents/modules/generated/web.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/web)
- Direct dependencies: [`base`](../base/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`attachment_indexation`](../attachment_indexation/overview.md), [`auth_oauth`](../auth_oauth/overview.md), [`auth_password_policy`](../auth_password_policy/overview.md), [`auth_signup`](../auth_signup/overview.md), [`auth_totp`](../auth_totp/overview.md), [`barcodes`](../barcodes/overview.md), [`base_iban`](../base_iban/overview.md), [`base_import`](../base_import/overview.md), [`base_import_module`](../base_import_module/overview.md), [`base_setup`](../base_setup/overview.md), [`bus`](../bus/overview.md), [`hr`](../hr/overview.md), [`http_routing`](../http_routing/overview.md), [`iap`](../iap/overview.md), [`mail_plugin`](../mail_plugin/overview.md), [`onboarding`](../onboarding/overview.md), [`portal`](../portal/overview.md), [`pos_mercury`](../pos_mercury/overview.md), [`project`](../project/overview.md), [`resource`](../resource/overview.md), [`sale_order_extension`](../sale_order_extension/overview.md), [`spreadsheet`](../spreadsheet/overview.md), [`test_http`](../test_http/overview.md), [`test_new_api`](../test_new_api/overview.md), [`test_rpc`](../test_rpc/overview.md), [`test_search_panel`](../test_search_panel/overview.md), [`test_testing_utilities`](../test_testing_utilities/overview.md), [`test_xlsx_export`](../test_xlsx_export/overview.md), [`transifex`](../transifex/overview.md), [`utm`](../utm/overview.md), [`web_editor`](../web_editor/overview.md), [`web_hierarchy`](../web_hierarchy/overview.md), [`web_tour`](../web_tour/overview.md), [`website`](../website/overview.md)
- Impact graph: [`module:web`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `base.document.layout` — extended by [`account`](../account/overview.md), [`l10n_ca`](../l10n_ca/overview.md), [`l10n_cz`](../l10n_cz/overview.md), [`l10n_din5008`](../l10n_din5008/overview.md), [`l10n_ma`](../l10n_ma/overview.md), [`l10n_mu_account`](../l10n_mu_account/overview.md), [`l10n_my_ubl_pint`](../l10n_my_ubl_pint/overview.md), [`l10n_sk`](../l10n_sk/overview.md)
- `ir.qweb.field.image` — extended by [`base`](../base/overview.md), [`web_editor`](../web_editor/overview.md), [`web_unsplash`](../web_unsplash/overview.md)
- Extends `base` — defined by [`base`](../base/overview.md)
- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `ir.model` — defined by [`base`](../base/overview.md), [`website`](../website/overview.md)
- Extends `ir.qweb.field.image` — defined by [`base`](../base/overview.md), [`web_editor`](../web_editor/overview.md)
- Extends `ir.qweb.field.image_url` — defined by [`base`](../base/overview.md)
- Extends `ir.ui.menu` — defined by [`base`](../base/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)
- Extends `res.users` — defined by [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from, model_extended_by
- [`module.attachment_indexation`](../../../agents/modules/generated/attachment_indexation.yaml) — required_by
- [`module.auth_oauth`](../../../agents/modules/generated/auth_oauth.yaml) — required_by
- [`module.auth_password_policy`](../../../agents/modules/generated/auth_password_policy.yaml) — required_by
- [`module.auth_signup`](../../../agents/modules/generated/auth_signup.yaml) — required_by
- [`module.auth_totp`](../../../agents/modules/generated/auth_totp.yaml) — required_by
- [`module.barcodes`](../../../agents/modules/generated/barcodes.yaml) — required_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — depends_on, extends_model_from, model_extended_by
- [`module.base_iban`](../../../agents/modules/generated/base_iban.yaml) — required_by
- [`module.base_import`](../../../agents/modules/generated/base_import.yaml) — required_by
- [`module.base_import_module`](../../../agents/modules/generated/base_import_module.yaml) — required_by
- [`module.base_setup`](../../../agents/modules/generated/base_setup.yaml) — required_by
- [`module.bus`](../../../agents/modules/generated/bus.yaml) — required_by
- [`module.contacts`](../../../agents/modules/generated/contacts.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.hr`](../../../agents/modules/generated/hr.yaml) — required_by
- [`module.http_routing`](../../../agents/modules/generated/http_routing.yaml) — required_by
- [`module.iap`](../../../agents/modules/generated/iap.yaml) — required_by
- [`module.l10n_ca`](../../../agents/modules/generated/l10n_ca.yaml) — model_extended_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_cz`](../../../agents/modules/generated/l10n_cz.yaml) — model_extended_by
- [`module.l10n_din5008`](../../../agents/modules/generated/l10n_din5008.yaml) — model_extended_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_ma`](../../../agents/modules/generated/l10n_ma.yaml) — model_extended_by
- [`module.l10n_mu_account`](../../../agents/modules/generated/l10n_mu_account.yaml) — model_extended_by
- [`module.l10n_my_ubl_pint`](../../../agents/modules/generated/l10n_my_ubl_pint.yaml) — model_extended_by
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_sk`](../../../agents/modules/generated/l10n_sk.yaml) — model_extended_by
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.mail_plugin`](../../../agents/modules/generated/mail_plugin.yaml) — required_by
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — extends_model_from
- [`module.mass_mailing_sms`](../../../agents/modules/generated/mass_mailing_sms.yaml) — extends_model_from
- [`module.onboarding`](../../../agents/modules/generated/onboarding.yaml) — required_by
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — required_by
- [`module.pos_mercury`](../../../agents/modules/generated/pos_mercury.yaml) — required_by
- [`module.project`](../../../agents/modules/generated/project.yaml) — required_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.resource`](../../../agents/modules/generated/resource.yaml) — required_by
- [`module.sale_order_extension`](../../../agents/modules/generated/sale_order_extension.yaml) — required_by
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.spreadsheet`](../../../agents/modules/generated/spreadsheet.yaml) — required_by
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.test_http`](../../../agents/modules/generated/test_http.yaml) — required_by
- [`module.test_new_api`](../../../agents/modules/generated/test_new_api.yaml) — required_by
- [`module.test_rpc`](../../../agents/modules/generated/test_rpc.yaml) — required_by
- [`module.test_search_panel`](../../../agents/modules/generated/test_search_panel.yaml) — required_by
- [`module.test_testing_utilities`](../../../agents/modules/generated/test_testing_utilities.yaml) — required_by
- [`module.test_xlsx_export`](../../../agents/modules/generated/test_xlsx_export.yaml) — required_by
- [`module.transifex`](../../../agents/modules/generated/transifex.yaml) — required_by
- [`module.utm`](../../../agents/modules/generated/utm.yaml) — required_by
- [`module.web_editor`](../../../agents/modules/generated/web_editor.yaml) — extends_model_from, model_extended_by, required_by
- [`module.web_hierarchy`](../../../agents/modules/generated/web_hierarchy.yaml) — required_by
- [`module.web_tour`](../../../agents/modules/generated/web_tour.yaml) — required_by
- [`module.web_unsplash`](../../../agents/modules/generated/web_unsplash.yaml) — model_extended_by
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from, required_by
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from

## Regression impact checklist

- Review 34 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_ca`](../l10n_ca/overview.md), [`l10n_cz`](../l10n_cz/overview.md), [`l10n_din5008`](../l10n_din5008/overview.md), [`l10n_ma`](../l10n_ma/overview.md), [`l10n_mu_account`](../l10n_mu_account/overview.md), [`l10n_my_ubl_pint`](../l10n_my_ubl_pint/overview.md), [`l10n_sk`](../l10n_sk/overview.md), [`web_editor`](../web_editor/overview.md), [`web_unsplash`](../web_unsplash/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`contacts`](../contacts/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`mass_mailing_sms`](../mass_mailing_sms/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`web_editor`](../web_editor/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.

### Conversation-derived learnings

- [`2026-08-10-sale-servicenow-patterns`](../../conversations/2026-08-10-sale-servicenow-patterns.json)
- [`2026-08-11-owl-component-fundamentals`](../../conversations/2026-08-11-owl-component-fundamentals.json)
- [`2026-08-11-owl-orm-rpc-data-access`](../../conversations/2026-08-11-owl-orm-rpc-data-access.json)
- [`2026-08-11-sale-order-workspace`](../../conversations/2026-08-11-sale-order-workspace.json)
- [`2026-08-12-cmr-backup-restore-capacity`](../../conversations/2026-08-12-cmr-backup-restore-capacity.json)
- [`2026-08-12-cmr-endpoint-bootstrap-enterprise-gate`](../../conversations/2026-08-12-cmr-endpoint-bootstrap-enterprise-gate.json)
- [`2026-08-12-cmr-ho-store-isolation`](../../conversations/2026-08-12-cmr-ho-store-isolation.json)
- [`2026-08-12-odoo-17-customer-baseline`](../../conversations/2026-08-12-odoo-17-customer-baseline.json)
- [`2026-08-13-ho-missing-enterprise-metadata-quarantine`](../../conversations/2026-08-13-ho-missing-enterprise-metadata-quarantine.json)
- [`2026-08-13-ho-partial-registry-landing-repair`](../../conversations/2026-08-13-ho-partial-registry-landing-repair.json)
- [`2026-08-13-webclient-stale-view-after-quarantine`](../../conversations/2026-08-13-webclient-stale-view-after-quarantine.json)
- [`2026-08-14-ho-enterprise-source-restored`](../../conversations/2026-08-14-ho-enterprise-source-restored.json)
- [`2026-08-14-ho-enterprise-view-compatibility`](../../conversations/2026-08-14-ho-enterprise-view-compatibility.json)
