# SpotOn

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

SpotOn is an all-in-one restaurant point-of-sale and management platform that combines POS, online ordering, reservations, payments, labor, and reporting for restaurants and hospitality businesses. For developers and integration partners, SpotOn offers the Restaurant POS Export API, a location-centric REST API that delivers close-to-realtime data export from the SpotOn Restaurant POS System. It exposes resources such as orders, menu items, modifiers, employees, taxes, surcharges, payment options, labor reports, and time clock entries. Authentication uses an API key supplied via the x-api-key request header, with access granted on a per-location basis. SpotOn also publishes the Reserve API (powered by SeatNinja) for its reservations and waitlist product.

**Areas:** Restaurant · Point-of-Sale · Payments · Online Ordering · Reservations · Reporting

## SpotOn on APIs.io

Everything profiled for SpotOn is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/spoton/](https://apis.io/providers/spoton/)** — or go straight to one of the APIs or properties below.

### APIs (15)

- [SpotOn Availability API](https://apis.io/apis/spoton/spoton-availability-api/) — Available reservation times and wait-time lookups.
- [SpotOn Cash Deposits API](https://apis.io/apis/spoton/spoton-cash-deposits-api/) — Cash deposit records recorded at a location.
- [SpotOn Employees API](https://apis.io/apis/spoton/spoton-employees-api/) — Employee records and their job positions for a location.
- [SpotOn Job Positions API](https://apis.io/apis/spoton/spoton-job-positions-api/) — Job position definitions for a location.
- [SpotOn Locations API](https://apis.io/apis/spoton/spoton-locations-api/) — Location details for the SpotOn POS organization.
- [SpotOn Menu Items API](https://apis.io/apis/spoton/spoton-menu-items-api/) — Menu item catalog for a location.
- [SpotOn Order Types API](https://apis.io/apis/spoton/spoton-order-types-api/) — Order type definitions for a location, such as Dine In or Takeout.
- [SpotOn Orders API](https://apis.io/apis/spoton/spoton-orders-api/) — Order and check data export, including items, modifiers, payments, and taxes.
- [SpotOn Paid In Outs API](https://apis.io/apis/spoton/spoton-paid-in-outs-api/) — Cash paid in and paid out records for a location.
- [SpotOn Payment Options API](https://apis.io/apis/spoton/spoton-payment-options-api/) — Payment methods configured at a location.
- [SpotOn Report Categories API](https://apis.io/apis/spoton/spoton-report-categories-api/) — Hierarchical report categories used to group menu items.
- [SpotOn Reservations API](https://apis.io/apis/spoton/spoton-reservations-api/) — Create and manage guest reservations.
- [SpotOn Restaurants API](https://apis.io/apis/spoton/spoton-restaurants-api/) — Restaurants accessible with the API key.
- [SpotOn Time Clock Entries API](https://apis.io/apis/spoton/spoton-time-clock-entries-api/) — Employee shift clock-in and clock-out records.
- [SpotOn Waitlist API](https://apis.io/apis/spoton/spoton-waitlist-api/) — Add guests to a restaurant waitlist.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Spoton Agentic Access](https://apis.io/agentic-access/spoton/spoton-agentic-access/)

#### JSON Schema (31)

The data models the API reads and writes.

- [AvailabilityResponse](https://apis.io/schemas/spoton/reserve-availability-response/)
- [AvailabilitySlot](https://apis.io/schemas/spoton/reserve-availability-slot/)
- [CustomerInformation](https://apis.io/schemas/spoton/reserve-customer-information/)
- [Reservation](https://apis.io/schemas/spoton/reserve-reservation/)
- [ReservationRequest](https://apis.io/schemas/spoton/reserve-reservation-request/)
- [Restaurant](https://apis.io/schemas/spoton/reserve-restaurant/)
- [WaitTimeResponse](https://apis.io/schemas/spoton/reserve-wait-time-response/)
- [WaitlistEntry](https://apis.io/schemas/spoton/reserve-waitlist-entry/)
- [WaitlistRequest](https://apis.io/schemas/spoton/reserve-waitlist-request/)
- [Address](https://apis.io/schemas/spoton/restaurant-pos-export-address/)
- [Break](https://apis.io/schemas/spoton/restaurant-pos-export-break/)
- [CashDeposit](https://apis.io/schemas/spoton/restaurant-pos-export-cash-deposit/)
- [Employee](https://apis.io/schemas/spoton/restaurant-pos-export-employee/)
- [JobPosition](https://apis.io/schemas/spoton/restaurant-pos-export-job-position/)
- [Location](https://apis.io/schemas/spoton/restaurant-pos-export-location/)
- [MenuItemCatalog](https://apis.io/schemas/spoton/restaurant-pos-export-menu-item-catalog/)
- [Order](https://apis.io/schemas/spoton/restaurant-pos-export-order/)
- [OrderCheck](https://apis.io/schemas/spoton/restaurant-pos-export-order-check/)
- [OrderDiscount](https://apis.io/schemas/spoton/restaurant-pos-export-order-discount/)
- [OrderGuest](https://apis.io/schemas/spoton/restaurant-pos-export-order-guest/)
- [OrderMenuItem](https://apis.io/schemas/spoton/restaurant-pos-export-order-menu-item/)
- [OrderModifier](https://apis.io/schemas/spoton/restaurant-pos-export-order-modifier/)
- [OrderPayment](https://apis.io/schemas/spoton/restaurant-pos-export-order-payment/)
- [OrderSurcharge](https://apis.io/schemas/spoton/restaurant-pos-export-order-surcharge/)
- [OrderTax](https://apis.io/schemas/spoton/restaurant-pos-export-order-tax/)
- …and 6 more published on APIs.io

#### JSON Structure (31)

Data models expressed in JSON Structure.

- [Reserve Availability Response Structure](https://apis.io/json-structure/spoton/reserve-availability-response-structure/)
- [Reserve Availability Slot Structure](https://apis.io/json-structure/spoton/reserve-availability-slot-structure/)
- [Reserve Customer Information Structure](https://apis.io/json-structure/spoton/reserve-customer-information-structure/)
- [Reserve Reservation Request Structure](https://apis.io/json-structure/spoton/reserve-reservation-request-structure/)
- [Reserve Reservation Structure](https://apis.io/json-structure/spoton/reserve-reservation-structure/)
- [Reserve Restaurant Structure](https://apis.io/json-structure/spoton/reserve-restaurant-structure/)
- [Reserve Wait Time Response Structure](https://apis.io/json-structure/spoton/reserve-wait-time-response-structure/)
- [Reserve Waitlist Entry Structure](https://apis.io/json-structure/spoton/reserve-waitlist-entry-structure/)
- [Reserve Waitlist Request Structure](https://apis.io/json-structure/spoton/reserve-waitlist-request-structure/)
- [Restaurant Pos Export Address Structure](https://apis.io/json-structure/spoton/restaurant-pos-export-address-structure/)
- [Restaurant Pos Export Break Structure](https://apis.io/json-structure/spoton/restaurant-pos-export-break-structure/)
- [Restaurant Pos Export Cash Deposit Structure](https://apis.io/json-structure/spoton/restaurant-pos-export-cash-deposit-structure/)
- [Restaurant Pos Export Employee Structure](https://apis.io/json-structure/spoton/restaurant-pos-export-employee-structure/)
- [Restaurant Pos Export Job Position Structure](https://apis.io/json-structure/spoton/restaurant-pos-export-job-position-structure/)
- [Restaurant Pos Export Location Structure](https://apis.io/json-structure/spoton/restaurant-pos-export-location-structure/)
- [Restaurant Pos Export Menu Item Catalog Structure](https://apis.io/json-structure/spoton/restaurant-pos-export-menu-item-catalog-structure/)
- [Restaurant Pos Export Order Check Structure](https://apis.io/json-structure/spoton/restaurant-pos-export-order-check-structure/)
- [Restaurant Pos Export Order Discount Structure](https://apis.io/json-structure/spoton/restaurant-pos-export-order-discount-structure/)
- [Restaurant Pos Export Order Guest Structure](https://apis.io/json-structure/spoton/restaurant-pos-export-order-guest-structure/)
- [Restaurant Pos Export Order Menu Item Structure](https://apis.io/json-structure/spoton/restaurant-pos-export-order-menu-item-structure/)
- [Restaurant Pos Export Order Modifier Structure](https://apis.io/json-structure/spoton/restaurant-pos-export-order-modifier-structure/)
- [Restaurant Pos Export Order Payment Structure](https://apis.io/json-structure/spoton/restaurant-pos-export-order-payment-structure/)
- [Restaurant Pos Export Order Structure](https://apis.io/json-structure/spoton/restaurant-pos-export-order-structure/)
- [Restaurant Pos Export Order Surcharge Structure](https://apis.io/json-structure/spoton/restaurant-pos-export-order-surcharge-structure/)
- [Restaurant Pos Export Order Tax Structure](https://apis.io/json-structure/spoton/restaurant-pos-export-order-tax-structure/)
- …and 6 more published on APIs.io

#### JSON-LD (2)

Linked-data contexts for the provider's vocabulary.

- [Spoton Reserve Context](https://apis.io/jsonld/spoton/spoton-reserve-context/)
- [Spoton Restaurant Pos Export Context](https://apis.io/jsonld/spoton/spoton-restaurant-pos-export-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Spoton Vocabulary](https://apis.io/vocabularies/spoton/spoton-vocabulary/)

#### Examples (31)

Example requests and responses.

- [Reserve Availability Response Example](https://apis.io/examples/spoton/reserve-availability-response-example/)
- [Reserve Availability Slot Example](https://apis.io/examples/spoton/reserve-availability-slot-example/)
- [Reserve Customer Information Example](https://apis.io/examples/spoton/reserve-customer-information-example/)
- [Reserve Reservation Example](https://apis.io/examples/spoton/reserve-reservation-example/)
- [Reserve Reservation Request Example](https://apis.io/examples/spoton/reserve-reservation-request-example/)
- [Reserve Restaurant Example](https://apis.io/examples/spoton/reserve-restaurant-example/)
- [Reserve Wait Time Response Example](https://apis.io/examples/spoton/reserve-wait-time-response-example/)
- [Reserve Waitlist Entry Example](https://apis.io/examples/spoton/reserve-waitlist-entry-example/)
- [Reserve Waitlist Request Example](https://apis.io/examples/spoton/reserve-waitlist-request-example/)
- [Restaurant Pos Export Address Example](https://apis.io/examples/spoton/restaurant-pos-export-address-example/)
- [Restaurant Pos Export Break Example](https://apis.io/examples/spoton/restaurant-pos-export-break-example/)
- [Restaurant Pos Export Cash Deposit Example](https://apis.io/examples/spoton/restaurant-pos-export-cash-deposit-example/)
- [Restaurant Pos Export Employee Example](https://apis.io/examples/spoton/restaurant-pos-export-employee-example/)
- [Restaurant Pos Export Job Position Example](https://apis.io/examples/spoton/restaurant-pos-export-job-position-example/)
- [Restaurant Pos Export Location Example](https://apis.io/examples/spoton/restaurant-pos-export-location-example/)
- [Restaurant Pos Export Menu Item Catalog Example](https://apis.io/examples/spoton/restaurant-pos-export-menu-item-catalog-example/)
- [Restaurant Pos Export Order Check Example](https://apis.io/examples/spoton/restaurant-pos-export-order-check-example/)
- [Restaurant Pos Export Order Discount Example](https://apis.io/examples/spoton/restaurant-pos-export-order-discount-example/)
- [Restaurant Pos Export Order Example](https://apis.io/examples/spoton/restaurant-pos-export-order-example/)
- [Restaurant Pos Export Order Guest Example](https://apis.io/examples/spoton/restaurant-pos-export-order-guest-example/)
- [Restaurant Pos Export Order Menu Item Example](https://apis.io/examples/spoton/restaurant-pos-export-order-menu-item-example/)
- [Restaurant Pos Export Order Modifier Example](https://apis.io/examples/spoton/restaurant-pos-export-order-modifier-example/)
- [Restaurant Pos Export Order Payment Example](https://apis.io/examples/spoton/restaurant-pos-export-order-payment-example/)
- [Restaurant Pos Export Order Surcharge Example](https://apis.io/examples/spoton/restaurant-pos-export-order-surcharge-example/)
- [Restaurant Pos Export Order Tax Example](https://apis.io/examples/spoton/restaurant-pos-export-order-tax-example/)
- …and 6 more published on APIs.io

#### Collections (30)

Postman and Open Collection request collections.

- [SpotOn Reserve Availability API](https://apis.io/collections/spoton/open-spoton-availability-api/)
- [SpotOn Reserve Availability Cash Deposits API](https://apis.io/collections/spoton/open-spoton-cash-deposits-api/)
- [SpotOn Reserve Availability Employees API](https://apis.io/collections/spoton/open-spoton-employees-api/)
- [SpotOn Reserve Availability Job Positions API](https://apis.io/collections/spoton/open-spoton-job-positions-api/)
- [SpotOn Reserve Availability Locations API](https://apis.io/collections/spoton/open-spoton-locations-api/)
- [SpotOn Reserve Availability Menu Items API](https://apis.io/collections/spoton/open-spoton-menu-items-api/)
- [SpotOn Reserve Availability Order Types API](https://apis.io/collections/spoton/open-spoton-order-types-api/)
- [SpotOn Reserve Availability Orders API](https://apis.io/collections/spoton/open-spoton-orders-api/)
- [SpotOn Reserve Availability Paid In Outs API](https://apis.io/collections/spoton/open-spoton-paid-in-outs-api/)
- [SpotOn Reserve Availability Payment Options API](https://apis.io/collections/spoton/open-spoton-payment-options-api/)
- [SpotOn Reserve Availability Report Categories API](https://apis.io/collections/spoton/open-spoton-report-categories-api/)
- [SpotOn Reserve Availability Reservations API](https://apis.io/collections/spoton/open-spoton-reservations-api/)
- [SpotOn Reserve Availability Restaurants API](https://apis.io/collections/spoton/open-spoton-restaurants-api/)
- [SpotOn Reserve Availability Time Clock Entries API](https://apis.io/collections/spoton/open-spoton-time-clock-entries-api/)
- [SpotOn Reserve Availability Waitlist API](https://apis.io/collections/spoton/open-spoton-waitlist-api/)
- [SpotOn Reserve Availability API](https://apis.io/collections/spoton/postman-spoton-availability-api/)
- [SpotOn Reserve Availability Cash Deposits API](https://apis.io/collections/spoton/postman-spoton-cash-deposits-api/)
- [SpotOn Reserve Availability Employees API](https://apis.io/collections/spoton/postman-spoton-employees-api/)
- [SpotOn Reserve Availability Job Positions API](https://apis.io/collections/spoton/postman-spoton-job-positions-api/)
- [SpotOn Reserve Availability Locations API](https://apis.io/collections/spoton/postman-spoton-locations-api/)
- [SpotOn Reserve Availability Menu Items API](https://apis.io/collections/spoton/postman-spoton-menu-items-api/)
- [SpotOn Reserve Availability Order Types API](https://apis.io/collections/spoton/postman-spoton-order-types-api/)
- [SpotOn Reserve Availability Orders API](https://apis.io/collections/spoton/postman-spoton-orders-api/)
- [SpotOn Reserve Availability Paid In Outs API](https://apis.io/collections/spoton/postman-spoton-paid-in-outs-api/)
- [SpotOn Reserve Availability Payment Options API](https://apis.io/collections/spoton/postman-spoton-payment-options-api/)
- …and 5 more published on APIs.io

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [SpotOn — jsonschema rules](https://apis.io/rules/spoton/spoton-jsonschema-spectral-rules/)
- [SpotOn API Rules](https://apis.io/rules/spoton/spoton-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Spoton Authentication](https://apis.io/security/spoton/spoton-authentication/)
- [Spoton Domain Security](https://apis.io/security/spoton/spoton-domain-security/)
- [Spoton Trust Center](https://apis.io/security/spoton/spoton-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Spoton Plans Pricing](https://apis.io/plans/spoton/spoton-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Spoton Rate Limits](https://apis.io/rate-limits/spoton/spoton-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Spoton Finops](https://apis.io/finops/spoton/spoton-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.spoton.com)
- [Documentation](https://developers.spoton.com/restaurant/docs/introduction)
- [Pricing](https://www.spoton.com/pricing/)
- [Support](https://help.spoton.com)
- [Blog](https://www.spoton.com/blog/rss/)
- [GitHub](https://github.com/SpotOnInc)
- [Status](https://status.seatninja.com/)

## API Evangelist rating

**Kin Score 35.3** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 31.3 |
| Contract governance | 27.3 |
| Operational transparency | 26.3 |
| Developer ergonomics | 45.2 |
| Access clarity | 26.3 |

**Agent readiness 22.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 19.6** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/spoton/](https://apis.io/providers/spoton/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for SpotOn: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/spoton/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
