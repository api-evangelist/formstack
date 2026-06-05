# Formstack (formstack)

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
