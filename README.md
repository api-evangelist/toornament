# Toornament

Toornament is an esports tournament management platform providing a comprehensive API for creating, managing, and viewing tournaments across 100+ esports disciplines. The API supports full tournament lifecycle management including participant registration, bracket generation, match reporting, and real-time standings. Used by game publishers, esports organizers, broadcasters, and gaming communities worldwide.

**Website:** [https://www.toornament.com](https://www.toornament.com)
**Documentation:** [https://developer.toornament.com](https://developer.toornament.com)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Brackets, Competition, Esports, Gaming, Tournaments

## APIs

### Toornament Organizer API

Full-featured tournament management API for tournament organizers. Provides complete CRUD operations for tournaments, participant management, stage and bracket configuration, match reporting, registration management, and webhook subscriptions.

**Human URL:** [https://developer.toornament.com/v2/overview/get-started](https://developer.toornament.com/v2/overview/get-started)
**Base URL:** `https://api.toornament.com/organizer/v2`

**Tags:** Brackets, Esports, Gaming, Matches, Organizer, Participants, Tournaments

**Authentication:** API key (X-Api-Key header) + OAuth2 access token

**Properties:**
- [Documentation](https://developer.toornament.com/v2/overview/get-started)
- [OpenAPI](openapi/toornament-openapi.yml)
- [SpectralRules](rules/toornament-rules.yml)
- [NaftikoCapability](capabilities/shared/toornament-organizer.yaml)

### Toornament Viewer API

Read-only public API for accessing tournament information. Ideal for embedding tournament brackets, leaderboards, and match schedules in applications and streaming overlays.

**Human URL:** [https://developer.toornament.com/v2/doc/viewer_overview](https://developer.toornament.com/v2/doc/viewer_overview)
**Base URL:** `https://api.toornament.com/viewer/v2`

**Tags:** Brackets, Esports, Gaming, Read-Only, Tournaments, Viewer

## Artifacts

### OpenAPI Specifications

| File | Description |
|---|---|
| [openapi/toornament-openapi.yml](openapi/toornament-openapi.yml) | Toornament Organizer API — OpenAPI 3.1 |

### Spectral Rules

| File | Description |
|---|---|
| [rules/toornament-rules.yml](rules/toornament-rules.yml) | Spectral ruleset for Toornament API conventions |

### Naftiko Capabilities

| File | Description |
|---|---|
| [capabilities/tournament-management.yaml](capabilities/tournament-management.yaml) | Full tournament lifecycle workflow (REST + MCP, 12 tools) |
| [capabilities/shared/toornament-organizer.yaml](capabilities/shared/toornament-organizer.yaml) | Shared Toornament Organizer API definition |

### JSON Schema

| File | Description |
|---|---|
| [json-schema/toornament-tournament-schema.json](json-schema/toornament-tournament-schema.json) | JSON Schema for Tournament entity |
| [json-schema/toornament-participant-schema.json](json-schema/toornament-participant-schema.json) | JSON Schema for Participant entity |

### JSON Structure

| File | Description |
|---|---|
| [json-structure/toornament-tournament-structure.json](json-structure/toornament-tournament-structure.json) | Tournament object model structure documentation |

### JSON-LD Context

| File | Description |
|---|---|
| [json-ld/toornament-context.jsonld](json-ld/toornament-context.jsonld) | JSON-LD context for Toornament domain vocabulary |

### Examples

| File | Description |
|---|---|
| [examples/toornament-create-tournament-example.json](examples/toornament-create-tournament-example.json) | POST /tournaments — create tournament |
| [examples/toornament-report-match-example.json](examples/toornament-report-match-example.json) | PATCH match — report match result |

### Vocabulary

| File | Description |
|---|---|
| [vocabulary/toornament-vocabulary.yml](vocabulary/toornament-vocabulary.yml) | Domain vocabulary for the Toornament platform |

## Features

- Tournament Creation and Management
- Participant Registration and Check-in
- Bracket Generation (Single/Double Elimination)
- Group Stage Management
- Match Reporting and Results
- Live Rankings and Standings
- Custom Registration Fields
- Webhook Event Notifications
- Multi-discipline Support (100+ games)
- Team and Player Support
- Public Viewer API

## Common Properties

- [Website](https://www.toornament.com/)
- [Documentation](https://developer.toornament.com/)
- [Getting Started](https://developer.toornament.com/v2/overview/get-started)
- [Sign Up](https://www.toornament.com/signup/)
- [Login](https://app.toornament.com/)
- [API Pricing](https://www.toornament.com/en_US/p/tournament-api)

## Timestamps

- **Created:** 2025-02-06
- **Modified:** 2026-05-03

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
