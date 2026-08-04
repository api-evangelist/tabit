# Tabit (tabit)

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

Tabit is a mobile-first, cloud-based restaurant point-of-sale and hospitality management platform from Tabit Technologies. Its product suite spans tableside mobile ordering and payments (PAD/Pay), online ordering (Order), kitchen display (Chef), self-service kiosks, delivery (Wheels), guest management, gift cards, and hotel F&B/PMS integration. Tabit does not publish a public, self-service developer API or API reference; integrations are delivered through a partner program and an integration-request process rather than an open developer portal.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tabit/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tabit/refs/heads/main/apis.yml)

## Tags

- Restaurant
- Point of Sale
- POS
- Hospitality
- Ordering
- Payments

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## API Availability

Tabit does not operate a public developer portal and does not publish an API reference, OpenAPI definition, base URL, or authentication scheme. Integration with Tabit is partner-gated: prospective integrators submit an integration request and work through certified partner guides (Hotel PMS, white-label delivery such as DoorDash Marketplace, reservation software such as OpenTable, analytics, and FOH/BOH software). The APIs listed below describe Tabit's real functional surface areas as exposed through that partner program; they are not backed by publicly documented endpoints.

## APIs

### Tabit Orders API

Order capture and management across Tabit's mobile POS (PAD), online ordering (Order), kiosk, and delivery (Wheels) products. Order data flows to third-party channels (e.g., DoorDash Marketplace) through partner integrations rather than a documented public REST endpoint. No public order API reference, base URL, or authentication scheme is published as of this catalog date.

- **Human URL:** [https://www.tabit.cloud/integrations/](https://www.tabit.cloud/integrations/)

#### Tags

- Orders
- Ordering
- POS

#### Properties

- [Documentation](https://www.tabit.cloud/integrations/)
- [OpenAPI](openapi/tabit-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tabit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tabit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tabit Menu API

Menu and item/modifier management used to publish Tabit menus to online-ordering and third-party delivery channels (third-party menu management). Exposed to partners through Tabit's integration program; no public menu API reference, base URL, or authentication is documented.

- **Human URL:** [https://support-us.tabit.cloud/hc/en-us/sections/4942208018578-Online-Ordering-Integrations](https://support-us.tabit.cloud/hc/en-us/sections/4942208018578-Online-Ordering-Integrations)

#### Tags

- Menu
- Catalog
- Items

#### Properties

- [Documentation](https://support-us.tabit.cloud/hc/en-us/sections/4942208018578-Online-Ordering-Integrations)
- [OpenAPI](openapi/tabit-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tabit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tabit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tabit Reservations API

Reservation and guest-management capabilities, including integration with reservation software (e.g., Tabit is a listed OpenTable POS integration partner). Reservation data exchange is handled via certified partner integrations; no public reservations API reference or base URL is published.

- **Human URL:** [https://www.tabit.cloud/integrations/](https://www.tabit.cloud/integrations/)

#### Tags

- Reservations
- Bookings
- Guest

#### Properties

- [Documentation](https://www.tabit.cloud/integrations/)
- [OpenAPI](openapi/tabit-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tabit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tabit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tabit Payments API

Tabit Pay handles tableside card, tap-to-pay, and pay-at-table flows (QR / SMS to the guest's device) along with a Secure Payment Form (SPF) component maintained by Tabit's engineering org. Payment processing is delivered through the product and certified payment-provider integrations; no public, self-service payments API reference or base URL is published.

- **Human URL:** [https://support-us.tabit.cloud/hc/en-us/categories/22390251048210-Payments](https://support-us.tabit.cloud/hc/en-us/categories/22390251048210-Payments)

#### Tags

- Payments
- Tabit Pay
- Checkout

#### Properties

- [Documentation](https://support-us.tabit.cloud/hc/en-us/categories/22390251048210-Payments)
- [OpenAPI](openapi/tabit-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tabit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tabit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tabit Integrations API

Tabit's partner integration surface spanning Hotel PMS, white-label delivery (e.g., DoorDash Marketplace), analytics, reservation software, and front/back-of-house software. Onboarding is driven by an integration-request process and certified-partner guides rather than a public, open API; no self-service developer portal, endpoint catalog, or auth scheme is published.

- **Human URL:** [https://support-us.tabit.cloud/hc/en-us/articles/12570827573266-Overview-of-Tabit-s-Integrations](https://support-us.tabit.cloud/hc/en-us/articles/12570827573266-Overview-of-Tabit-s-Integrations)

#### Tags

- Integrations
- Partners
- PMS

#### Properties

- [Documentation](https://support-us.tabit.cloud/hc/en-us/articles/12570827573266-Overview-of-Tabit-s-Integrations)
- [Documentation](https://support-us.tabit.cloud/hc/en-us/sections/15837301376658-Integration-Guides)
- [OpenAPI](openapi/tabit-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tabit.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tabit.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/inPact)
- [LinkedIn](https://www.linkedin.com/company/tabit-technologies)
- [Website](https://www.tabit.cloud/)
- [Documentation](https://support-us.tabit.cloud/hc/en-us)
- [Plans](plans/tabit-plans-pricing.yml)
- [Rate Limits](rate-limits/tabit-rate-limits.yml)
- [Fin Ops](finops/tabit-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
