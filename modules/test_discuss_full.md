---
layout: page
title: "Test Discuss (full) (test_discuss_full)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/test_discuss_full/
nav_order: 0
---
# Test Discuss (full) — `test_discuss_full`

**Source:** [`agents/modules/generated/test_discuss_full.yaml`](../../agents/modules/generated/test_discuss_full.yaml) · **Wiki:** [`knowledge/modules/test_discuss_full/overview.md`](../../knowledge/modules/test_discuss_full/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>test_discuss_full</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Test Discuss (full)</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">platform_core</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/test_discuss_full</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_discuss_full"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Test of Discuss with all possible overrides installed.

## Direct dependencies

[`calendar`](calendar.md), [`crm`](crm.md), [`crm_livechat`](crm_livechat.md), [`hr_attendance`](hr_attendance.md), [`hr_fleet`](hr_fleet.md), [`hr_holidays`](hr_holidays.md), [`hr_homeworking`](hr_homeworking.md), [`im_livechat`](im_livechat.md), [`mail`](mail.md), [`mail_bot`](mail_bot.md), [`project_todo`](project_todo.md), [`website_livechat`](website_livechat.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.calendar` | depends_on | `agents/modules/generated/calendar.yaml` |
| `module.crm` | depends_on | `agents/modules/generated/crm.yaml` |
| `module.crm_livechat` | depends_on | `agents/modules/generated/crm_livechat.yaml` |
| `module.hr_attendance` | depends_on | `agents/modules/generated/hr_attendance.yaml` |
| `module.hr_fleet` | depends_on | `agents/modules/generated/hr_fleet.yaml` |
| `module.hr_holidays` | depends_on | `agents/modules/generated/hr_holidays.yaml` |
| `module.hr_homeworking` | depends_on | `agents/modules/generated/hr_homeworking.yaml` |
| `module.im_livechat` | depends_on | `agents/modules/generated/im_livechat.yaml` |
| `module.mail` | depends_on | `agents/modules/generated/mail.yaml` |
| `module.mail_bot` | depends_on | `agents/modules/generated/mail_bot.yaml` |

## Full wiki excerpt

- SME owner: [`module.test_discuss_full`](../../../agents/modules/generated/test_discuss_full.yaml)
- Domain: `platform_core`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/test_discuss_full)
- Direct dependencies: [`calendar`](../calendar/overview.md), [`crm`](../crm/overview.md), [`crm_livechat`](../crm_livechat/overview.md), [`hr_attendance`](../hr_attendance/overview.md), [`hr_fleet`](../hr_fleet/overview.md), [`hr_holidays`](../hr_holidays/overview.md), [`hr_homeworking`](../hr_homeworking/overview.md), [`im_livechat`](../im_livechat/overview.md), [`mail`](../mail/overview.md), [`mail_bot`](../mail_bot/overview.md), [`project_todo`](../project_todo/overview.md), [`website_livechat`](../website_livechat/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:test_discuss_full`](../../impact-graph.json)

## Purpose

Test of Discuss with all possible overrides installed.

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.calendar`](../../../agents/modules/generated/calendar.yaml) — depends_on
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — depends_on
- [`module.crm_livechat`](../../../agents/modules/generated/crm_livechat.yaml) — depends_on
- [`module.hr_attendance`](../../../agents/modules/generated/hr_attendance.yaml) — depends_on
- [`module.hr_fleet`](../../../agents/modules/generated/hr_fleet.yaml) — depends_on
- [`module.hr_holidays`](../../../agents/modules/generated/hr_holidays.yaml) — depends_on
- [`module.hr_homeworking`](../../../agents/modules/generated/hr_homeworking.yaml) — depends_on
- [`module.im_livechat`](../../../agents/modules/generated/im_livechat.yaml) — depends_on
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — depends_on
- [`module.mail_bot`](../../../agents/modules/generated/mail_bot.yaml) — depends_on
- [`module.project_todo`](../../../agents/modules/generated/project_todo.yaml) — depends_on
- [`module.website_livechat`](../../../agents/modules/generated/website_livechat.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
