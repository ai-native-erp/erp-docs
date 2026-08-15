---
layout: page
title: "Project Mail Plugin (project_mail_plugin)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/project_mail_plugin/
nav_order: 0
---
# Project Mail Plugin — `project_mail_plugin`

**Source:** [`agents/modules/generated/project_mail_plugin.yaml`](../../agents/modules/generated/project_mail_plugin.yaml) · **Wiki:** [`knowledge/modules/project_mail_plugin/overview.md`](../../knowledge/modules/project_mail_plugin/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>project_mail_plugin</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Project Mail Plugin</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">projects_services</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/project_mail_plugin</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/project_mail_plugin"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Integrate your inbox with projects

## Direct dependencies

[`mail_plugin`](mail_plugin.md), [`project`](project.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mail_plugin` | depends_on | `agents/modules/generated/mail_plugin.yaml` |
| `module.project` | depends_on | `agents/modules/generated/project.yaml` |

## Full wiki excerpt

- SME owner: [`module.project_mail_plugin`](../../../agents/modules/generated/project_mail_plugin.yaml)
- Domain: `projects_services`
- Category: Services/Project
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/project_mail_plugin)
- Direct dependencies: [`mail_plugin`](../mail_plugin/overview.md), [`project`](../project/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:project_mail_plugin`](../../impact-graph.json)

## Purpose

Integrate your inbox with projects

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.mail_plugin`](../../../agents/modules/generated/mail_plugin.yaml) — depends_on
- [`module.project`](../../../agents/modules/generated/project.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
