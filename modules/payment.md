---
layout: page
title: "Payment Engine (payment)"
subtitle: "Odoo 17 module profile — owner, dependencies, models, learnings."
permalink: /modules/payment/
nav_order: 0
---
# Payment Engine — `payment`

**Source:** [`agents/modules/generated/payment.yaml`](../../agents/modules/generated/payment.yaml) · **Wiki:** [`knowledge/modules/payment/overview.md`](../../knowledge/modules/payment/overview.md)

<div class="meta-grid">
<div class="meta-card"><div class="k">Module</div><div class="v"><code>payment</code></div></div>
<div class="meta-card"><div class="k">Title</div><div class="v">Payment Engine</div></div>
<div class="meta-card"><div class="k">Domain</div><div class="v">accounting</div></div>
<div class="meta-card"><div class="k">Application</div><div class="v">False</div></div>
<div class="meta-card"><div class="k">License</div><div class="v">LGPL-3</div></div>
<div class="meta-card"><div class="k">Source path</div><div class="v"><code>addons/payment</code></div></div>
<div class="meta-card"><div class="k">Upstream revision</div><div class="v"><a href="https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/payment"><code>126b5bd</code></a></div></div>
</div>
## Purpose

The payment engine used by payment provider modules.

## Direct dependencies

[`onboarding`](onboarding.md), [`portal`](portal.md)

## Reverse dependencies (modules that depend on this)

[`account_payment`](account_payment.md), [`payment_adyen`](payment_adyen.md), [`payment_alipay`](payment_alipay.md), [`payment_aps`](payment_aps.md), [`payment_asiapay`](payment_asiapay.md), [`payment_authorize`](payment_authorize.md), [`payment_buckaroo`](payment_buckaroo.md), [`payment_custom`](payment_custom.md), [`payment_demo`](payment_demo.md), [`payment_flutterwave`](payment_flutterwave.md), [`payment_mercado_pago`](payment_mercado_pago.md), [`payment_mollie`](payment_mollie.md), [`payment_ogone`](payment_ogone.md), [`payment_paypal`](payment_paypal.md), [`payment_payulatam`](payment_payulatam.md), [`payment_payumoney`](payment_payumoney.md), [`payment_razorpay`](payment_razorpay.md), [`payment_sips`](payment_sips.md), [`payment_stripe`](payment_stripe.md), [`payment_worldline`](payment_worldline.md), [`payment_xendit`](payment_xendit.md)

## Models defined by this module

<div class="model-list">
<div class="model"><div class="name"><code>payment.capture.wizard</code></div><div class="role">defined by <code>payment</code></div></div>
<div class="model"><div class="name"><code>payment.link.wizard</code></div><div class="role">defined by <code>payment</code></div></div>
<div class="model"><div class="name"><code>payment.method</code></div><div class="role">defined by <code>payment</code></div></div>
<div class="model"><div class="name"><code>payment.provider</code></div><div class="role">defined by <code>payment</code></div></div>
<div class="model"><div class="name"><code>payment.provider.onboarding.wizard</code></div><div class="role">defined by <code>payment</code></div></div>
<div class="model"><div class="name"><code>payment.token</code></div><div class="role">defined by <code>payment</code></div></div>
<div class="model"><div class="name"><code>payment.transaction</code></div><div class="role">defined by <code>payment</code></div></div>
</div>

## Models extended by this module

<div class="model-list">
<div class="model"><div class="name"><code>ir.http</code></div><div class="role">extended by <code>payment</code></div></div>
<div class="model"><div class="name"><code>onboarding.onboarding.step</code></div><div class="role">extended by <code>payment</code></div></div>
<div class="model"><div class="name"><code>res.company</code></div><div class="role">extended by <code>payment</code></div></div>
<div class="model"><div class="name"><code>res.partner</code></div><div class="role">extended by <code>payment</code></div></div>
</div>

## Related SME agents (top 10)

| Agent | Relationships | Profile |
|---|---|---|
| `module.account` | extends_model_from | `agents/modules/generated/account.yaml` |
| `module.account_payment` | model_extended_by, required_by | `agents/modules/generated/account_payment.yaml` |
| `module.base` | extends_model_from | `agents/modules/generated/base.yaml` |
| `module.crm` | extends_model_from | `agents/modules/generated/crm.yaml` |
| `module.l10n_cl` | extends_model_from | `agents/modules/generated/l10n_cl.yaml` |
| `module.l10n_ec_website_sale` | model_extended_by | `agents/modules/generated/l10n_ec_website_sale.yaml` |
| `module.l10n_it_edi` | extends_model_from | `agents/modules/generated/l10n_it_edi.yaml` |
| `module.l10n_sg` | extends_model_from | `agents/modules/generated/l10n_sg.yaml` |
| `module.l10n_tr_nilvera` | extends_model_from | `agents/modules/generated/l10n_tr_nilvera.yaml` |
| `module.mail` | extends_model_from | `agents/modules/generated/mail.yaml` |

