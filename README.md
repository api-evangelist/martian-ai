# Martian (martian-ai)

Martian operates an LLM model router and gateway that dynamically routes each request to the best underlying model across providers for the optimal balance of quality, latency, and cost. The Martian Gateway exposes a drop-in, OpenAI-compatible REST API (and an Anthropic Messages-compatible surface) so applications can route across a large catalog of models by changing only the base URL.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/martian-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/martian-ai/refs/heads/main/apis.yml)

## Tags

- AI
- LLM
- Model Router
- Gateway
- Cost Optimization

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Martian Chat Completions API

OpenAI-compatible chat completions routed dynamically across a large catalog of provider models. Models are addressed with a provider/model-name string, with optional routing controls (e.g. willingness-to-pay) to trade quality against cost, plus automatic cross-provider failover and streaming.

- **Human URL:** [https://docs.withmartian.com/api-reference/endpoints](https://docs.withmartian.com/api-reference/endpoints)
- **Base URL:** `https://api.withmartian.com/v1`

#### Tags

- Chat
- Completions
- Routing
- LLM

#### Properties

- [Documentation](https://docs.withmartian.com/quickstart)
- [API Reference](https://docs.withmartian.com/api-reference/endpoints)
- [OpenAPI](openapi/martian-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/martian-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/martian-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Martian Messages API

Anthropic Messages-compatible endpoint that accepts the Anthropic Messages request shape and routes it through the Martian Gateway, enabling Anthropic SDKs and frameworks to use Martian routing without code changes.

- **Human URL:** [https://docs.withmartian.com/api-reference/endpoints](https://docs.withmartian.com/api-reference/endpoints)
- **Base URL:** `https://api.withmartian.com/v1`

#### Tags

- Messages
- Anthropic Compatible
- Routing

#### Properties

- [API Reference](https://docs.withmartian.com/api-reference/endpoints)
- [OpenAPI](openapi/martian-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/martian-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/martian-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Martian Models API

Lists every model currently supported by the Martian Gateway, returning the provider/model-name identifiers usable as routing targets in chat completions and messages requests.

- **Human URL:** [https://docs.withmartian.com/api-reference/endpoints](https://docs.withmartian.com/api-reference/endpoints)
- **Base URL:** `https://api.withmartian.com/v1`

#### Tags

- Models
- Catalog
- Routing

#### Properties

- [API Reference](https://docs.withmartian.com/api-reference/endpoints)
- [OpenAPI](openapi/martian-ai-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/martian-ai.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/martian-ai.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/withmartian)
- [LinkedIn](https://www.linkedin.com/company/withmartian)
- [Website](https://www.withmartian.com)
- [Documentation](https://docs.withmartian.com)
- [Plans](plans/martian-ai-plans-pricing.yml)
- [Rate Limits](rate-limits/martian-ai-rate-limits.yml)
- [Fin Ops](finops/martian-ai-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
