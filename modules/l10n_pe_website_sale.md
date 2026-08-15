---
layout: page
title: "Peruvian eCommerce (l10n_pe_website_sale)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_pe_website_sale/
nav_order: 0
---
# Peruvian eCommerce — `l10n_pe_website_sale`

**Source:** [`agents/modules/generated/l10n_pe_website_sale.yaml`](../../agents/modules/generated/l10n_pe_website_sale.yaml) · **Wiki:** [`knowledge/modules/l10n_pe_website_sale/overview.md`](../../knowledge/modules/l10n_pe_website_sale/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_pe_website_sale</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Peruvian eCommerce</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_pe_website_sale</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_pe_website_sale"><code>126b5bd</code></a></div></div>
</div>
## Purpose

Be able to see Identification Type in ecommerce checkout form.

## Direct dependencies

[`l10n_pe`](l10n_pe.md), [`website_sale`](website_sale.md)

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>website</code></div><div class="role">extended by <code>l10n_pe_website_sale</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.l10n_pe` | depends_on | `agents/modules/generated/l10n_pe.yaml` |
| `module.website` | extends_model_from | `agents/modules/generated/website.yaml` |
| `module.website_sale` | depends_on | `agents/modules/generated/website_sale.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_pe_website_sale`](../../../agents/modules/generated/l10n_pe_website_sale.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/Website
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_pe_website_sale)
- Direct dependencies: [`l10n_pe`](../l10n_pe/overview.md), [`website_sale`](../website_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_pe_website_sale`](../../impact-graph.json)

## Purpose

Be able to see Identification Type in ecommerce checkout form.

## Model relationships

- Extends `website` — defined by [`website`](../website/overview.md)

## Related SME agents

- [`module.l10n_pe`](../../../agents/modules/generated/l10n_pe.yaml) — depends_on
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — depends_on

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: None.
- Review model owners used by this module: [`website`](../website/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