## Full wiki excerpt

- SME owner: [`module.payment`](../../../agents/modules/generated/payment.yaml)
- Domain: `accounting`
- Category: Hidden
- Source revision: [`126b5bdd1e85`](https://github.com/odoo/odoo/tree/126b5bdd1e85771549198976f8570cd2ff167608/addons/payment)
- Direct dependencies: [`onboarding`](../onboarding/overview.md), [`portal`](../portal/overview.md)
- Declared license: `LGPL-3`; architecture review: [`platform.licensing-commercial-boundaries`](../../base-platform/licensing-commercial-boundaries.md)
- Reverse dependencies: [`account_payment`](../account_payment/overview.md), [`payment_adyen`](../payment_adyen/overview.md), [`payment_alipay`](../payment_alipay/overview.md), [`payment_aps`](../payment_aps/overview.md), [`payment_asiapay`](../payment_asiapay/overview.md), [`payment_authorize`](../payment_authorize/overview.md), [`payment_buckaroo`](../payment_buckaroo/overview.md), [`payment_custom`](../payment_custom/overview.md), [`payment_demo`](../payment_demo/overview.md), [`payment_flutterwave`](../payment_flutterwave/overview.md), [`payment_mercado_pago`](../payment_mercado_pago/overview.md), [`payment_mollie`](../payment_mollie/overview.md), [`payment_ogone`](../payment_ogone/overview.md), [`payment_paypal`](../payment_paypal/overview.md), [`payment_payulatam`](../payment_payulatam/overview.md), [`payment_payumoney`](../payment_payumoney/overview.md), [`payment_razorpay`](../payment_razorpay/overview.md), [`payment_sips`](../payment_sips/overview.md), [`payment_stripe`](../payment_stripe/overview.md), [`payment_worldline`](../payment_worldline/overview.md), [`payment_xendit`](../payment_xendit/overview.md)
- Impact graph: [`module:payment`](../../impact-graph.json)

## Purpose

The payment engine used by payment provider modules.

## Model relationships

- `payment.capture.wizard` — extended by [`payment_adyen`](../payment_adyen/overview.md)
- `payment.link.wizard` — extended by [`account_payment`](../account_payment/overview.md), [`sale`](../sale/overview.md)
- `payment.method` — extended by [`l10n_ec_website_sale`](../l10n_ec_website_sale/overview.md)
- `payment.provider` — extended by [`account_payment`](../account_payment/overview.md), [`payment_adyen`](../payment_adyen/overview.md), [`payment_alipay`](../payment_alipay/overview.md), [`payment_aps`](../payment_aps/overview.md), [`payment_asiapay`](../payment_asiapay/overview.md), [`payment_authorize`](../payment_authorize/overview.md), [`payment_buckaroo`](../payment_buckaroo/overview.md), [`payment_custom`](../payment_custom/overview.md), [`payment_demo`](../payment_demo/overview.md), [`payment_flutterwave`](../payment_flutterwave/overview.md), [`payment_mercado_pago`](../payment_mercado_pago/overview.md), [`payment_mollie`](../payment_mollie/overview.md), [`payment_ogone`](../payment_ogone/overview.md), [`payment_paypal`](../payment_paypal/overview.md), [`payment_payulatam`](../payment_payulatam/overview.md), [`payment_payumoney`](../payment_payumoney/overview.md), [`payment_razorpay`](../payment_razorpay/overview.md), [`payment_razorpay_oauth`](../payment_razorpay_oauth/overview.md), [`payment_sips`](../payment_sips/overview.md), [`payment_stripe`](../payment_stripe/overview.md), [`payment_worldline`](../payment_worldline/overview.md), [`payment_xendit`](../payment_xendit/overview.md), [`sale`](../sale/overview.md), [`website_payment`](../website_payment/overview.md), [`website_sale_picking`](../website_sale_picking/overview.md)
- `payment.provider.onboarding.wizard` — extended by [`sale`](../sale/overview.md)
- `payment.token` — extended by [`payment_adyen`](../payment_adyen/overview.md), [`payment_authorize`](../payment_authorize/overview.md), [`payment_demo`](../payment_demo/overview.md), [`payment_flutterwave`](../payment_flutterwave/overview.md), [`payment_ogone`](../payment_ogone/overview.md), [`payment_stripe`](../payment_stripe/overview.md), [`website_sale`](../website_sale/overview.md)
- `payment.transaction` — extended by [`account_payment`](../account_payment/overview.md), [`payment_adyen`](../payment_adyen/overview.md), [`payment_alipay`](../payment_alipay/overview.md), [`payment_aps`](../payment_aps/overview.md), [`payment_asiapay`](../payment_asiapay/overview.md), [`payment_authorize`](../payment_authorize/overview.md), [`payment_buckaroo`](../payment_buckaroo/overview.md), [`payment_custom`](../payment_custom/overview.md), [`payment_demo`](../payment_demo/overview.md), [`payment_flutterwave`](../payment_flutterwave/overview.md), [`payment_mercado_pago`](../payment_mercado_pago/overview.md), [`payment_mollie`](../payment_mollie/overview.md), [`payment_ogone`](../payment_ogone/overview.md), [`payment_paypal`](../payment_paypal/overview.md), [`payment_payulatam`](../payment_payulatam/overview.md), [`payment_payumoney`](../payment_payumoney/overview.md), [`payment_razorpay`](../payment_razorpay/overview.md), [`payment_sips`](../payment_sips/overview.md), [`payment_stripe`](../payment_stripe/overview.md), [`payment_worldline`](../payment_worldline/overview.md), [`payment_xendit`](../payment_xendit/overview.md), [`pos_online_payment`](../pos_online_payment/overview.md), [`sale`](../sale/overview.md), [`website_payment`](../website_payment/overview.md)
- Extends `ir.http` — defined by [`base`](../base/overview.md)
- Extends `onboarding.onboarding.step` — defined by [`onboarding`](../onboarding/overview.md)
- Extends `res.company` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md)
- Extends `res.partner` — defined by [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md)

