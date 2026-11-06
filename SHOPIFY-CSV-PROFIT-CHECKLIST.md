# Shopify CSV profit reconciliation: a practical checklist

This educational checklist is for store owners comparing Shopify order exports with actual costs. It is not accounting, tax, or audit advice.

## Before calculating
- Pick a reporting period and decide whether you're measuring order-date sales or cash/refund activity in the period. Do not mix the two silently.
- Keep original exports intact. Work on copies and remove customer-identifying columns before sharing examples.
- Verify the CSV's row grain: an order may appear on multiple line-item rows. Do **not** sum repeated order-level totals once per item.
- Document currencies, time zones, tax handling, and whether shipping charged to buyers is included in revenue.

## Reconciliation sequence
1. **Sales:** Start with an agreed revenue definition; separate product sales, discounts, taxes collected, and shipping charged.
2. **Refunds and returns:** Match refunds to orders and dates. Distinguish returned merchandise from refunded shipping/tax and note fees that are not returned.
3. **COGS:** Use SKU-level unit cost *at the time of sale* where available. Today's catalog cost may not represent historical cost. Flag missing or changing costs rather than guessing.
4. **Processing fees:** Reconcile actual payment processor charges and nonrefunded fees. A flat percentage estimate is only an estimate.
5. **Fulfillment:** Account for merchant-paid shipping, packaging, and fulfillment charges without double-counting costs already embedded in supplier invoices.
6. **Advertising:** Compare the same period's ad spend and document how shared campaign spend is allocated; attribution reports are not accounting records.
7. **Exceptions:** Review canceled orders, partial fulfillments, exchanges, gift cards, multi-currency orders, chargebacks, and marketplace fees separately.

## Illustrative fictional example (USD)
- Net merchandise revenue after discounts and merchandise refunds: $1,000
- Historical merchandise COGS: $420
- Payment processing fees: $35
- Merchant-paid fulfillment and packaging: $90
- Advertising spend: $180
- **Illustrative contribution after listed costs: $275**

This is **not** net business profit: payroll, rent, software, taxes, overhead, chargebacks, and other costs may still apply. Real CSV exports can contain duplicated order totals and inconsistent timing, so validate every mapping.

## Free browser-side tool
[AFTERCOSTS — Know what your store keeps](https://aftercosts.jebraeili-nima.workers.dev/?utm_source=github&utm_medium=guide) offers a free browser-only Shopify CSV profit reconciliation workflow. It does not connect directly to Shopify and does not replace bookkeeping or an accountant. Review its supported inputs and outputs before relying on an estimate; no customer CSV needs to be sent to us.

There is also an **optional $29 founding-edition offline kit** with portable local files. The free website has overlapping functionality. After payment, delivery uses a **shareable private bearer link**, not account-bound or webhook-verified licensing. No future upgrades or savings are promised. [Offline kit details](https://aftercosts.jebraeili-nima.workers.dev/go/offline-kit?utm_source=github&utm_medium=guide).
