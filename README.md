# Bloomerang (bloomerang)

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

Bloomerang is a cloud-based donor management and fundraising CRM built for small and mid-size nonprofits, covering constituent records, donations and pledges, communications, and reporting. Bloomerang acquired fellow nonprofit platform Kindful in January 2021, but Kindful continues to run its own separate API and product line; this entry documents Bloomerang's own REST API v2 (base `https://api.bloomerang.co/v2`), authenticated with a private API key or OAuth 2.0, for managing constituents, transactions, interactions, and related donor data.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/bloomerang/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/bloomerang/refs/heads/main/apis.yml)

## Tags

- Nonprofit
- Donor Management
- CRM
- Fundraising
- Fundraising Software

## Timestamps

- **Created:** 2026-07-03
- **Modified:** 2026-07-03

## APIs

### Bloomerang Constituents API

Create, retrieve, search, and update constituent records - the individuals, households, and organizations tracked in a Bloomerang donor database - including addresses, emails, phone numbers, and communication preferences.

- **Human URL:** [https://bloomerang.com/api/rest-api](https://bloomerang.com/api/rest-api)
- **Base URL:** `https://api.bloomerang.co/v2`

#### Tags

- Constituents
- Donors
- Contacts

#### Properties

- [Documentation](https://bloomerang.com/api/rest-api)
- [OpenAPI](openapi/bloomerang-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bloomerang.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bloomerang.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bloomerang Households API

Manage households - the family-unit grouping of individual constituents used throughout Bloomerang for giving history rollups and household-level mailings and reporting.

- **Human URL:** [https://bloomerang.com/api/rest-api](https://bloomerang.com/api/rest-api)
- **Base URL:** `https://api.bloomerang.co/v2`

#### Tags

- Households
- Constituents

#### Properties

- [Documentation](https://bloomerang.com/api/rest-api)
- [OpenAPI](openapi/bloomerang-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bloomerang.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bloomerang.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bloomerang Transactions API

Record and retrieve transactions - the total amount of a payment, split into one or more designations such as donations, pledges, pledge payments, recurring donations, or recurring donation payments - against a fund and constituent.

- **Human URL:** [https://bloomerang.com/api/rest-api](https://bloomerang.com/api/rest-api)
- **Base URL:** `https://api.bloomerang.co/v2`

#### Tags

- Transactions
- Donations
- Pledges

#### Properties

- [Documentation](https://bloomerang.com/api/rest-api)
- [OpenAPI](openapi/bloomerang-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bloomerang.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bloomerang.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bloomerang Interactions API

Log and retrieve interactions - a "touch" between the organization and a constituent such as a call, meeting, letter, or email - used to build the constituent engagement timeline.

- **Human URL:** [https://bloomerang.com/api/rest-api](https://bloomerang.com/api/rest-api)
- **Base URL:** `https://api.bloomerang.co/v2`

#### Tags

- Interactions
- Engagement
- Communications

#### Properties

- [Documentation](https://bloomerang.com/api/rest-api)
- [OpenAPI](openapi/bloomerang-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bloomerang.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bloomerang.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bloomerang Notes API

Create and retrieve freeform notes attached to a constituent record, including optional file attachments, surfaced on the constituent timeline alongside interactions and transactions.

- **Human URL:** [https://bloomerang.com/api/rest-api](https://bloomerang.com/api/rest-api)
- **Base URL:** `https://api.bloomerang.co/v2`

#### Tags

- Notes
- Constituents

#### Properties

- [Documentation](https://bloomerang.com/api/rest-api)
- [OpenAPI](openapi/bloomerang-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bloomerang.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bloomerang.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bloomerang Relationships API

Manage relationships between two constituents - such as spouse, employer, or board member - each carrying a role on both sides of the relationship and an optional note.

- **Human URL:** [https://bloomerang.com/api/rest-api](https://bloomerang.com/api/rest-api)
- **Base URL:** `https://api.bloomerang.co/v2`

#### Tags

- Relationships
- Constituents

#### Properties

- [Documentation](https://bloomerang.com/api/rest-api)
- [OpenAPI](openapi/bloomerang-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bloomerang.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bloomerang.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bloomerang Custom Fields API

Retrieve the custom field definitions configured for a given object type (Constituent, Transaction, Interaction, Note) so integrations can read and write an organization's account-specific custom data.

- **Human URL:** [https://bloomerang.com/api/rest-api](https://bloomerang.com/api/rest-api)
- **Base URL:** `https://api.bloomerang.co/v2`

#### Tags

- Custom Fields
- Configuration

#### Properties

- [Documentation](https://bloomerang.com/api/rest-api)
- [OpenAPI](openapi/bloomerang-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bloomerang.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bloomerang.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bloomerang Lists API

Read saved constituent lists (segments) built in the Bloomerang CRM UI, and page through the constituents they contain, for use in exports, mailings, and downstream reporting. Modeled from Bloomerang's list/segment feature set; a public REST path for this feature was not independently confirmed during review - see `review.yml`.

- **Human URL:** [https://bloomerang.com/api/rest-api](https://bloomerang.com/api/rest-api)
- **Base URL:** `https://api.bloomerang.co/v2`

#### Tags

- Lists
- Segmentation

#### Properties

- [Documentation](https://bloomerang.com/api/rest-api)
- [OpenAPI](openapi/bloomerang-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bloomerang.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bloomerang.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bloomerang Webhooks API

Register, list, and remove webhook subscriptions so a third-party system receives an HTTP callback when events occur in Bloomerang, such as a new constituent or transaction being created.

- **Human URL:** [https://bloomerang.com/api/rest-api](https://bloomerang.com/api/rest-api)
- **Base URL:** `https://api.bloomerang.co/v2`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://bloomerang.com/api/rest-api)
- [OpenAPI](openapi/bloomerang-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bloomerang.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bloomerang.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Bloomerang Accounts and Users API

Read account-level reference data - CRM users, funds, campaigns, and appeals - used to populate designations on transactions and to attribute activity to a specific staff user.

- **Human URL:** [https://bloomerang.com/api/rest-api](https://bloomerang.com/api/rest-api)
- **Base URL:** `https://api.bloomerang.co/v2`

#### Tags

- Accounts
- Users
- Funds
- Campaigns

#### Properties

- [Documentation](https://bloomerang.com/api/rest-api)
- [OpenAPI](openapi/bloomerang-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/bloomerang.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/bloomerang.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/Bloomerang)
- [LinkedIn](https://www.linkedin.com/company/bloomerang-donor-management-software)
- [Website](https://bloomerang.com)
- [Documentation](https://bloomerang.com/api)
- [Plans](plans/bloomerang-plans-pricing.yml)
- [Rate Limits](rate-limits/bloomerang-rate-limits.yml)
- [Fin Ops](finops/bloomerang-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
