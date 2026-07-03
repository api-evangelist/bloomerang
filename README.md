# Bloomerang (bloomerang)

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
