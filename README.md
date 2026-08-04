# osmAPI (osmapi)

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

osmAPI is a unified AI gateway that routes requests to OpenAI, Anthropic, Google, and 14+ LLM providers through a single API. Drop-in compatible with the OpenAI SDK, it provides smart routing, streaming, function calling, web search, response healing, embeddings, audio, and realtime endpoints.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/osmapi/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/osmapi/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- AI
- Anthropic
- Gateway
- LLM
- OpenAI
- Routing

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-05-19

## APIs

### osmAPI Chat Completions API

OpenAI-compatible chat completions endpoint with smart routing, streaming, function calling, web search, and response healing across multiple LLM providers.

- **Human URL:** [https://docs.osmapi.com/v1_chat_completions](https://docs.osmapi.com/v1_chat_completions)
- **Base URL:** `https://api.osmapi.com/v1`

#### Tags

- AI
- Chat
- LLM
- Streaming

#### Properties

- [Documentation](https://docs.osmapi.com/v1_chat_completions)
- [OpenAPI](openapi/osmapi-chat-completions-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/osmapi-chat-completions.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/osmapi-chat-completions.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### osmAPI Anthropic Messages API

Anthropic-compatible messages endpoint supporting system prompts, extended thinking, tool use, and streaming through osmAPI's gateway.

- **Human URL:** [https://docs.osmapi.com/v1_messages](https://docs.osmapi.com/v1_messages)
- **Base URL:** `https://api.osmapi.com/v1`

#### Tags

- AI
- Anthropic
- Messages
- Tool Use

#### Properties

- [Documentation](https://docs.osmapi.com/v1_messages)
- [OpenAPI](openapi/osmapi-anthropic-messages-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/osmapi-anthropic-messages.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/osmapi-anthropic-messages.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### osmAPI Models API

Endpoint for listing available AI models with pricing, context length, capabilities, and provider details.

- **Human URL:** [https://docs.osmapi.com/v1_models](https://docs.osmapi.com/v1_models)
- **Base URL:** `https://api.osmapi.com/v1`

#### Tags

- AI
- Models

#### Properties

- [Documentation](https://docs.osmapi.com/v1_models)
- [OpenAPI](openapi/osmapi-models-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/osmapi-models.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/osmapi-models.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### osmAPI Health API

Health check endpoint reporting service status and dependency connectivity.

- **Human URL:** [https://docs.osmapi.com/health](https://docs.osmapi.com/health)
- **Base URL:** `https://api.osmapi.com`

#### Tags

- Health
- Status

#### Properties

- [Documentation](https://docs.osmapi.com/health)
- [OpenAPI](openapi/osmapi-health-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/osmapi-health.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/osmapi-health.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/openstreetmap)
- [LinkedIn](https://www.linkedin.com/company/osm-api)
- [Portal](https://www.osmapi.com/)
- [Documentation](https://docs.osmapi.com/)
- [Dashboard](https://app.osmapi.com/)
- [Authentication](https://docs.osmapi.com/features/api-keys)
- [Rate Limits](https://docs.osmapi.com/resources/rate-limits)
- [Routing](https://docs.osmapi.com/features/routing)
- [Caching](https://docs.osmapi.com/features/caching)
- [Pricing](https://docs.osmapi.com/features/cost-breakdown)
- [J S O N L D Context](json-ld/osmapi-context.jsonld)
- [JSON Schema](json-schema/osmapi-chat-completion-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/osmapi-model-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
