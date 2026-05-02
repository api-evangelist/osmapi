# osmAPI (osmapi)
osmAPI is a unified AI gateway that routes requests to OpenAI, Anthropic, Google, and 14+ LLM providers through a single API. Drop-in compatible with the OpenAI SDK, it provides smart routing, streaming, function calling, web search, response healing, embeddings, audio, and realtime endpoints.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/osmapi/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags:

 - AI, LLM, Gateway, Routing, OpenAI, Anthropic

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-04-28

## APIs

### osmAPI Chat Completions API
OpenAI-compatible chat completions endpoint with smart routing, streaming, function calling, web search, and response healing across multiple LLM providers.

**Human URL:** [https://docs.osmapi.com/v1_chat_completions](https://docs.osmapi.com/v1_chat_completions)

**Base URL:** https://api.osmapi.com/v1

#### Tags:

 - AI, Chat, LLM, Streaming

#### Properties

- [Documentation](https://docs.osmapi.com/v1_chat_completions)
- [OpenAPI](openapi/osmapi-chat-completions-openapi.yml)

### osmAPI Anthropic Messages API
Anthropic-compatible messages endpoint supporting system prompts, extended thinking, tool use, and streaming through osmAPI's gateway.

**Human URL:** [https://docs.osmapi.com/v1_messages](https://docs.osmapi.com/v1_messages)

**Base URL:** https://api.osmapi.com/v1

#### Tags:

 - AI, Anthropic, Messages, Tool Use

#### Properties

- [Documentation](https://docs.osmapi.com/v1_messages)
- [OpenAPI](openapi/osmapi-anthropic-messages-openapi.yml)

### osmAPI Models API
Endpoint for listing available AI models with pricing, context length, capabilities, and provider details.

**Human URL:** [https://docs.osmapi.com/v1_models](https://docs.osmapi.com/v1_models)

**Base URL:** https://api.osmapi.com/v1

#### Tags:

 - AI, Models

#### Properties

- [Documentation](https://docs.osmapi.com/v1_models)
- [OpenAPI](openapi/osmapi-models-openapi.yml)

### osmAPI Health API
Health check endpoint reporting service status and dependency connectivity.

**Human URL:** [https://docs.osmapi.com/health](https://docs.osmapi.com/health)

**Base URL:** https://api.osmapi.com

#### Tags:

 - Health, Status

#### Properties

- [Documentation](https://docs.osmapi.com/health)
- [OpenAPI](openapi/osmapi-health-openapi.yml)

## Common Properties

- [Portal](https://www.osmapi.com/)
- [Documentation](https://docs.osmapi.com/)
- [Dashboard](https://app.osmapi.com/)
- [Authentication](https://docs.osmapi.com/features/api-keys)
- [RateLimits](https://docs.osmapi.com/resources/rate-limits)
- [Routing](https://docs.osmapi.com/features/routing)
- [Caching](https://docs.osmapi.com/features/caching)
- [Pricing](https://docs.osmapi.com/features/cost-breakdown)
- [JSONLDContext](json-ld/osmapi-context.jsonld)
- [JSONSchema](json-schema/osmapi-chat-completion-schema.json)
- [JSONSchema](json-schema/osmapi-model-schema.json)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
