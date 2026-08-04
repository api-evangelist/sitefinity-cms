# Sitefinity CMS (sitefinity-cms)

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

Sitefinity CMS is a .NET-based content management system developed by Progress Software that provides REST APIs for managing content items, pages, users, roles, taxonomies, media, and e-commerce resources. Developers use the Sitefinity REST API to build headless front-ends, integrate third-party systems, automate content operations, and extend the platform with custom modules.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/sitefinity-cms/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sitefinity-cms/refs/heads/main/apis.yml)

## Tags

- Content Management
- Headless CMS
- .NET
- REST

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-19

## APIs

### Sitefinity CMS Content API

The Sitefinity CMS Content API provides RESTful access to all content types defined in a Sitefinity instance. Developers use it to create, read, update, and delete content items, manage content translations, publish and unpublish items, and query content with filtering, sorting, and pagination. The API is organized around content type endpoints generated dynamically from the Sitefinity content model, enabling custom content types to be accessed via consistent patterns.

- **Human URL:** [https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api](https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api)
- **Base URL:** `https://your-site.sitefinity.com/api/default`

#### Tags

- Content Management
- Content Types
- REST

#### Properties

- [Documentation](https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api)
- [OpenAPI](openapi/sitefinity-cms-content-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sitefinity-cms-content-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sitefinity-cms-content-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sitefinity CMS Pages API

The Sitefinity CMS Pages API provides REST endpoints for managing the page hierarchy, page properties, page templates, and page nodes. Developers use it to automate page creation, update navigation structures, manage URL routing, and integrate page management into CI/CD workflows. The Pages API is part of the broader Sitefinity REST infrastructure and supports standard CRUD operations.

- **Human URL:** [https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api-pages](https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api-pages)
- **Base URL:** `https://your-site.sitefinity.com/api/default`

#### Tags

- Pages
- Content Management
- REST

#### Properties

- [Documentation](https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api-pages)
- [Postman Collection](collections/sitefinity-cms-content-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sitefinity-cms-content-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sitefinity CMS Users and Roles API

The Sitefinity CMS Users and Roles API provides REST endpoints for managing user accounts, roles, and permissions. Developers use this API to automate user provisioning, manage role assignments, and integrate Sitefinity identity management with external identity providers. The Roles API exposes operations for listing, creating, and updating roles and their associated permissions.

- **Human URL:** [https://www.progress.com/documentation/sitefinity-cms/for-developers-roles-api](https://www.progress.com/documentation/sitefinity-cms/for-developers-roles-api)
- **Base URL:** `https://your-site.sitefinity.com/api/default`

#### Tags

- Users
- Roles
- Identity
- REST

#### Properties

- [Documentation](https://www.progress.com/documentation/sitefinity-cms/for-developers-roles-api)
- [Postman Collection](collections/sitefinity-cms-content-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sitefinity-cms-content-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sitefinity CMS Media API

The Sitefinity CMS Media API provides REST endpoints for managing images, videos, documents, and other media items stored in Sitefinity libraries. Developers use it to upload, retrieve, update, and delete media assets programmatically, supporting headless media workflows and integrations with digital asset management pipelines.

- **Human URL:** [https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api-media](https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api-media)
- **Base URL:** `https://your-site.sitefinity.com/api/default`

#### Tags

- Media
- Digital Assets
- Libraries
- REST

#### Properties

- [Documentation](https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api-media)
- [Postman Collection](collections/sitefinity-cms-content-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sitefinity-cms-content-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sitefinity CMS Taxonomies API

The Sitefinity CMS Taxonomies API provides REST endpoints for managing taxonomies, categories, and tags used to classify and organize content. Developers use it to create classification structures, assign taxonomy items to content, and query content by taxonomy dimension for filtering and navigation.

- **Human URL:** [https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api](https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api)
- **Base URL:** `https://your-site.sitefinity.com/api/default`

#### Tags

- Taxonomies
- Classification
- Content Management
- REST

#### Properties

- [Documentation](https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api)
- [Postman Collection](collections/sitefinity-cms-content-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sitefinity-cms-content-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/sitefinity)
- [LinkedIn](https://www.linkedin.com/showcase/progress-sitefinity-cms)
- [Website](https://www.progress.com/sitefinity-cms)
- [Documentation](https://www.progress.com/documentation/sitefinity-cms)
- [Portal](https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api)
- [Blog](https://www.progress.com/blogs/sitefinity)
- [Support](https://www.progress.com/support)
- [JSON-LD](json-ld/sitefinity-cms-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/sitefinity-cms-rules.yml)
- [Vocabulary](vocabulary/sitefinity-cms-vocabulary.yml)
- [Capabilities](capabilities/content-management.yaml)
- [Integrations](https://www.progress.com/partners)
