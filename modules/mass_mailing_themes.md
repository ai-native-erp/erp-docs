---
layout: page
title: "Mass Mailing Themes (mass_mailing_themes)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/mass_mailing_themes/
nav_order: 0
---
# Mass Mailing Themes — `mass_mailing_themes`

**Source:** [`agents/modules/generated/mass_mailing_themes.yaml`](../../agents/modules/generated/mass_mailing_themes.yaml) · **Wiki:** [`knowledge/modules/mass_mailing_themes/overview.md`](../../knowledge/modules/mass_mailing_themes/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>mass_mailing_themes</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Mass Mailing Themes</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">marketing_events</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/mass_mailing_themes</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mass_mailing_themes"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Design gorgeous mails

## Direct dependencies

[`mass_mailing`](mass_mailing.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.mass_mailing` | depends_on | `agents/modules/generated/mass_mailing.yaml` |

## Full wiki excerpt

- SME owner: [`module.mass_mailing_themes`](../../../agents/modules/generated/mass_mailing_themes.yaml)
- Domain: `marketing_events`
- Category: Marketing/Email Marketing
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/mass_mailing_themes)
- Direct dependencies: [`mass_mailing`](../mass_mailing/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:mass_mailing_themes`](../../impact-graph.json)

## Purpose

Design gorgeous mails

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.mass_mailing`](../../../agents/modules/generated/mass_mailing.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
