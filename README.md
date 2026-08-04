# Formstack (formstack)

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

Formstack is a no-code workplace productivity platform spanning online forms, document generation, electronic signature, and workflow automation. The developer portal at developers.formstack.com exposes a REST API (v2025.0) for forms, submissions, fields, webhooks, folders, and partial submissions, plus product-specific surfaces for Formstack Documents, Formstack Sign, and Formstack Workflows. Authentication uses OAuth 2.0. Machine-readable indexes and OpenAPI artifacts are surfaced at developers.formstack.com/llms.txt.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/formstack/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/formstack/refs/heads/main/apis.yml)

## Tags

- Forms
- Documents
- eSignature
- Workflow Automation
- No-Code
- OAuth2

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-30

## APIs

### Formstack Forms API

REST API for creating, reading, updating, and deleting forms in a Formstack account, including form configuration, styling, and access rules.

- **Human URL:** [https://developers.formstack.com/reference/api-overview](https://developers.formstack.com/reference/api-overview)
- **Base URL:** `https://www.formstack.com/api/v2`

#### Tags

- Forms
- REST

#### Properties

- [Documentation](https://developers.formstack.com/reference/api-overview)
- [Postman Collection](collections/formstack.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formstack.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Formstack Submissions API

Read, create, update, and delete form submissions; supports filtering by date, search, and field values. Returns submitted field data and metadata.

- **Human URL:** [https://developers.formstack.com/reference/api-overview](https://developers.formstack.com/reference/api-overview)
- **Base URL:** `https://www.formstack.com/api/v2`

#### Tags

- Submissions
- Data

#### Properties

- [Documentation](https://developers.formstack.com/reference/api-overview)
- [Postman Collection](collections/formstack.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formstack.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Formstack Fields API

Programmatically manage form fields - text, select, file upload, signature, payment, calculation, and others - including ordering, validation, and conditional logic.

- **Human URL:** [https://developers.formstack.com/reference/api-overview](https://developers.formstack.com/reference/api-overview)
- **Base URL:** `https://www.formstack.com/api/v2`

#### Tags

- Fields
- Form Schema

#### Properties

- [Documentation](https://developers.formstack.com/reference/api-overview)
- [Postman Collection](collections/formstack.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formstack.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Formstack Webhooks API

Configure webhook subscriptions to receive submission events at a customer-provided URL, with retry semantics for failed deliveries.

- **Human URL:** [https://developers.formstack.com/reference/api-overview](https://developers.formstack.com/reference/api-overview)
- **Base URL:** `https://www.formstack.com/api/v2`

#### Tags

- Webhooks
- Events

#### Properties

- [Documentation](https://developers.formstack.com/reference/api-overview)
- [AsyncAPI](https://raw.githubusercontent.com/api-evangelist/formstack/refs/heads/main/openapi/formstack-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/formstack.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formstack.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Formstack Folders API

Manage folder organization for forms within a Formstack account.

- **Human URL:** [https://developers.formstack.com/reference/api-overview](https://developers.formstack.com/reference/api-overview)
- **Base URL:** `https://www.formstack.com/api/v2`

#### Tags

- Folders
- Organization

#### Properties

- [Documentation](https://developers.formstack.com/reference/api-overview)
- [Postman Collection](collections/formstack.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formstack.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Formstack Documents API

Programmatic interface to Formstack Documents (formerly WebMerge) for generating PDFs, Word docs, and other templated documents from data payloads.

- **Human URL:** [https://developers.formstack.com/](https://developers.formstack.com/)
- **Base URL:** `https://www.webmerge.me/api`

#### Tags

- Documents
- Document Generation
- PDF

#### Properties

- [Documentation](https://developers.formstack.com/)
- [Postman Collection](collections/formstack.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formstack.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Formstack Sign API

Electronic signature API for sending documents for signature, tracking status, and retrieving signed copies. Part of the Formstack Suite.

- **Human URL:** [https://developers.formstack.com/](https://developers.formstack.com/)
- **Base URL:** `https://www.formstack.com/api/v2`

#### Tags

- eSignature
- Sign

#### Properties

- [Documentation](https://developers.formstack.com/)
- [Postman Collection](collections/formstack.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formstack.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Formstack Workflows API

Workflow automation surface for routing submissions, documents, and approvals across multi-step business processes.

- **Human URL:** [https://developers.formstack.com/](https://developers.formstack.com/)
- **Base URL:** `https://www.formstack.com/api/v2`

#### Tags

- Workflows
- Automation

#### Properties

- [Documentation](https://developers.formstack.com/)
- [Postman Collection](collections/formstack.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formstack.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Formstack OAuth 2.0

OAuth 2.0 authorization server used to authenticate API clients and issue access tokens for the Formstack REST API.

- **Human URL:** [https://developers.formstack.com/reference/oauth2-authentication](https://developers.formstack.com/reference/oauth2-authentication)
- **Base URL:** `https://www.formstack.com/api/v2/oauth2`

#### Tags

- OAuth2
- Authentication

#### Properties

- [Documentation](https://developers.formstack.com/reference/oauth2-authentication)
- [Postman Collection](collections/formstack.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/formstack.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.formstack.com/)
- [Documentation](https://developers.formstack.com/)
- [Changelog](https://developers.formstack.com/changelog)
- [L L Ms Txt](https://developers.formstack.com/llms.txt)
- [LinkedIn](https://www.linkedin.com/company/formstack)
- [Git Hub](https://github.com/formstack)
- [Twitter](https://twitter.com/Formstack)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
