# Codat (codat-io)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Codat provides a business data API that connects small-business accounting, banking, and commerce platforms to lenders, fintechs, and B2B software providers. A single integration to `api.codat.io` standardizes data from QuickBooks, Xero, Sage, NetSuite, FreshBooks, and 30+ other systems - and can write bills, payments, and expenses back into them - powering underwriting, reconciliation, payables, and spend products.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/codat-io/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/codat-io/refs/heads/main/apis.yml)

Authentication is your Codat API key, Base64-encoded and sent in an `Authorization: Basic` header.

## Tags

- Business Data
- Accounting
- Banking
- Commerce
- Fintech
- Lending
- Financial Data

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Codat Platform API

Core control plane for managing companies, data connections, refreshing and tracking pulled datasets, integrations, webhook consumers, API keys, and account settings across every Codat data product.

- **Human URL:** [https://docs.codat.io/platform-api](https://docs.codat.io/platform-api)
- **Base URL:** `https://api.codat.io`

#### Tags

- Companies
- Connections
- Webhooks
- Integrations

#### Properties

- [Documentation](https://docs.codat.io/platform-api)
- [API Reference](https://docs.codat.io/platform-api)
- [OpenAPI](openapi/codat-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/codat-io.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/codat-io.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Codat Accounting API

Standardized read (and, for supported platforms, write) access to accounting data - accounts, chart of accounts, invoices, bills, bill payments, credit notes, customers, suppliers, payments, journal entries, journals, direct costs/incomes, transfers, and financial statement reports (balance sheet, profit and loss, cash flow).

- **Human URL:** [https://docs.codat.io/accounting-api](https://docs.codat.io/accounting-api)
- **Base URL:** `https://api.codat.io`

#### Tags

- Accounting
- Invoices
- Bills
- Journal Entries
- Chart of Accounts

#### Properties

- [Documentation](https://docs.codat.io/accounting-api)
- [API Reference](https://docs.codat.io/accounting-api)
- [OpenAPI](openapi/codat-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Codat Banking API

Standardized banking data pulled from connected bank and accounting platforms - bank accounts, account balances, bank transactions, and transaction categories - for reconciliation and cash-flow analysis.

- **Human URL:** [https://docs.codat.io/banking-api](https://docs.codat.io/banking-api)
- **Base URL:** `https://api.codat.io`

#### Tags

- Banking
- Bank Accounts
- Transactions
- Balances

#### Properties

- [Documentation](https://docs.codat.io/banking-api)
- [API Reference](https://docs.codat.io/banking-api)
- [OpenAPI](openapi/codat-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Codat Commerce API

Standardized commerce and point-of-sale data from platforms such as Shopify, Square, and Stripe - customers, orders, payments, products, disputes, locations, and company info - for merchant underwriting and revenue analysis.

- **Human URL:** [https://docs.codat.io/commerce-api](https://docs.codat.io/commerce-api)
- **Base URL:** `https://api.codat.io`

#### Tags

- Commerce
- Orders
- Payments
- Products

#### Properties

- [Documentation](https://docs.codat.io/commerce-api)
- [API Reference](https://docs.codat.io/commerce-api)
- [OpenAPI](openapi/codat-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Codat Lending API

Purpose-built lending product combining standardized financial data with Assess features - enhanced/categorized balance sheet and profit-and-loss reports, financial metrics, accounts receivable/payable, loan summaries, and data-integrity checks - for automated SMB underwriting.

- **Human URL:** [https://docs.codat.io/lending-api](https://docs.codat.io/lending-api)
- **Base URL:** `https://api.codat.io`

#### Tags

- Lending
- Assess
- Underwriting
- Financial Metrics

#### Properties

- [Documentation](https://docs.codat.io/lending-api)
- [API Reference](https://docs.codat.io/lending-api)
- [OpenAPI](openapi/codat-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Codat Bank Feeds API

Lets card issuers and neobanks push transaction data as a bank feed into customers' accounting platforms, creating and mapping bank/source accounts so transactions appear ready for reconciliation.

- **Human URL:** [https://docs.codat.io/bank-feeds-api](https://docs.codat.io/bank-feeds-api)
- **Base URL:** `https://api.codat.io`

#### Tags

- Bank Feeds
- Bank Accounts
- Reconciliation

#### Properties

- [Documentation](https://docs.codat.io/bank-feeds-api)
- [API Reference](https://docs.codat.io/bank-feeds-api)
- [OpenAPI](openapi/codat-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Codat Sync for Payables API

Write bills, suppliers, bill payments, and bank accounts back into a customer's accounting platform, with mapping options - the engine behind accounts-payable and bill-pay automation products.

- **Human URL:** [https://docs.codat.io/sync-for-payables-api](https://docs.codat.io/sync-for-payables-api)
- **Base URL:** `https://api.codat.io`

#### Tags

- Payables
- Bills
- Suppliers
- Bill Payments

#### Properties

- [Documentation](https://docs.codat.io/sync-for-payables-api)
- [API Reference](https://docs.codat.io/sync-for-payables-api)
- [OpenAPI](openapi/codat-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Codat Sync for Expenses API

Reconcile card and expense transactions into a customer's accounting software - create expense, reimbursable, and transfer transactions, run syncs, track sync/transaction status, upload attachments, and fetch mapping options.

- **Human URL:** [https://docs.codat.io/sync-for-expenses-api](https://docs.codat.io/sync-for-expenses-api)
- **Base URL:** `https://api.codat.io`

#### Tags

- Expenses
- Spend
- Reconciliation

#### Properties

- [Documentation](https://docs.codat.io/sync-for-expenses-api)
- [API Reference](https://docs.codat.io/sync-for-expenses-api)
- [OpenAPI](openapi/codat-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Codat Sync for Commerce API

Turnkey product that syncs sales, payments, and fees from commerce and POS platforms into accounting software, with sync configuration, status, and supported-integration discovery.

- **Human URL:** [https://docs.codat.io/sync-for-commerce-api](https://docs.codat.io/sync-for-commerce-api)
- **Base URL:** `https://api.codat.io`

#### Tags

- Commerce
- Sync
- Reconciliation

#### Properties

- [Documentation](https://docs.codat.io/sync-for-commerce-api)
- [API Reference](https://docs.codat.io/sync-for-commerce-api)
- [OpenAPI](openapi/codat-io-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [GitHub Organization](https://github.com/codatio)
- [LinkedIn](https://www.linkedin.com/company/codat)
- [Website](https://www.codat.io)
- [Documentation](https://docs.codat.io)
- [Plans](plans/codat-io-plans-pricing.yml)
- [Rate Limits](rate-limits/codat-io-rate-limits.yml)
- [Fin Ops](finops/codat-io-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
