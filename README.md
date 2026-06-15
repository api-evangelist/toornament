# Toornament (toornament)

Toornament is an esports tournament management platform providing a comprehensive API for creating, managing, and viewing tournaments across 100+ esports disciplines. The API supports full tournament lifecycle management including participant registration, bracket generation, match reporting, and real-time standings. Used by game publishers, esports organizers, broadcasters, and gaming communities worldwide.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/toornament/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/toornament/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Esports
- Gaming
- Tournaments
- Brackets
- Competition

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-05-19

## APIs

### Toornament Organizer API

Full-featured tournament management API for tournament organizers. Provides complete CRUD operations for tournaments, participant management, stage and bracket configuration, match reporting, registration management, and webhook subscriptions. Requires API key authentication plus OAuth2 access tokens with organizer:view or organizer:admin scopes.

- **Human URL:** [https://developer.toornament.com/v2/overview/get-started](https://developer.toornament.com/v2/overview/get-started)
- **Base URL:** `https://api.toornament.com/organizer/v2`

#### Tags

- Brackets
- Esports
- Gaming
- Matches
- Organizer
- Participants
- Tournaments

#### Properties

- [Documentation](https://developer.toornament.com/v2/overview/get-started)
- [OpenAPI](openapi/toornament-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/toornament.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toornament.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/toornament-rules.yml)

### Toornament Viewer API

Read-only public API for accessing tournament information without full organizer authentication. Ideal for embedding tournament brackets, leaderboards, and match schedules in applications, streaming overlays, and fan sites. Supports disciplines, tournaments, participants, stages, matches, and rankings.

- **Human URL:** [https://developer.toornament.com/v2/doc/viewer_overview](https://developer.toornament.com/v2/doc/viewer_overview)
- **Base URL:** `https://api.toornament.com/viewer/v2`

#### Tags

- Brackets
- Esports
- Gaming
- Read-Only
- Tournaments
- Viewer

#### Properties

- [Documentation](https://developer.toornament.com/v2/doc/viewer_overview)
- [Postman Collection](collections/toornament.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/toornament.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/toornament)
- [Website](https://www.toornament.com/)
- [Documentation](https://developer.toornament.com/)
- [Getting Started](https://developer.toornament.com/v2/overview/get-started)
- [Sign Up](https://www.toornament.com/signup/)
- [Login](https://app.toornament.com/)
- [Pricing](https://www.toornament.com/en_US/p/tournament-api)
- [JSON-LD](json-ld/toornament-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [J S O N- Schema](json-schema/toornament-tournament-schema.json)
- [JSON Structure](json-structure/toornament-tournament-structure.json)
- [Spectral Rules](rules/toornament-rules.yml)
- [Vocabulary](vocabulary/toornament-vocabulary.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
