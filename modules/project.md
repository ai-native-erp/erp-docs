---
layout: page
title: "Project (project)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/project/
nav_order: 0
---
# Project — `project`

**Source:** [`agents/modules/generated/project.yaml`](../../agents/modules/generated/project.yaml) · **Wiki:** [`knowledge/modules/project/overview.md`](../../knowledge/modules/project/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>project</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Project</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">projects_services</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">True</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/project</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/project"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Organize and plan your projects

## Direct dependencies

[`analytic`](analytic.md), [`base_setup`](base_setup.md), [`digest`](digest.md), [`mail`](mail.md), [`portal`](portal.md), [`rating`](rating.md), [`resource`](resource.md), [`web`](web.md), [`web_tour`](web_tour.md)

## Reverse dependencies (modules that depend on this)

[`hr_timesheet`](hr_timesheet.md), [`project_account`](project_account.md), [`project_mail_plugin`](project_mail_plugin.md), [`project_mrp`](project_mrp.md), [`project_sms`](project_sms.md), [`project_todo`](project_todo.md), [`website_form_project`](website_form_project.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>project.collaborator</code></div><div class="role">defined by <code>project</code></div></div>
<div class="model"><div class="name"><code>project.milestone</code></div><div class="role">defined by <code>project</code></div></div>
<div class="model"><div class="name"><code>project.project</code></div><div class="role">defined by <code>project</code></div></div>
<div class="model"><div class="name"><code>project.project.stage</code></div><div class="role">defined by <code>project</code></div></div>
<div class="model"><div class="name"><code>project.project.stage.delete.wizard</code></div><div class="role">defined by <code>project</code></div></div>
<div class="model"><div class="name"><code>project.share.wizard</code></div><div class="role">defined by <code>project</code></div></div>
<div class="model"><div class="name"><code>project.tags</code></div><div class="role">defined by <code>project</code></div></div>
<div class="model"><div class="name"><code>project.task</code></div><div class="role">defined by <code>project</code></div></div>
<div class="model"><div class="name"><code>project.task.burndown.chart.report</code></div><div class="role">defined by <code>project</code></div></div>
<div class="model"><div class="name"><code>project.task.recurrence</code></div><div class="role">defined by <code>project</code></div></div>
<div class="model"><div class="name"><code>project.task.stage.personal</code></div><div class="role">defined by <code>project</code></div></div>
<div class="model"><div class="name"><code>project.task.type</code></div><div class="role">defined by <code>project</code></div></div>
<div class="model"><div class="name"><code>project.task.type.delete.wizard</code></div><div class="role">defined by <code>project</code></div></div>
<div class="model"><div class="name"><code>project.update</code></div><div class="role">defined by <code>project</code></div></div>
<div class="model"><div class="name"><code>report.project.task.user</code></div><div class="role">defined by <code>project</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>account.analytic.account</code></div><div class="role">extended by <code>project</code></div></div>
<div class="model"><div class="name"><code>digest.digest</code></div><div class="role">extended by <code>project</code></div></div>
<div class="model"><div class="name"><code>ir.ui.menu</code></div><div class="role">extended by <code>project</code></div></div>
<div class="model"><div class="name"><code>mail.activity.mixin</code></div><div class="role">extended by <code>project</code></div></div>
<div class="model"><div class="name"><code>mail.alias.mixin</code></div><div class="role">extended by <code>project</code></div></div>
<div class="model"><div class="name"><code>mail.message</code></div><div class="role">extended by <code>project</code></div></div>
<div class="model"><div class="name"><code>mail.thread</code></div><div class="role">extended by <code>project</code></div></div>
<div class="model"><div class="name"><code>mail.thread.cc</code></div><div class="role">extended by <code>project</code></div></div>
<div class="model"><div class="name"><code>mail.tracking.duration.mixin</code></div><div class="role">extended by <code>project</code></div></div>
<div class="model"><div class="name"><code>portal.mixin</code></div><div class="role">extended by <code>project</code></div></div>
<div class="model"><div class="name"><code>portal.share</code></div><div class="role">extended by <code>project</code></div></div>
<div class="model"><div class="name"><code>project.project</code></div><div class="role">extended by <code>project</code></div></div>
<div class="model"><div class="name"><code>project.task</code></div><div class="role">extended by <code>project</code></div></div>
<div class="model"><div class="name"><code>project.task.type</code></div><div class="role">extended by <code>project</code></div></div>
<div class="model"><div class="name"><code>rating.mixin</code></div><div class="role">extended by <code>project</code></div></div>
<div class="model"><div class="name"><code>rating.parent.mixin</code></div><div class="role">extended by <code>project</code></div></div>
<div class="model"><div class="name"><code>res.config.settings</code></div><div class="role">extended by <code>project</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>project</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.analytic` | depends_on, extends_model_from | `agents/modules/generated/analytic.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.base_setup` | depends_on | `agents/modules/generated/base_setup.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.digest` | depends_on, extends_model_from | `agents/modules/generated/digest.yaml` |
| `module.hr_timesheet` | extends_model_from, model_extended_by, required_by | `agents/modules/generated/hr_timesheet.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |

## Full wiki excerpt

- SME owner: [`module.project`](../../../agents/modules/generated/project.yaml)
- Domain: `projects_services`
- Category: Services/Project
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/project)
- Direct dependencies: [`analytic`](../analytic/overview.md), [`base_setup`](../base_setup/overview.md), [`digest`](../digest/overview.md), [`mail`](../mail/overview.md), [`portal`](../portal/overview.md), [`rating`](../rating/overview.md), [`resource`](../resource/overview.md), [`web`](../web/overview.md), [`web_tour`](../web_tour/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`hr_timesheet`](../hr_timesheet/overview.md), [`project_account`](../project_account/overview.md), [`project_mail_plugin`](../project_mail_plugin/overview.md), [`project_mrp`](../project_mrp/overview.md), [`project_sms`](../project_sms/overview.md), [`project_todo`](../project_todo/overview.md), [`website_form_project`](../website_form_project/overview.md)
- Impact graph: [`module:project`](../../impact-graph.json)

## Purpose

Organize and plan your projects

## Model relationships

- `project.collaborator` — extended by [`hr_timesheet`](../hr_timesheet/overview.md)
- `project.milestone` — extended by [`sale_project`](../sale_project/overview.md)
- `project.project` — extended by [`hr_timesheet`](../hr_timesheet/overview.md), [`project_account`](../project_account/overview.md), [`project_hr_expense`](../project_hr_expense/overview.md), [`project_mrp`](../project_mrp/overview.md), [`project_purchase`](../project_purchase/overview.md), [`project_sale_expense`](../project_sale_expense/overview.md), [`project_sms`](../project_sms/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md)
- `project.project.stage` — extended by [`project_sms`](../project_sms/overview.md)
- `project.project.stage.delete.wizard`
- `project.share.wizard`
- `project.tags`
- `project.task` — extended by [`hr_timesheet`](../hr_timesheet/overview.md), [`project_sms`](../project_sms/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md), [`project_todo`](../project_todo/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md)
- `project.task.burndown.chart.report`
- `project.task.recurrence` — extended by [`sale_project`](../sale_project/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md)
- `project.task.stage.personal`
- `project.task.type` — extended by [`project_sms`](../project_sms/overview.md)
- `project.task.type.delete.wizard`
- `project.update` — extended by [`hr_timesheet`](../hr_timesheet/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md)
- `report.project.task.user` — extended by [`hr_timesheet`](../hr_timesheet/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md)
- Extends `account.analytic.account` — defined by [`analytic`](../analytic/overview.md)
- Extends `digest.digest` — defined by [`digest`](../digest/overview.md)
- Extends `ir.ui.menu` — defined by [`base`](../base/overview.md)
- Extends `mail.activity.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.alias.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `mail.message` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread` — defined by [`mail`](../mail/overview.md)
- Extends `mail.thread.cc` — defined by [`mail`](../mail/overview.md)
- Extends `mail.tracking.duration.mixin` — defined by [`mail`](../mail/overview.md)
- Extends `portal.mixin` — defined by [`portal`](../portal/overview.md)
- Extends `portal.share` — defined by [`portal`](../portal/overview.md)
- Extends `project.project` — framework/dynamic owner
- Extends `project.task` — defined by [`hr_timesheet`](../hr_timesheet/overview.md)
- Extends `project.task.type` — framework/dynamic owner
- Extends `rating.mixin` — defined by [`rating`](../rating/overview.md)
- Extends `rating.parent.mixin` — defined by [`rating`](../rating/overview.md)
- Extends `res.config.settings` — defined by [`base`](../base/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.analytic`](../../../agents/modules/generated/analytic.yaml) — depends_on, extends_model_from
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.base_setup`](../../../agents/modules/generated/base_setup.yaml) — depends_on
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.digest`](../../../agents/modules/generated/digest.yaml) — depends_on, extends_model_from
- [`module.hr_timesheet`](../../../agents/modules/generated/hr_timesheet.yaml) — extends_model_from, model_extended_by, required_by
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on, extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — depends_on, extends_model_from
- [`module.project_account`](../../../agents/modules/generated/project_account.yaml) — model_extended_by, required_by
- [`module.project_hr_expense`](../../../agents/modules/generated/project_hr_expense.yaml) — model_extended_by
- [`module.project_mail_plugin`](../../../agents/modules/generated/project_mail_plugin.yaml) — required_by
- [`module.project_mrp`](../../../agents/modules/generated/project_mrp.yaml) — model_extended_by, required_by
- [`module.project_purchase`](../../../agents/modules/generated/project_purchase.yaml) — model_extended_by
- [`module.project_sale_expense`](../../../agents/modules/generated/project_sale_expense.yaml) — model_extended_by
- [`module.project_sms`](../../../agents/modules/generated/project_sms.yaml) — model_extended_by, required_by
- [`module.project_timesheet_holidays`](../../../agents/modules/generated/project_timesheet_holidays.yaml) — model_extended_by
- [`module.project_todo`](../../../agents/modules/generated/project_todo.yaml) — model_extended_by, required_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.rating`](../../../agents/modules/generated/rating.yaml) — depends_on, extends_model_from
- [`module.resource`](../../../agents/modules/generated/resource.yaml) — depends_on
- [`module.sale_project`](../../../agents/modules/generated/sale_project.yaml) — model_extended_by
- [`module.sale_timesheet`](../../../agents/modules/generated/sale_timesheet.yaml) — model_extended_by
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on
- [`module.web_tour`](../../../agents/modules/generated/web_tour.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_form_project`](../../../agents/modules/generated/website_form_project.yaml) — required_by
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from

## Regression impact checklist

- Review 7 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`hr_timesheet`](../hr_timesheet/overview.md), [`project_account`](../project_account/overview.md), [`project_hr_expense`](../project_hr_expense/overview.md), [`project_mrp`](../project_mrp/overview.md), [`project_purchase`](../project_purchase/overview.md), [`project_sale_expense`](../project_sale_expense/overview.md), [`project_sms`](../project_sms/overview.md), [`project_timesheet_holidays`](../project_timesheet_holidays/overview.md), [`project_todo`](../project_todo/overview.md), [`sale_project`](../sale_project/overview.md), [`sale_timesheet`](../sale_timesheet/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`analytic`](../analytic/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`digest`](../digest/overview.md), [`hr_timesheet`](../hr_timesheet/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`portal`](../portal/overview.md), [`purchase`](../purchase/overview.md), [`rating`](../rating/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
