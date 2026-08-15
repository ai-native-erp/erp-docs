---
layout: page
title: "Italy eCommerce eInvoicing (l10n_it_edi_website_sale)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_it_edi_website_sale/
nav_order: 0
---
# Italy eCommerce eInvoicing — `l10n_it_edi_website_sale`

**Source:** [`agents/modules/generated/l10n_it_edi_website_sale.yaml`](../../agents/modules/generated/l10n_it_edi_website_sale.yaml) · **Wiki:** [`knowledge/modules/l10n_it_edi_website_sale/overview.md`](../../knowledge/modules/l10n_it_edi_website_sale/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_it_edi_website_sale</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Italy eCommerce eInvoicing</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">OEEL-1</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_it_edi_website_sale</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_it_edi_website_sale"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Features for Italian eCommerce eInvoicing

## Direct dependencies

[`l10n_it_edi`](l10n_it_edi.md), [`website_sale`](website_sale.md)

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.l10n_it_edi` | depends_on | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.website_sale` | depends_on | `agents/modules/generated/website_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_it_edi_website_sale`](../../../agents/modules/generated/l10n_it_edi_website_sale.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_it_edi_website_sale)
- Direct dependencies: [`l10n_it_edi`](../l10n_it_edi/overview.md), [`website_sale`](../website_sale/overview.md)
- Declared license: `OEEL-1`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_it_edi_website_sale`](../../impact-graph.json)

## Purpose

Features for Italian eCommerce eInvoicing

## Model relationships

No static model declarations found.

## Related SME agents

- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — depends_on
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: None.
- Required specialist reviewers: security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
