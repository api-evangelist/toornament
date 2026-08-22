# Toornament (toornament)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
