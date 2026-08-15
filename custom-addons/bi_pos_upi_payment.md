---
layout: custom-page
title: "bi_pos_upi_payment (bi_pos_upi_payment)"
subtitle: "Custom addon — RetailEnterprise/Store/bi_pos_upi_payment"
permalink: /custom-addons/bi_pos_upi_payment/
nav_order: 0
nav_title: "bi_pos_upi_payment"
---
# bi_pos_upi_payment

<div class="meta-grid">
<div class="meta-card"><div class="k">Technical name</div><div class="v"><code>bi_pos_upi_payment</code></div></div>
<div class="meta-card"><div class="k">Path</div><div class="v"><code>RetailEnterprise/Store/bi_pos_upi_payment</code></div></div>
<div class="meta-card"><div class="k">Version</div><div class="v"></div></div>
<div class="meta-card"><div class="k">License</div><div class="v"></div></div>
<div class="meta-card"><div class="k">Depends</div><div class="v"><em>—</em></div></div>
</div>

## Description

BI POS UPI Payment — UPI/QR payment terminal integration at POS.

> **Deployment target:** Store.

## Manifest excerpt

```python
# -*- coding: utf-8 -*-
# Part of BrowseInfo. See LICENSE file for full copyright and licensing details.

{
	'name': 'POS Payment UPI',
	'version': '17.0.0.0',
	'category': 'Point Of Sale',
	'summary': 'Create UPI QR code from POS Multiple UPI Payment Methods Point of Sale UPI Payment Integration Auto POS Order UPI Scan with QR code Scan with Payment UPI in POS Payment with UPI Payment Point of Sales Pay UPI Payment Solutions POS UPI payment POS QR Code',
	'description' :"""Point of Sale UPI Payment Odoo App empowers businesses to seamlessly incorporate UPI payments into their POS operations, ensuring a streamlined and contemporary payment experience for customers. With this app users can configure multiple UPI payment options and allow users to scan and pay from point of sale directly using selected UPI payment option.""",
	'author': 'BrowseInfo',
	'website': 'https://www.browseinfo.com',
	"price": 49,
	"currency": 'EUR',
	'depends': ['base','point_of_sale'],
	'data': [
		'security/ir.model.access.csv',
		'views/pos_view.xml',
	],
	'assets': {
		'point_of_sale._assets_pos': [
			'bi_pos_upi_payment/static/src/js/model.js',
			'bi_pos_upi_payment/static/src/js/PaymentScreen.js',
			'bi_pos_upi_payment/static/src/js/UPIQRPopup.js',
            'bi_pos_upi_payment/static/src/xml/pos.xml',
			'bi_pos_upi_payment/static/src/css/paymentmethod_highlight.scss',
		],
	},
	'license':'OPL-1',
	'demo': [],
	'test': [],
	'installable': True,
	'auto_install': False,
	'live_test_url':'https://youtu.be/VFVAO2NRJg4',
	"images":['static/description/POS-UPI-Payment.gif'],
}
```
