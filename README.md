# osmAPI

This is a repository for tracking the APIs, properties, and artifacts for osmAPI, a unified AI gateway that routes requests to OpenAI, Anthropic, Google, and 14+ LLM providers through a single API.

## APIs

- **osmAPI Chat Completions API** - ([Documentation](https://docs.osmapi.com/v1_chat_completions)) ([OpenAPI](openapi/osmapi-chat-completions-openapi.yml)) - OpenAI-compatible chat completions endpoint with smart routing, streaming, function calling, web search, and response healing across multiple LLM providers.
- **osmAPI Anthropic Messages API** - ([Documentation](https://docs.osmapi.com/v1_messages)) ([OpenAPI](openapi/osmapi-anthropic-messages-openapi.yml)) - Anthropic-compatible messages endpoint supporting system prompts, extended thinking, tool use, and streaming through osmAPI's gateway.
- **osmAPI Models API** - ([Documentation](https://docs.osmapi.com/v1_models)) ([OpenAPI](openapi/osmapi-models-openapi.yml)) - Endpoint for listing available AI models with pricing, context length, capabilities, and provider details.
- **osmAPI Health API** - ([Documentation](https://docs.osmapi.com/health)) ([OpenAPI](openapi/osmapi-health-openapi.yml)) - Health check endpoint reporting service status and dependency connectivity.

## Common Properties

- [Portal](https://www.osmapi.com/)
- [Documentation](https://docs.osmapi.com/)
- [Dashboard](https://app.osmapi.com/)
- [Authentication](https://docs.osmapi.com/features/api-keys)
- [Rate Limits](https://docs.osmapi.com/resources/rate-limits)
- [Routing](https://docs.osmapi.com/features/routing)
- [Caching](https://docs.osmapi.com/features/caching)
- [Pricing](https://docs.osmapi.com/features/cost-breakdown)

## Artifacts

- [JSON-LD Context](json-ld/osmapi-context.jsonld)
- [Chat Completion JSON Schema](json-schema/osmapi-chat-completion-schema.json)
- [Model JSON Schema](json-schema/osmapi-model-schema.json)
