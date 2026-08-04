# SpotOn (spoton)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
