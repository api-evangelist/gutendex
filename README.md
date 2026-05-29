# Gutendex (gutendex)

Gutendex is a simple, self-hosted JSON-based web API for serving book catalog information from
Project Gutenberg, providing structured metadata for over 70,000 free ebooks including titles,
authors, subjects, bookshelves, languages, copyright status, media types, downloadable formats,
and download counts. The hosted instance at [gutendex.com](https://gutendex.com) runs the
open-source Django project by Gareth B. Johnson under the MIT license.

**APIs.yml:** [apis.yml](apis.yml)

## Type
- **x-type:** opensource
- **x-tier:** 3 (bulk-registered from public-apis, enriched 2026-05-29)
- **source:** [public-apis/public-apis](https://github.com/public-apis/public-apis) — category: Books
- **License:** MIT
- **Stack:** Python / Django / Django REST Framework

## APIs

### Gutendex Books API
Paginated metadata for Project Gutenberg ebooks with filtering by author birth/death year,
copyright status, IDs, languages, MIME type, search keywords, topic, and sort order. Single-book
lookup by Project Gutenberg ID.

- **Base URL:** `https://gutendex.com`
- **Operations:**
  - `GET /books` — List Books (paginated, 32 per page)
  - `GET /books/{id}` — Get Book

## Artifacts

### OpenAPI
- [openapi/gutendex-api-openapi.yml](openapi/gutendex-api-openapi.yml)

### JSON Schema
- [json-schema/gutendex-book-schema.json](json-schema/gutendex-book-schema.json)
- [json-schema/gutendex-book-list-schema.json](json-schema/gutendex-book-list-schema.json)
- [json-schema/gutendex-person-schema.json](json-schema/gutendex-person-schema.json)
- [json-schema/gutendex-format-schema.json](json-schema/gutendex-format-schema.json)
- [json-schema/gutendex-error-schema.json](json-schema/gutendex-error-schema.json)

### JSON Structure
- [json-structure/gutendex-book-structure.json](json-structure/gutendex-book-structure.json)
- [json-structure/gutendex-book-list-structure.json](json-structure/gutendex-book-list-structure.json)
- [json-structure/gutendex-person-structure.json](json-structure/gutendex-person-structure.json)
- [json-structure/gutendex-format-structure.json](json-structure/gutendex-format-structure.json)
- [json-structure/gutendex-error-structure.json](json-structure/gutendex-error-structure.json)

### JSON-LD
- [json-ld/gutendex-context.jsonld](json-ld/gutendex-context.jsonld)

### Examples
- [examples/gutendex-list-books-example.json](examples/gutendex-list-books-example.json)
- [examples/gutendex-get-book-example.json](examples/gutendex-get-book-example.json)
- [examples/gutendex-book-example.json](examples/gutendex-book-example.json)
- [examples/gutendex-person-example.json](examples/gutendex-person-example.json)
- [examples/gutendex-format-example.json](examples/gutendex-format-example.json)
- [examples/gutendex-error-example.json](examples/gutendex-error-example.json)

### Naftiko Capabilities
- [capabilities/gutendex-books.yaml](capabilities/gutendex-books.yaml)

### Spectral Rules
- [rules/gutendex-rules.yml](rules/gutendex-rules.yml)

### Vocabulary
- [vocabulary/gutendex-vocabulary.yml](vocabulary/gutendex-vocabulary.yml)

### Plans
- [plans/gutendex-plans-pricing.yml](plans/gutendex-plans-pricing.yml)

### Rate Limits
- [rate-limits/gutendex-rate-limits.yml](rate-limits/gutendex-rate-limits.yml)

## MCP Servers (Community)
- [bobbyhouse/project-gutenberg-mcp](https://github.com/bobbyhouse/project-gutenberg-mcp)
- [vellankis-space/project-gutenberg-mcp-server](https://github.com/vellankis-space/project-gutenberg-mcp-server)
- [nasimcoderex/gutenberg-mcp-server](https://github.com/nasimcoderex/gutenberg-mcp-server)

## Tags
Books, Catalog, Ebooks, Library, Literature, Metadata, Open Source, Project Gutenberg,
Public APIs, Public Domain

## Notes
Originally bulk-registered as part of a public-apis catalog sweep on 2026-05-28.
Enriched 2026-05-29 via the full opensource pipeline against the canonical repository
at [github.com/garethbjohnson/gutendex](https://github.com/garethbjohnson/gutendex).

The hosted gutendex.com instance is free to use with no API key, no signup, and no documented
rate limit. For production workloads, self-host the MIT-licensed Django app rather than relying
on the shared community-funded endpoint.

## Timestamps
- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## Maintainers
- **Kin Lane** — kin@apievangelist.com
