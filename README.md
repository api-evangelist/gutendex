# Gutendex (gutendex)

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

Gutendex is a simple, self-hosted JSON-based web API for serving book catalog information from Project Gutenberg, providing structured metadata for over 70,000 free ebooks including titles, authors, subjects, bookshelves, languages, copyright status, media types, downloadable formats, and download counts. The hosted instance at gutendex.com runs the open-source Django project by Gareth B. Johnson under the MIT license.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/gutendex/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/gutendex/main/apis.yml)

## Scope

- **Type:** Index
- **Access:** 3rd-Party

## Tags

- Books
- Catalog
- Ebooks
- Library
- Literature
- Metadata
- Open Source
- Project Gutenberg
- Public APIs
- Public Domain

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### Gutendex Books API

Returns paginated metadata for Project Gutenberg ebooks with filters for author birth/death year, copyright status, IDs, languages, MIME type, free-text search, topic, and sort order. Also exposes individual book lookup by Project Gutenberg ID.

- **Human URL:** [https://gutendex.com](https://gutendex.com)
- **Base URL:** `https://gutendex.com`

#### Tags

- Books
- Catalog
- Project Gutenberg
- Search

#### Properties

- [Documentation](https://gutendex.com)
- [OpenAPI](openapi/gutendex-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/gutendex-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/gutendex-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/gutendex-book-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gutendex-book-list-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gutendex-person-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gutendex-format-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/gutendex-error-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/gutendex-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

## Common Properties

- [Website](https://gutendex.com)
- [Documentation](https://gutendex.com)
- [OpenAPI](openapi/gutendex-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/gutendex-book-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/gutendex-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [GitHub Repository](https://github.com/garethbjohnson/gutendex)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Plans](plans/gutendex-plans-pricing.yml)
- [Pricing](plans/gutendex-plans-pricing.yml)
- [Rate Limits](rate-limits/gutendex-rate-limits.yml)
- [Spectral Rules](rules/gutendex-rules.yml)
- [Vocabulary](vocabulary/gutendex-vocabulary.yml)
- [Authentication](https://gutendex.com)
- [Getting Started](https://github.com/garethbjohnson/gutendex/wiki/Installation-Guide)
- [Tools](https://github.com/bobbyhouse/project-gutenberg-mcp)
- [Tools](https://github.com/vellankis-space/project-gutenberg-mcp-server)
- [Tools](https://github.com/nasimcoderex/gutenberg-mcp-server)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
