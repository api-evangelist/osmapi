# osmAPI (osmapi)

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
