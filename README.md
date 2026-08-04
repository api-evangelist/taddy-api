# Taddy API (taddy-api)

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

Taddy provides a GraphQL-based podcast API giving developers access to over 4 million podcasts and 200 million episodes with real-time search, episode transcripts, webhooks, top charts, and comic book data. Taddy simplifies building podcast applications by aggregating and standardizing RSS feed data at scale with daily updates of 1,000 new podcasts and 50,000 new episodes.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Audio
- Comics
- GraphQL
- Media
- Podcasts
- Transcripts
- Webhooks

## Timestamps

- **Created:** 2025-05-02
- **Modified:** 2026-05-19

## APIs

### Taddy Podcast API

GraphQL API providing access to over 4 million podcasts and 200 million episodes. Supports podcast and episode search, transcript retrieval with speaker and timecode data, top charts by country, webhooks for real-time updates and brand monitoring, and detailed metadata including genres, persons, chapters, and transcription status.

- **Human URL:** [https://taddy.org/developers/podcast-api](https://taddy.org/developers/podcast-api)
- **Base URL:** `https://api.taddy.org`

#### Tags

- Audio
- Episodes
- GraphQL
- Podcasts
- Search
- Transcripts
- Webhooks

#### Properties

- [Documentation](https://taddy.org/developers/podcast-api)
- [Getting Started](https://taddy.org/developers/intro-to-taddy-graphql-api)
- [Graph Q L  Schema](https://ax0.taddy.org/docs/schema.graphql)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/openapi/taddy-podcast-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/taddy-podcast.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/taddy-podcast.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Taddy Comics API

GraphQL API for accessing comic book series, issues, and creator data from the Taddy comic book database.

- **Human URL:** [https://taddy.org/developers/comics-api](https://taddy.org/developers/comics-api)
- **Base URL:** `https://api.taddy.org`

#### Tags

- Comics
- GraphQL
- Media

#### Properties

- [Documentation](https://taddy.org/developers/comics-api)
- [Postman Collection](collections/taddy-podcast.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/taddy-podcast.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/showcase/taddy-developers)
- [Portal](https://taddy.org/developers)
- [Documentation](https://taddy.org/developers/podcast-api)
- [Getting Started](https://taddy.org/developers/intro-to-taddy-graphql-api)
- [Sign Up](https://taddy.org/register)
- [Website](https://taddy.org/)
- [Pricing](https://taddy.org/developers#pricing)
- [Git Hub  Org](https://github.com/taddyorg)
- [Example  Project](https://github.com/taddyorg/taddy-api-example-project)
- [Dataset  Export](https://github.com/taddyorg/podcast-dataset-export)
- [Webhooks](https://github.com/taddyorg/webhook-example-taddy)
- [n8n  Integration](https://github.com/taddyorg/podcast-data-n8n-integration)
- [Zapier  Integration](https://github.com/taddyorg/podcast-data-zapier-integration)
- [J S O N  Schema](https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/json-schema/taddy-podcast-series-schema.json)
- [J S O N  Schema](https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/json-schema/taddy-podcast-episode-schema.json)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/vocabulary/taddy-api-vocabulary.yml)
- [L L Ms Txt](https://taddy.org/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
