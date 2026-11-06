# AFTERCOSTS — Know what your store keeps.

**A private, browser-side Shopify CSV profit-close studio for independent ecommerce merchants.**

[**Open the free AfterCosts tool**](https://aftercosts.jebraeili-nima.workers.dev/?utm_source=github) · [Profit-close guide](https://aftercosts.jebraeili-nima.workers.dev/guides/shopify-csv-profit-without-double-counting) · [Refund-timing guide](https://aftercosts.jebraeili-nima.workers.dev/guides/shopify-refund-dates-order-csv-vs-transactions)

AfterCosts helps store owners estimate what remains after refunds, mapped product costs, payment fees, merchant-paid shipping, advertising and overhead. Import your own Shopify Orders CSV **locally in your browser** and review missing-cost warnings and assumptions.

> **Important:** AfterCosts is independent of Shopify and is not an official Shopify App Store integration. It does not fetch live orders, reconcile bank payouts, provide certified accounting or tax advice, or guarantee financial outcomes. All results are management estimates based on data and assumptions you provide.

## Features available to try

- Import exported Shopify Orders CSVs, including orders with multiple line items.
- Avoid double-counting the same order-level total across line-item rows.
- Map known unit costs by SKU and flag missing cost coverage.
- Review refunds and a refund-date timing bridge where transaction exports are supplied.
- Model payment-processing and fulfillment fees with editable assumptions.
- Include period advertising and overhead to estimate order contribution.
- Download redacted reports and print results locally.

The **free web evaluation contains the core calculation features**. An **optional $29 one-time offline kit** provides a portable HTML copy and companion templates, with overlapping functionality. This is *not* a monthly subscription or account-bound paid SaaS. The checkout delivery link is shareable. [**View the optional $29 offline kit checkout**](https://aftercosts.jebraeili-nima.workers.dev/go/offline-kit?utm_source=github) (limited to 10 completed purchases; availability is shown at checkout).

## We are inviting 3 Shopify merchant testers

Have a weekly Shopify spreadsheet? [See the open early-tester invitation](https://github.com/jh69fc845n-a11y/aftercosts/issues/1). The free tool runs locally in your browser; please **do not share actual customer CSVs or sensitive order information**. We want candid feedback, not paid endorsements.

## Try with fictional data

1. [Open the web application](https://aftercosts.jebraeili-nima.workers.dev/?utm_source=github) and use its explicitly fictional demonstration figures.
2. Explore the synthetic CSV samples in [examples/](examples/).
3. Export your own Orders CSV from Shopify for one reporting window and currency.
4. Enter relevant SKU costs, fees, shipping, advertising and overhead for that same period.
5. Review data completeness before relying on the calculated estimates.

**Privacy:** CSV processing takes place inside your browser rather than uploading the order or cost files to our server. If you separately submit the opt-in enquiry form, the contact details you provide are stored to respond to your enquiry. See our [privacy policy](https://aftercosts.jebraeili-nima.workers.dev/privacy).

## Practical guides

- [Calculate Shopify profit from CSV without double-counting orders](https://aftercosts.jebraeili-nima.workers.dev/guides/shopify-csv-profit-without-double-counting)
- [Shopify refund processing dates vs order dates](https://aftercosts.jebraeili-nima.workers.dev/guides/shopify-refund-dates-order-csv-vs-transactions)
- [SKU contribution after refunds, fees and advertising](https://aftercosts.jebraeili-nima.workers.dev/guides/shopify-sku-contribution-after-refunds-fees-ad-spend)
- [Weekly reconciliation checklist](docs/reconciliation-checklist.md)
- [FAQ](docs/faq.md)

## Known limitations

- Historical unit costs must be entered and verified by the merchant; unmapped costs can overstate contribution.
- Tax impacts of partial refunds, card fees and SKU-level expense allocation are approximations.
- Multi-currency and historical cost changes may need additional reconciliation.
- Settlement payouts are not equivalent to order-level contribution.
- No Shopify API integration, automated bookkeeping, audit, tax output or guaranteed financial return.

## Feedback and security

We're seeking candid feedback from merchants who currently reconcile weekly profit in spreadsheets. GitHub Issues may be used for reproducible feature requests or bug reports **using synthetic, non-sensitive data only**.

For billing or private matters, contact **jebinima43@gmail.com**. **Never post customer CSVs, personal details, credentials, financial records or private purchase links in public issues.**

## Repository scope

This repository publishes **documentation and fictional examples only**. It does not include the proprietary offline application, payment delivery links, production keys, private merchant records or buyer data.

Shopify is a trademark of its respective owner and is referenced descriptively; no endorsement or affiliation is implied.
