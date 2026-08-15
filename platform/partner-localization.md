---
layout: platform-page
title: "Partners, Companies, Currency, and Localization Primitives"
subtitle: "Base-platform SME — partner localization"
permalink: /platform/partner-localization/
nav_order: 0
nav_title: "Partners, Companies, Currency, and Localization Primitives"
---
# Partners, Companies, Currency, and Localization Primitives

**Source:** [`agents/platform/partner-localization.yaml`](../../agents/platform/partner-localization.yaml) · **Wiki:** [`knowledge/base-platform/partner-localization.md`](../../knowledge/base-platform/partner-localization.md)

- Owner: [`platform.partner-localization`](../../agents/platform/partner-localization.yaml)
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/commit/126b5bdd1e85771549198976f8570cd2ff167608)
- Impact graph: [`platform:partner-localization`](relations.json)

- Platformer handbook: [architecture, features, data model, and troubleshooting](../platform-handbook/README.md)

## Connected platform SMEs and wikis

- [Configuration, Defaults, Settings, and Sequences](configuration-settings.md) — [`platform.configuration-settings`](../../agents/platform/configuration-settings.yaml)
- [Multi-company and Context Boundaries](multi-company.md) — [`platform.multi-company`](../../agents/platform/multi-company.yaml)
- [Security and Identity](security-identity.md) — [`platform.security-identity`](../../agents/platform/security-identity.yaml)

## Connected module SMEs and wikis

- [`base`](../modules/base/overview.md) — [`module.base`](../../agents/modules/generated/base.yaml)
- [`contacts`](../modules/contacts/overview.md) — [`module.contacts`](../../agents/modules/generated/contacts.yaml)

## Upstream evidence surfaces

- [`odoo/addons/base/models/res_partner.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/res_partner.py)
- [`odoo/addons/base/models/res_company.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/res_company.py)
- [`odoo/addons/base/models/res_currency.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/res_currency.py)
- [`odoo/addons/base/models/res_country.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/res_country.py)
- [`odoo/addons/base/models/res_lang.py`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/odoo/addons/base/models/res_lang.py)

## High-risk changes

- shared master data
- currency rounding
- localization assumptions
- company ownership

## Change protocol

Traverse connected SMEs, module dependency/reverse-dependency edges, and model extension edges before implementation. Validate the smallest affected test set plus bounded downstream impact; escalate public access, company boundaries, schema, data loading, and transaction changes to their linked reviewers.
