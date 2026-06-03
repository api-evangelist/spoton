# SpotOn (spoton)
SpotOn is an all-in-one restaurant point-of-sale and management platform that combines POS, online ordering, reservations, payments, labor, and reporting for restaurants and hospitality businesses. For developers and integration partners, SpotOn offers the Restaurant POS Export API, a location-centric REST API that delivers close-to-realtime data export from the SpotOn Restaurant POS System. It exposes resources such as orders, menu items, modifiers, employees, taxes, surcharges, payment options, labor reports, and time clock entries. Authentication uses an API key supplied via the x-api-key request header, with access granted on a per-location basis. SpotOn also publishes the Reserve API (powered by SeatNinja) for its reservations and waitlist product.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/spoton/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Restaurant, Point of Sale, Payments, Online Ordering, Reservations, Reporting

## Timestamps

- **Created:** 2026-06-02
- **Modified:** 2026-06-03

## APIs

### SpotOn Restaurant POS Export API
A location-centric REST API providing close-to-realtime data export from the SpotOn Restaurant POS System. Resources include orders, order types, menu items, payment options, employees, job positions, time clock entries, paid in/outs, cash deposits, locations, and report categories. Authentication uses an API key passed in the x-api-key request header, with access scoped per location.

**Human URL:** [https://developers.spoton.com/restaurant/docs/introduction](https://developers.spoton.com/restaurant/docs/introduction)

**Base URL:** `https://restaurantapi.spoton.com/posexport/v1`

#### Tags:

 - Point of Sale, Orders, Menu, Employees, Reporting

#### Properties

- [Documentation](https://developers.spoton.com/restaurant/docs/introduction)
- [APIReference](https://developers.spoton.com/restaurant/reference)
- [Authentication](https://developers.spoton.com/restaurant/docs/api-access)
- [OpenAPI](openapi/spoton-restaurant-pos-export-openapi-original.yml)
- JSONSchema, JSONStructure, Example, and NaftikoCapability artifacts — see the Artifacts and Capabilities sections below.

### SpotOn Reserve API
An API for SpotOn Reserve (powered by SeatNinja), the company's reservations and waitlist product, allowing partners to list accessible restaurants, check available reservation times and wait times, create reservations, and add guests to a waitlist. Authentication uses an API key passed in the x-api-key request header, scoped per restaurant.

**Human URL:** [https://developers.spoton.com/reserve/docs/getting-started](https://developers.spoton.com/reserve/docs/getting-started)

**Base URL:** `https://api.seatninja.com`

#### Tags:

 - Reservations, Waitlist, Availability

#### Properties

- [Documentation](https://developers.spoton.com/reserve/docs/getting-started)
- [GettingStarted](https://developers.spoton.com/reserve/docs/getting-started)
- [SDK — JavaScript SDK](https://developers.spoton.com/reserve/docs/javascript)
- [OpenAPI](openapi/spoton-reserve-openapi-original.yml)
- JSONSchema, JSONStructure, Example, and NaftikoCapability artifacts — see the Artifacts and Capabilities sections below.

## Common Properties

- [Website](https://www.spoton.com)
- [Documentation](https://developers.spoton.com/restaurant/docs/introduction)
- [DeveloperPortal](https://www.spoton.com/developer-center/)
- [Pricing](https://www.spoton.com/pricing/)
- [GitHubOrganization](https://github.com/SpotOnInc)
- [StatusPage](https://status.seatninja.com/)
- [Support](https://help.spoton.com)
- [LinkedIn](https://www.linkedin.com/company/spoton)
- [X](https://twitter.com/spoton)
- [SpectralRules](rules/spoton-rules.yml)
- [Vocabulary](vocabulary/spoton-vocabulary.yaml)
- [Plans](plans/spoton-plans-pricing.yml)
- [RateLimits](rate-limits/spoton-rate-limits.yml)
- [FinOps](finops/spoton-finops.yml)

## Features

| Name | Description |
|------|-------------|
| Restaurant POS | All-in-one point-of-sale for counter-service and full-service restaurants. |
| Online Ordering | Branded online ordering integrated with the POS. |
| Reservations and Waitlist | SpotOn Reserve manages reservations, waitlists, and guest communication. |
| Payments | Integrated card processing with per-transaction take rates. |
| Labor Management | Employees, job positions, time clock entries, and labor reporting. |
| Reporting | Sales, cash, and labor reporting with close-to-realtime data export. |
| Data Export API | Location-centric REST API exporting orders, menu, payments, and labor data. |

## Use Cases

| Name | Description |
|------|-------------|
| Accounting and Reconciliation | Export orders, payments, and cash deposits to reconcile against statements and accounting systems. |
| Business Intelligence | Pull POS sales and labor data into a warehouse for analytics and dashboards. |
| Payroll Integration | Export time clock entries and pay rates to drive payroll processing. |
| Menu Synchronization | Keep third-party ordering and inventory systems in sync with the POS menu catalog. |
| Guest Booking Experiences | Build reservation and waitlist flows using the Reserve API and its JavaScript SDK. |

## Integrations

| Name | Description |
|------|-------------|
| Accounting Systems | Feed exported sales, cash, and tip data into accounting and bookkeeping platforms. |
| Payroll Providers | Use time clock and labor data to integrate with payroll services. |
| Data Warehouses | Load POS export data into analytics warehouses and BI tools. |
| Reservation Front-Ends | Embed SpotOn Reserve booking and waitlist via the JavaScript SDK. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [SpotOn Restaurant POS Export API](openapi/spoton-restaurant-pos-export-openapi-original.yml) — 21 operations across 11 resource groups
- [SpotOn Reserve API](openapi/spoton-reserve-openapi-original.yml) — 5 operations across reservations, waitlist, and availability

### JSON Schema

31 JSON Schema files in [`json-schema/`](json-schema/) extracted from the OpenAPI component schemas (22 Restaurant POS Export, 9 Reserve).

### JSON Structure

31 JSON Structure files in [`json-structure/`](json-structure/) converted from the JSON Schema files.

### JSON-LD

- [SpotOn Restaurant POS Export Context](json-ld/spoton-restaurant-pos-export-context.jsonld)
- [SpotOn Reserve Context](json-ld/spoton-reserve-context.jsonld)

### Examples

31 example payloads in [`examples/`](examples/), one per JSON Schema.

## Capabilities

Self-contained Naftiko capabilities (one per OpenAPI tag), each exposing a REST adapter and an MCP adapter routed through an inline consumes block.

### SpotOn Restaurant POS Export API

- [Locations](capabilities/restaurant-pos-export-locations.yaml) — 1 operation
- [Orders](capabilities/restaurant-pos-export-orders.yaml) — 2 operations
- [Order Types](capabilities/restaurant-pos-export-order-types.yaml) — 2 operations
- [Menu Items](capabilities/restaurant-pos-export-menu-items.yaml) — 2 operations
- [Payment Options](capabilities/restaurant-pos-export-payment-options.yaml) — 2 operations
- [Employees](capabilities/restaurant-pos-export-employees.yaml) — 2 operations
- [Job Positions](capabilities/restaurant-pos-export-job-positions.yaml) — 2 operations
- [Time Clock Entries](capabilities/restaurant-pos-export-time-clock-entries.yaml) — 2 operations
- [Paid In Outs](capabilities/restaurant-pos-export-paid-in-outs.yaml) — 2 operations
- [Cash Deposits](capabilities/restaurant-pos-export-cash-deposits.yaml) — 2 operations
- [Report Categories](capabilities/restaurant-pos-export-report-categories.yaml) — 2 operations

### SpotOn Reserve API

- [Restaurants](capabilities/reserve-restaurants.yaml) — 1 operation
- [Availability](capabilities/reserve-availability.yaml) — 2 operations
- [Reservations](capabilities/reserve-reservations.yaml) — 1 operation
- [Waitlist](capabilities/reserve-waitlist.yaml) — 1 operation

## Vocabulary

- [SpotOn Vocabulary](vocabulary/spoton-vocabulary.yaml) — Unified taxonomy mapping 15 resources, 4 actions, 7 workflows, and 6 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [SpotOn Rules](rules/spoton-rules.yml) — 35 rules across 13 categories enforcing SpotOn API conventions

## Commercial

- [Plans / Pricing](plans/spoton-plans-pricing.yml) — API Commons Plans 0.1 capturing the Quick Start, POS Essentials, and Build Your Own tiers
- [Rate Limits](rate-limits/spoton-rate-limits.yml) — API Commons Rate Limits 0.1 capturing date-range windowing and Reserve sandbox quotas
- [FinOps](finops/spoton-finops.yml) — FOCUS-aligned FinOps Framework 1.0 for subscription plus take-rate billing

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