## Related SME agents

- [`module.account`](../../../agents/modules/generated/account.yaml) — extends_model_from
- [`module.account_payment`](../../../agents/modules/generated/account_payment.yaml) — model_extended_by, required_by
- [`module.base`](../../../agents/modules/generated/base.yaml) — extends_model_from
- [`module.crm`](../../../agents/modules/generated/crm.yaml) — extends_model_from
- [`module.l10n_cl`](../../../agents/modules/generated/l10n_cl.yaml) — extends_model_from
- [`module.l10n_ec_website_sale`](../../../agents/modules/generated/l10n_ec_website_sale.yaml) — model_extended_by
- [`module.l10n_it_edi`](../../../agents/modules/generated/l10n_it_edi.yaml) — extends_model_from
- [`module.l10n_sg`](../../../agents/modules/generated/l10n_sg.yaml) — extends_model_from
- [`module.l10n_tr_nilvera`](../../../agents/modules/generated/l10n_tr_nilvera.yaml) — extends_model_from
- [`module.mail`](../../../agents/modules/generated/mail.yaml) — extends_model_from
- [`module.onboarding`](../../../agents/modules/generated/onboarding.yaml) — depends_on, extends_model_from
- [`module.partner_autocomplete`](../../../agents/modules/generated/partner_autocomplete.yaml) — extends_model_from
- [`module.payment_adyen`](../../../agents/modules/generated/payment_adyen.yaml) — model_extended_by, required_by
- [`module.payment_alipay`](../../../agents/modules/generated/payment_alipay.yaml) — model_extended_by, required_by
- [`module.payment_aps`](../../../agents/modules/generated/payment_aps.yaml) — model_extended_by, required_by
- [`module.payment_asiapay`](../../../agents/modules/generated/payment_asiapay.yaml) — model_extended_by, required_by
- [`module.payment_authorize`](../../../agents/modules/generated/payment_authorize.yaml) — model_extended_by, required_by
- [`module.payment_buckaroo`](../../../agents/modules/generated/payment_buckaroo.yaml) — model_extended_by, required_by
- [`module.payment_custom`](../../../agents/modules/generated/payment_custom.yaml) — model_extended_by, required_by
- [`module.payment_demo`](../../../agents/modules/generated/payment_demo.yaml) — model_extended_by, required_by
- [`module.payment_flutterwave`](../../../agents/modules/generated/payment_flutterwave.yaml) — model_extended_by, required_by
- [`module.payment_mercado_pago`](../../../agents/modules/generated/payment_mercado_pago.yaml) — model_extended_by, required_by
- [`module.payment_mollie`](../../../agents/modules/generated/payment_mollie.yaml) — model_extended_by, required_by
- [`module.payment_ogone`](../../../agents/modules/generated/payment_ogone.yaml) — model_extended_by, required_by
- [`module.payment_paypal`](../../../agents/modules/generated/payment_paypal.yaml) — model_extended_by, required_by
- [`module.payment_payulatam`](../../../agents/modules/generated/payment_payulatam.yaml) — model_extended_by, required_by
- [`module.payment_payumoney`](../../../agents/modules/generated/payment_payumoney.yaml) — model_extended_by, required_by
- [`module.payment_razorpay`](../../../agents/modules/generated/payment_razorpay.yaml) — model_extended_by, required_by
- [`module.payment_razorpay_oauth`](../../../agents/modules/generated/payment_razorpay_oauth.yaml) — model_extended_by
- [`module.payment_sips`](../../../agents/modules/generated/payment_sips.yaml) — model_extended_by, required_by
- [`module.payment_stripe`](../../../agents/modules/generated/payment_stripe.yaml) — model_extended_by, required_by
- [`module.payment_worldline`](../../../agents/modules/generated/payment_worldline.yaml) — model_extended_by, required_by
- [`module.payment_xendit`](../../../agents/modules/generated/payment_xendit.yaml) — model_extended_by, required_by
- [`module.phone_validation`](../../../agents/modules/generated/phone_validation.yaml) — extends_model_from
- [`module.portal`](../../../agents/modules/generated/portal.yaml) — depends_on
- [`module.pos_online_payment`](../../../agents/modules/generated/pos_online_payment.yaml) — model_extended_by
- [`module.purchase`](../../../agents/modules/generated/purchase.yaml) — extends_model_from
- [`module.sale`](../../../agents/modules/generated/sale.yaml) — model_extended_by
- [`module.sms`](../../../agents/modules/generated/sms.yaml) — extends_model_from
- [`module.test_access_rights`](../../../agents/modules/generated/test_access_rights.yaml) — extends_model_from
- [`module.website`](../../../agents/modules/generated/website.yaml) — extends_model_from
- [`module.website_partner`](../../../agents/modules/generated/website_partner.yaml) — extends_model_from
- [`module.website_payment`](../../../agents/modules/generated/website_payment.yaml) — model_extended_by
- [`module.website_sale`](../../../agents/modules/generated/website_sale.yaml) — model_extended_by
- [`module.website_sale_picking`](../../../agents/modules/generated/website_sale_picking.yaml) — model_extended_by

