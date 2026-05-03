# Upvest (upvest)
Upvest is a Berlin-based API-first investment infrastructure provider that enables banks, brokers, and wealth managers to build and launch investment experiences through a single modular API. Founded in 2017, Upvest is a regulated securities institution in Europe and the UK, covering trading, custody, and back-office operations. The platform supports fractional investing, portfolios, savings plans, roundups, and direct debit, enabling clients like Bunq, DKB, N26, Revolut, and Raisin to offer investment products to their customers.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/upvest/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Banking Infrastructure, Fintech, Investments, Securities, Fractional Investing, Custody, Wealth Management

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-03

## APIs

### Upvest Investment API
The Upvest Investment API provides a unified interface for building embedded investment experiences. It supports placing and managing orders, creating portfolios, configuring savings plans, handling securities transfers, and managing user accounts and positions. The API covers the full order lifecycle with asynchronous processing and webhook notifications for real-time event handling.

**Human URL:** [https://docs.upvest.co/](https://docs.upvest.co/)

#### Tags:

 - Custody, Investments, Orders, Portfolios, Securities, Trading, Fractional Investing, Savings Plans, Payments, Webhooks

#### Properties

- [Documentation](https://docs.upvest.co/api)
- [OpenAPI](openapi/upvest-investment-api-openapi.yml)
- [AsyncAPI](asyncapi/upvest-investment-events-asyncapi.yml)
- [JSONSchema - User](json-schema/investment-api-user-schema.json)
- [JSONSchema - Account](json-schema/investment-api-account-schema.json)
- [JSONSchema - Order](json-schema/investment-api-order-schema.json)
- [JSONSchema - Portfolio](json-schema/investment-api-portfolio-schema.json)
- [JSONSchema - Savings Plan](json-schema/investment-api-savings-plan-schema.json)
- [JSONSchema - Instrument](json-schema/investment-api-instrument-schema.json)
- [JSONSchema - Transaction](json-schema/investment-api-transaction-schema.json)
- [JSONSchema - Position](json-schema/investment-api-position-schema.json)

## Common Properties

- [Website](https://upvest.co/)
- [Portal](https://upvest.co/developers)
- [Documentation](https://docs.upvest.co/)
- [GettingStarted](https://docs.upvest.co/documentation/guides)
- [Blog](https://upvest.co/blog)
- [Blog - Engineering Blog](https://engineering.upvest.co/)
- [SignUp](https://upvest.co/contact)
- [PrivacyPolicy](https://upvest.co/legal/privacy-policy)
- [GitHubOrganization](https://github.com/upvestco)
- [GitHubRepository - HTTP Signature Proxy CLI](https://github.com/upvestco/httpsignature-proxy)
- [GitHubRepository - HTTP Signature Examples](https://github.com/upvestco/http-signature-examples)
- [JSONLD](json-ld/upvest-context.jsonld)
- [SpectralRules](rules/upvest-spectral-rules.yml)
- [Vocabulary](vocabulary/upvest-vocabulary.yaml)
- [NaftikoCapability - Investment Operations](capabilities/investment-operations.yaml)
- [NaftikoCapability - Investment API Shared](capabilities/shared/investment-api.yaml)

## Features

| Name | Description |
|------|-------------|
| Fractional Investing | Enable customers to invest in stocks and ETFs starting at 1 EUR with fractional share support. |
| Portfolio Management | Build customized portfolios of stocks, ETFs, and upcoming crypto assets with automated rebalancing. |
| Savings Plans | Configure recurring automated investment plans with direct debit integration. |
| Roundups | Micro-investing through spending-based roundups that automatically invest spare change. |
| Instant Account Creation | Enable customers to open investment accounts in seconds through the API. |
| Custody Management | Regulated custody services with digital reports and securities safeguarding. |
| Multi-Currency Cash Management | Track and manage cash balances across multiple currencies with virtual bank accounts. |
| Tax and Compliance | Automated tax wrapper support including ISA, tax exemptions, and compliance reporting. |
| Webhook Events | Real-time asynchronous event notifications for orders, payments, accounts, and compliance events. |
| Sandbox Environment | Full-featured sandbox at sandbox.upvest.co for testing with simulated bank transactions. |

## Use Cases

| Name | Description |
|------|-------------|
| Embedded Brokerage | Banks and fintechs embedding fractional stock and ETF trading into existing financial products. |
| Digital Wealth Management | Wealth managers building automated portfolio and savings plan products for retail clients. |
| Neobank Investment Features | Neobanks adding investment capabilities to checking and savings account offerings. |
| White-Label Investment Platform | Third-party platforms building fully branded investment experiences using Upvest infrastructure. |
| Roundup Investing | Platforms enabling micro-investing by rounding up purchases and investing the difference. |

## Integrations

| Name | Description |
|------|-------------|
| HTTP Signature Proxy | Localhost proxy for handling HTTP request signing required by the Upvest Investment API. |
| Direct Debit | Automated recurring payment integration for savings plans and top-ups. |
| Webhook Integration | Event-driven integration pattern via Upvest webhook subscriptions for real-time processing. |
| OAuth 2.0 | Client credentials flow for API authentication and token management. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Upvest Investment API](openapi/upvest-investment-api-openapi.yml)

### AsyncAPI

- [Upvest Investment Events](asyncapi/upvest-investment-events-asyncapi.yml)

### JSON Schema

- [User](json-schema/investment-api-user-schema.json)
- [Account](json-schema/investment-api-account-schema.json)
- [Order](json-schema/investment-api-order-schema.json)
- [Portfolio](json-schema/investment-api-portfolio-schema.json)
- [Savings Plan](json-schema/investment-api-savings-plan-schema.json)
- [Instrument](json-schema/investment-api-instrument-schema.json)
- [Transaction](json-schema/investment-api-transaction-schema.json)
- [Position](json-schema/investment-api-position-schema.json)
- [Direct Debit](json-schema/investment-api-direct-debit-schema.json)
- [Withdrawal](json-schema/investment-api-withdrawal-schema.json)
- [Webhook Subscription](json-schema/investment-api-webhook-subscription-schema.json)
- [Tax Residency](json-schema/investment-api-tax-residency-schema.json)
- *(56 total schema files in json-schema/)*

### JSON Structure

- [User Structure](json-structure/investment-api-user-structure.json)
- [Account Structure](json-structure/investment-api-account-structure.json)
- [Order Structure](json-structure/investment-api-order-structure.json)
- *(58 total structure files in json-structure/)*

### JSON-LD

- [Upvest Context](json-ld/upvest-context.jsonld)

### Examples

- [User Example](examples/investment-api-user-example.json)
- [Account Example](examples/investment-api-account-example.json)
- [Order Example](examples/investment-api-order-example.json)
- *(58 total example files in examples/)*

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Investment API](capabilities/shared/investment-api.yaml) — 30 operations covering the full Upvest investment infrastructure API

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Investment Operations](capabilities/investment-operations.yaml) | Upvest Investment API | 23 | Fintech Developer, Integration Engineer, Investment Platform Admin |

## Vocabulary

- [Upvest Vocabulary](vocabulary/upvest-vocabulary.yaml) — Unified taxonomy mapping 25 resources, 8 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Upvest Spectral Rules](rules/upvest-spectral-rules.yml) — 42 rules across 13 categories enforcing Upvest API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
