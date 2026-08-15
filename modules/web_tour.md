---
layout: page
title: "Tours (web_tour)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/web_tour/
nav_order: 0
---
# Tours — `web_tour`

**Source:** [`agents/modules/generated/web_tour.yaml`](../../agents/modules/generated/web_tour.yaml) · **Wiki:** [`knowledge/modules/web_tour/overview.md`](../../knowledge/modules/web_tour/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>web_tour</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Tours</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/web_tour</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/web_tour"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`web`](web.md)

## Reverse dependencies (modules that depend on this)

[`crm`](crm.md), [`hr_expense`](hr_expense.md), [`hr_recruitment`](hr_recruitment.md), [`mail`](mail.md), [`mass_mailing`](mass_mailing.md), [`project`](project.md), [`survey`](survey.md), [`test_apikeys`](test_apikeys.md), [`test_http`](test_http.md), [`test_main_flows`](test_main_flows.md), [`test_new_api`](test_new_api.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>web_tour.tour</code></div><div class="role">defined by <code>web_tour</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>web_tour</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.crm` | required_by | `agents/modules/generated/crm.yaml` |
| `module.hr_expense` | required_by | `agents/modules/generated/hr_expense.yaml` |
| `module.hr_recruitment` | required_by | `agents/modules/generated/hr_recruitment.yaml` |
| `module.mail` | required_by | `agents/modules/generated/mail.yaml` |
| `module.mass_mailing` | required_by | `agents/modules/generated/mass_mailing.yaml` |
| `module.project` | required_by | `agents/modules/generated/project.yaml` |
| `module.survey` | required_by | `agents/modules/generated/survey.yaml` |
| `module.test_apikeys` | required_by | `agents/modules/generated/test_apikeys.yaml` |
| `module.test_http` | required_by | `agents/modules/generated/test_http.yaml` |

## Conversation learnings

- [`2026-08-10-odoo-customization-testing`](../../knowledge/conversations/2026-08-10-odoo-customization-testing.json)

## Full wiki excerpt

- SME owner: [`module.web_tour`](../../../agents/modules/generated/web_tour.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/web_tour)
- Direct dependencies: [`web`](../web/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`crm`](../crm/overview.md), [`hr_expense`](../hr_expense/overview.md), [`hr_recruitment`](../hr_recruitment/overview.md), [`mail`](../mail/overview.md), [`mass_mailing`](../mass_mailing/overview.md), [`project`](../project/overview.md), [`survey`](../survey/overview.md), [`test_apikeys`](../test_apikeys/overview.md), [`test_http`](../test_http/overview.md), [`test_main_flows`](../test_main_flows/overview.md), [`test_new_api`](../test_new_api/overview.md)
- Impact graph: [`module:web_tour`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `web_tour.tour`
- Extends `ir.http` — defined by [`base`](../base/overview.md)

## Related SME agents

- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — required_by
- [`module.hr_expense`](../../../agents/modules/generated/hr_expense.yaml) — required_by
- [`module.hr_recruitment`](../../../agents/modules/generated/hr_recruitment.yaml) — required_by
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — required_by
- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — required_by
- [`module.project`](../../../agents/modules/generated/project.yaml) — required_by
- [`module.survey`](../../../agents/modules/generated/survey.yaml) — required_by
- [`module.test_apikeys`](../../../agents/modules/generated/test_apikeys.yaml) — required_by
- [`module.test_http`](../../../agents/modules/generated/test_http.yaml) — required_by
- [`module.test_main_flows`](../../../agents/modules/generated/test_main_flows.yaml) — required_by
- [`module.test_new_api`](../../../agents/modules/generated/test_new_api.yaml) — required_by
- [`module.web`](../../../agents/modules/generated/web.yaml) — depends_on

## Regression impact checklist

- Review 11 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`base`](../base/overview.md).
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.

### Conversation-derived learnings

- [`2026-08-10-odoo-customization-testing`](../../conversations/2026-08-10-odoo-customization-testing.json)
