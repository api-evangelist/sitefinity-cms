# Sitefinity CMS (sitefinity-cms)
Sitefinity CMS is a .NET-based content management system developed by Progress Software that provides REST APIs for managing content items, pages, users, roles, taxonomies, media, and e-commerce resources. Developers use the Sitefinity REST API to build headless front-ends, integrate third-party systems, automate content operations, and extend the platform with custom modules.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/sitefinity-cms/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - Content Management, Headless CMS, .NET, REST

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-02

## APIs

### Sitefinity CMS Content API
The Sitefinity CMS Content API provides RESTful access to all content types defined in a Sitefinity instance. Developers use it to create, read, update, and delete content items, manage translations, publish and unpublish items, and query content with OData filtering, sorting, and pagination.

**Human URL:** [https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api](https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api)

#### Tags:
 - Content Management, Content Types, REST

#### Properties
- [Documentation](https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api)
- [OpenAPI](openapi/sitefinity-cms-content-api-openapi.yml)

---

### Sitefinity CMS Pages API
The Sitefinity CMS Pages API provides REST endpoints for managing the page hierarchy, page properties, page templates, and page nodes.

**Human URL:** [https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api-pages](https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api-pages)

#### Tags:
 - Content Management, Pages, REST

#### Properties
- [Documentation](https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api-pages)

---

### Sitefinity CMS Users and Roles API
The Sitefinity CMS Users and Roles API provides REST endpoints for managing user accounts, roles, and permissions.

**Human URL:** [https://www.progress.com/documentation/sitefinity-cms/for-developers-roles-api](https://www.progress.com/documentation/sitefinity-cms/for-developers-roles-api)

#### Tags:
 - Identity, REST, Roles, Users

#### Properties
- [Documentation](https://www.progress.com/documentation/sitefinity-cms/for-developers-roles-api)

---

### Sitefinity CMS Media API
The Sitefinity CMS Media API provides REST endpoints for managing images, videos, documents, and other media items stored in Sitefinity libraries.

**Human URL:** [https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api-media](https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api-media)

#### Tags:
 - Digital Assets, Libraries, Media, REST

#### Properties
- [Documentation](https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api-media)

---

### Sitefinity CMS Taxonomies API
The Sitefinity CMS Taxonomies API provides REST endpoints for managing taxonomies, categories, and tags used to classify content.

**Human URL:** [https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api](https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api)

#### Tags:
 - Classification, Content Management, REST, Taxonomies

#### Properties
- [Documentation](https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api)

---

## Common Properties

- [Website](https://www.progress.com/sitefinity-cms)
- [Documentation](https://www.progress.com/documentation/sitefinity-cms)
- [Portal](https://www.progress.com/documentation/sitefinity-cms/for-developers-rest-api)
- [Blog](https://www.progress.com/blogs/sitefinity)
- [Support](https://www.progress.com/support)

## Artifacts

### OpenAPI Specifications
- [sitefinity-cms-content-api-openapi.yml](openapi/sitefinity-cms-content-api-openapi.yml) — Content API (news, blog posts, events)

### JSON Schemas
- [sitefinity-cms-content-item-schema.json](json-schema/sitefinity-cms-content-item-schema.json) — Content item schema

### JSON Structures
- [sitefinity-cms-structure.json](json-structure/sitefinity-cms-structure.json) — Resource structure documentation

### JSON-LD
- [sitefinity-cms-context.jsonld](json-ld/sitefinity-cms-context.jsonld) — Linked data context

### Spectral Rules
- [sitefinity-cms-rules.yml](rules/sitefinity-cms-rules.yml) — API governance ruleset

### Capabilities (Naftiko)
- [content-management.yaml](capabilities/content-management.yaml) — Content management workflow (6 tools)

#### Shared Definitions
- [capabilities/shared/content-api.yaml](capabilities/shared/content-api.yaml)

### Examples
- [sitefinity-cms-list-news-items-example.json](examples/sitefinity-cms-list-news-items-example.json)

### Vocabulary
- [sitefinity-cms-vocabulary.yml](vocabulary/sitefinity-cms-vocabulary.yml) — Domain terminology

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
