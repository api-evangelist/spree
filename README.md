# Spree Commerce (spree)

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

Open-source headless e-commerce framework with a REST API for managing products, variants, orders, customers, inventory, promotions, and payment processing. Spree provides two OpenAPI 3.0-documented APIs — a Store API for customer-facing operations and an Admin API for back-office management — along with a TypeScript SDK, CLI, and Next.js storefront starter.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/spree/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/spree/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- E-Commerce
- Headless Commerce
- Products
- Orders
- Inventory
- Payments
- Promotions
- Open Source
- Ruby on Rails

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Spree Store API

Customer-facing REST API for browsing products, managing carts, placing orders, and handling checkout. Documented with OpenAPI 3.0.

- **Human URL:** [https://spreecommerce.org/docs/api-reference/introduction](https://spreecommerce.org/docs/api-reference/introduction)
- **Base URL:** `https://yourdomain.com/api/v3/store`

#### Tags

- Products
- Cart
- Checkout
- Orders
- Customers
- Storefront

#### Properties

- [Documentation](https://spreecommerce.org/docs/api-reference/introduction)
- [OpenAPI](openapi/spree-store-api.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Spree Admin API

Back-office REST API for managing products, variants, inventory, promotions, orders, users, and store configuration. Documented with OpenAPI 3.0.

- **Human URL:** [https://spreecommerce.org/docs/api-reference/introduction](https://spreecommerce.org/docs/api-reference/introduction)
- **Base URL:** `https://yourdomain.com/api/v3/admin`

#### Tags

- Products
- Variants
- Inventory
- Promotions
- Orders
- Users
- Administration

#### Properties

- [Documentation](https://spreecommerce.org/docs/api-reference/introduction)
- [OpenAPI](openapi/spree-admin-api.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Spree Storefront API

Legacy storefront REST API for customer-facing operations including products, cart, checkout, and account management. OpenAPI 3.0 documented.

- **Human URL:** [https://spreecommerce.org/docs/api-reference/introduction](https://spreecommerce.org/docs/api-reference/introduction)
- **Base URL:** `https://demo.spreecommerce.org`

#### Tags

- Products
- Cart
- Checkout
- Orders
- Storefront

#### Properties

- [Documentation](https://spreecommerce.org/docs/api-reference/introduction)
- [OpenAPI](openapi/spree-storefront-api.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Spree Platform API

Platform-level REST API for multi-tenant and enterprise Spree deployments, covering advanced store configuration, multi-vendor, and platform management. OpenAPI 3.0 documented.

- **Human URL:** [https://spreecommerce.org/docs/api-reference/introduction](https://spreecommerce.org/docs/api-reference/introduction)
- **Base URL:** `https://yourdomain.com/api/v3`

#### Tags

- Platform
- Multi-Vendor
- Administration
- Store Configuration

#### Properties

- [Documentation](https://spreecommerce.org/docs/api-reference/introduction)
- [OpenAPI](openapi/spree-platform-api.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [Website](https://spreecommerce.org/)
- [Documentation](https://spreecommerce.org/docs/developer/getting-started/quickstart)
- [Git Hub Org](https://github.com/spree)
- [LinkedIn](https://www.linkedin.com/company/spree-commerce)
- [Blog](https://spreecommerce.org/blog/)
- [Pricing](https://spreecommerce.org/enterprise/)
- [Status Page](https://spreecommerce.org/)
- [X (Twitter)](https://x.com/spreecommerce)
- [Plans](plans/spree-plans-pricing.yml)
- [Rate Limits](rate-limits/spree-rate-limits.yml)
- [Fin Ops](finops/spree-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
