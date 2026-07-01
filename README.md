# Codat (codat-io)

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