## Regression impact checklist

- Review 21 direct dependent module(s) and bounded transitive dependents in `knowledge/impact-index.json`.
- Review modules extending owned models: [`account_payment`](../account_payment/overview.md), [`l10n_ec_website_sale`](../l10n_ec_website_sale/overview.md), [`payment_adyen`](../payment_adyen/overview.md), [`payment_alipay`](../payment_alipay/overview.md), [`payment_aps`](../payment_aps/overview.md), [`payment_asiapay`](../payment_asiapay/overview.md), [`payment_authorize`](../payment_authorize/overview.md), [`payment_buckaroo`](../payment_buckaroo/overview.md), [`payment_custom`](../payment_custom/overview.md), [`payment_demo`](../payment_demo/overview.md), [`payment_flutterwave`](../payment_flutterwave/overview.md), [`payment_mercado_pago`](../payment_mercado_pago/overview.md), [`payment_mollie`](../payment_mollie/overview.md), [`payment_ogone`](../payment_ogone/overview.md), [`payment_paypal`](../payment_paypal/overview.md), [`payment_payulatam`](../payment_payulatam/overview.md), [`payment_payumoney`](../payment_payumoney/overview.md), [`payment_razorpay`](../payment_razorpay/overview.md), [`payment_razorpay_oauth`](../payment_razorpay_oauth/overview.md), [`payment_sips`](../payment_sips/overview.md), [`payment_stripe`](../payment_stripe/overview.md), [`payment_worldline`](../payment_worldline/overview.md), [`payment_xendit`](../payment_xendit/overview.md), [`pos_online_payment`](../pos_online_payment/overview.md), [`sale`](../sale/overview.md), [`website_payment`](../website_payment/overview.md), [`website_sale`](../website_sale/overview.md), [`website_sale_picking`](../website_sale_picking/overview.md).
- Review model owners used by this module: [`account`](../account/overview.md), [`base`](../base/overview.md), [`crm`](../crm/overview.md), [`l10n_cl`](../l10n_cl/overview.md), [`l10n_it_edi`](../l10n_it_edi/overview.md), [`l10n_sg`](../l10n_sg/overview.md), [`l10n_tr_nilvera`](../l10n_tr_nilvera/overview.md), [`mail`](../mail/overview.md), [`onboarding`](../onboarding/overview.md), [`partner_autocomplete`](../partner_autocomplete/overview.md), [`phone_validation`](../phone_validation/overview.md), [`purchase`](../purchase/overview.md), [`sms`](../sms/overview.md), [`test_access_rights`](../test_access_rights/overview.md), [`website`](../website/overview.md), [`website_partner`](../website_partner/overview.md).
- Required specialist reviewers: security_reviewer, security_reviewer, frontend_owl.
- Run this module’s tests plus affected downstream tests before upgrade.

## Learnings

Canonical learnings live in [`learnings.yaml`](learnings.yaml). Cross-wiki relationships use stable module and learning IDs.
