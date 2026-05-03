# Taddy API

Taddy provides a GraphQL-based podcast API giving developers access to over 4 million podcasts and 200 million episodes with real-time search, episode transcripts, webhooks, top charts, and comic book data. Taddy simplifies building podcast applications by aggregating and standardizing RSS feed data at scale with daily updates of 1,000 new podcasts and 50,000 new episodes.

**APIs.json URL:** https://raw.githubusercontent.com/api-evangelist/taddy-api/refs/heads/main/apis.yml

## APIs

### Taddy Podcast API

GraphQL API providing access to over 4 million podcasts and 200 million episodes. Supports podcast and episode search, transcript retrieval with speaker and timecode data, top charts by country, webhooks for real-time updates and brand monitoring, and detailed metadata including genres, persons, chapters, and transcription status.

- **Base URL:** https://api.taddy.org
- **Documentation:** https://taddy.org/developers/podcast-api
- **Getting Started:** https://taddy.org/developers/intro-to-taddy-graphql-api
- **GraphQL Schema:** https://ax0.taddy.org/docs/schema.graphql
- **OpenAPI Spec:** [openapi/taddy-podcast-openapi.yml](openapi/taddy-podcast-openapi.yml)

### Taddy Comics API

GraphQL API for accessing comic book series, issues, and creator data from the Taddy comic book database.

- **Documentation:** https://taddy.org/developers/comics-api

## Artifacts

### OpenAPI Specifications

| API | File |
|---|---|
| Taddy Podcast API | [openapi/taddy-podcast-openapi.yml](openapi/taddy-podcast-openapi.yml) |

### JSON Schemas

| Schema | File |
|---|---|
| Podcast Series | [json-schema/taddy-podcast-series-schema.json](json-schema/taddy-podcast-series-schema.json) |
| Podcast Episode | [json-schema/taddy-podcast-episode-schema.json](json-schema/taddy-podcast-episode-schema.json) |

### JSON Structures

| Structure | File |
|---|---|
| Podcast Series | [json-structure/taddy-podcast-series-structure.json](json-structure/taddy-podcast-series-structure.json) |
| Podcast Episode | [json-structure/taddy-podcast-episode-structure.json](json-structure/taddy-podcast-episode-structure.json) |

### JSON-LD Contexts

| Context | File |
|---|---|
| Taddy API | [json-ld/taddy-api-context.jsonld](json-ld/taddy-api-context.jsonld) |

### Examples

| Example | File |
|---|---|
| Execute GraphQL Query | [examples/taddy-execute-graphql-query-example.json](examples/taddy-execute-graphql-query-example.json) |

### Spectral Rules

| Ruleset | File |
|---|---|
| Taddy API Rules | [rules/taddy-api-rules.yml](rules/taddy-api-rules.yml) |

### Naftiko Capabilities

#### Shared Definitions

| API | File |
|---|---|
| Taddy Podcast | [capabilities/shared/taddy-podcast.yaml](capabilities/shared/taddy-podcast.yaml) |

#### Workflow Capabilities

| Workflow | Description | File |
|---|---|---|
| Podcast Discovery | Search, retrieve, and analyze podcast content for content teams and app developers | [capabilities/podcast-discovery.yaml](capabilities/podcast-discovery.yaml) |

### Vocabulary

| Vocabulary | File |
|---|---|
| Taddy API | [vocabulary/taddy-api-vocabulary.yml](vocabulary/taddy-api-vocabulary.yml) |

## Resources

- **Developer Portal:** https://taddy.org/developers
- **Pricing:** https://taddy.org/developers#pricing (Free, Pro $75/mo, Business $150/mo)
- **Sign Up:** https://taddy.org/register
- **GitHub Org:** https://github.com/taddyorg
- **Example Project:** https://github.com/taddyorg/taddy-api-example-project
- **Dataset Export:** https://github.com/taddyorg/podcast-dataset-export
- **Webhook Example:** https://github.com/taddyorg/webhook-example-taddy
- **n8n Integration:** https://github.com/taddyorg/podcast-data-n8n-integration
- **Zapier Integration:** https://github.com/taddyorg/podcast-data-zapier-integration

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
