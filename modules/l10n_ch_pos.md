---
layout: page
title: "Swiss - Point of Sale (l10n_ch_pos)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/l10n_ch_pos/
nav_order: 0
---
# Swiss - Point of Sale — `l10n_ch_pos`

**Source:** [`agents/modules/generated/l10n_ch_pos.yaml`](../../agents/modules/generated/l10n_ch_pos.yaml) · **Wiki:** [`knowledge/modules/l10n_ch_pos/overview.md`](../../knowledge/modules/l10n_ch_pos/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>l10n_ch_pos</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Swiss - Point of Sale</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">localization</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/l10n_ch_pos</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_ch_pos"><code>126b5bd</code></a></div></div>
</div>
## Purpose

No manifest summary supplied.

## Direct dependencies

[`l10n_ch`](l10n_ch.md), [`point_of_sale`](point_of_sale.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>pos.order</code></div><div class="role">defined by <code>l10n_ch_pos</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>pos.order</code></div><div class="role">extended by <code>l10n_ch_pos</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.l10n_ch` | depends_on | `agents/modules/generated/l10n_ch.yaml` |
| `module.l10n_co_pos` | model_extended_by | `agents/modules/generated/l10n_co_pos.yaml` |
| `module.l10n_es_edi_verifactu_pos` | model_extended_by | `agents/modules/generated/l10n_es_edi_verifactu_pos.yaml` |
| `module.l10n_es_pos` | model_extended_by | `agents/modules/generated/l10n_es_pos.yaml` |
| `module.l10n_es_pos_tbai` | model_extended_by | `agents/modules/generated/l10n_es_pos_tbai.yaml` |
| `module.l10n_fr_pos_cert` | model_extended_by | `agents/modules/generated/l10n_fr_pos_cert.yaml` |
| `module.l10n_in_pos` | model_extended_by | `agents/modules/generated/l10n_in_pos.yaml` |
| `module.l10n_sa_pos` | model_extended_by | `agents/modules/generated/l10n_sa_pos.yaml` |
| `module.point_of_sale` | depends_on, extends_model_from | `agents/modules/generated/point_of_sale.yaml` |
| `module.pos_hr` | model_extended_by | `agents/modules/generated/pos_hr.yaml` |

## Full wiki excerpt

- SME owner: [`module.l10n_ch_pos`](../../../agents/modules/generated/l10n_ch_pos.yaml)
- Domain: `localization`
- Category: Accounting/Localizations/Point of Sale
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/l10n_ch_pos)
- Direct dependencies: [`l10n_ch`](../l10n_ch/overview.md), [`point_of_sale`](../point_of_sale/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: None
- Impact graph: [`module:l10n_ch_pos`](../../impact-graph.json)

## Purpose

No manifest summary supplied.

## Model relationships

- `pos.order` — extended by [`l10n_co_pos`](../l10n_co_pos/overview.md), [`l10n_es_edi_verifactu_pos`](../l10n_es_edi_verifactu_pos/overview.md), [`l10n_es_pos`](../l10n_es_pos/overview.md), [`l10n_es_pos_tbai`](../l10n_es_pos_tbai/overview.md), [`l10n_fr_pos_cert`](../l10n_fr_pos_cert/overview.md), [`l10n_in_pos`](../l10n_in_pos/overview.md), [`l10n_sa_pos`](../l10n_sa_pos/overview.md), [`pos_hr`](../pos_hr/overview.md), [`pos_loyalty`](../pos_loyalty/overview.md), [`pos_mercury`](../pos_mercury/overview.md), [`pos_mrp`](../pos_mrp/overview.md), [`pos_online_payment`](../pos_online_payment/overview.md), [`pos_online_payment_self_order`](../pos_online_payment_self_order/overview.md), [`pos_paytm`](../pos_paytm/overview.md), [`pos_razorpay`](../pos_razorpay/overview.md), [`pos_restaurant`](../pos_restaurant/overview.md), [`pos_restaurant_adyen`](../pos_restaurant_adyen/overview.md), [`pos_restaurant_stripe`](../pos_restaurant_stripe/overview.md), [`pos_sale`](../pos_sale/overview.md), [`pos_self_order`](../pos_self_order/overview.md)
- Extends `pos.order` — defined by [`point_of_sale`](../point_of_sale/overview.md)

## Related SME agents

- [`module.l10n_ch`](../../../agents/modules/generated/l10n_ch.yaml) — depends_on
- [`module.l10n_co_pos`](../../../agents/modules/generated/l10n_co_pos.yaml) — model_extended_by
- [`module.l10n_es_edi_verifactu_pos`](../../../agents/modules/generated/l10n_es_edi_verifactu_pos.yaml) — model_extended_by
- [`module.l10n_es_pos`](../../../agents/modules/generated/l10n_es_pos.yaml) — model_extended_by
- [`module.l10n_es_pos_tbai`](../../../agents/modules/generated/l10n_es_pos_tbai.yaml) — model_extended_by
- [`module.l10n_fr_pos_cert`](../../../agents/modules/generated/l10n_fr_pos_cert.yaml) — model_extended_by
- [`module.l10n_in_pos`](../../../agents/modules/generated/l10n_in_pos.yaml) — model_extended_by
- [`module.l10n_sa_pos`](../../../agents/modules/generated/l10n_sa_pos.yaml) — model_extended_by
- [`module.point_of_sale`](../../../agents/modules/generated/point_of_sale.yaml) — depends_on, extends_model_from
- [`module.pos_hr`](../../../agents/modules/generated/pos_hr.yaml) — model_extended_by
- [`module.pos_loyalty`](../../../agents/modules/generated/pos_loyalty.yaml) — model_extended_by
- [`module.pos_mercury`](../../../agents/modules/generated/pos_mercury.yaml) — model_extended_by
- [`module.pos_mrp`](../../../agents/modules/generated/pos_mrp.yaml) — model_extended_by
- [`module.pos_online_payment`](../../../agents/modules/generated/pos_online_payment.yaml) — model_extended_by
- [`module.pos_online_payment_self_order`](../../../agents/modules/generated/pos_online_payment_self_order.yaml) — model_extended_by
- [`module.pos_paytm`](../../../agents/modules/generated/pos_paytm.yaml) — model_extended_by
- [`module.pos_razorpay`](../../../agents/modules/generated/pos_razorpay.yaml) — model_extended_by
- [`module.pos_restaurant`](../../../agents/modules/generated/pos_restaurant.yaml) — model_extended_by
- [`module.pos_restaurant_adyen`](../../../agents/modules/generated/pos_restaurant_adyen.yaml) — model_extended_by
- [`module.pos_restaurant_stripe`](../../../agents/modules/generated/pos_restaurant_stripe.yaml) — model_extended_by
- [`module.pos_sale`](../../../agents/modules/generated/pos_sale.yaml) — model_extended_by
- [`module.pos_self_order`](../../../agents/modules/generated/pos_self_order.yaml) — model_extended_by

## Regression impact checklist

- Review 0 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`l10n_co_pos`](../l10n_co_pos/overview.md), [`l10n_es_edi_verifactu_pos`](../l10n_es_edi_verifactu_pos/overview.md), [`l10n_es_pos`](../l10n_es_pos/overview.md), [`l10n_es_pos_tbai`](../l10n_es_pos_tbai/overview.md), [`l10n_fr_pos_cert`](../l10n_fr_pos_cert/overview.md), [`l10n_in_pos`](../l10n_in_pos/overview.md), [`l10n_sa_pos`](../l10n_sa_pos/overview.md), [`pos_hr`](../pos_hr/overview.md), [`pos_loyalty`](../pos_loyalty/overview.md), [`pos_mercury`](../pos_mercury/overview.md), [`pos_mrp`](../pos_mrp/overview.md), [`pos_online_payment`](../pos_online_payment/overview.md), [`pos_online_payment_self_order`](../pos_online_payment_self_order/overview.md), [`pos_paytm`](../pos_paytm/overview.md), [`pos_razorpay`](../pos_razorpay/overview.md), [`pos_restaurant`](../pos_restaurant/overview.md), [`pos_restaurant_adyen`](../pos_restaurant_adyen/overview.md), [`pos_restaurant_stripe`](../pos_restaurant_stripe/overview.md), [`pos_sale`](../pos_sale/overview.md), [`pos_self_order`](../pos_self_order/overview.md).
- Review model owners used by this module: [`point_of_sale`](../point_of_sale/overview.md).
- Required specialist reviewers: module owner and QA.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
