# OpenUV (openuv)

OpenUV provides a global real-time UV index API. The service combines meteorological inputs (ozone, cloud cover, area reflection) with NASA satellite sources to return current UV index, daily maximum UV, ozone level, safe sun-exposure times per Fitzpatrick skin type, and a recommended sun protection window for any geographic coordinate.

**APIs.json:** [https://www.openuv.io](https://www.openuv.io)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Weather
- UV Index
- Sun
- Solar
- Geolocation
- Forecast
- Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### OpenUV

Real-time global UV index API returning current UV index, daily maximum UV, ozone, sun position, and safe exposure times by skin type for any latitude/longitude. Supports forecast windows and recommended sun-protection time windows. All endpoints are GET-only, authenticated via x-access-token header.

- **Human URL:** [https://www.openuv.io](https://www.openuv.io)
- **Base URL:** `https://api.openuv.io/api/v1`

#### Tags

- Weather
- UV Index
- Forecast

#### Properties

- [Documentation](https://www.openuv.io)
- [API Reference](https://www.openuv.io/api/json)
- [OpenAPI](openapi/openuv-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/openuv.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/openuv.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/openuv-uv-index-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openuv-uv-forecast-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/openuv-protection-window-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/openuv-uv-index-structure.json)
- [JSON Structure](json-structure/openuv-uv-forecast-structure.json)
- [JSON Structure](json-structure/openuv-protection-window-structure.json)
- [JSON-LD](json-ld/openuv-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Example](examples/openuv-uv-index-example.json)
- [Example](examples/openuv-uv-forecast-example.json)
- [Example](examples/openuv-protection-window-example.json)
- [Example](examples/openuv-api-statistics-example.json)
- [Example](examples/openuv-api-status-example.json)
- [JSON Schema](json-schema/openuv-api-statistics-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Authentication](https://www.openuv.io/console)
- [Rate Limits](rate-limits/openuv-rate-limits.yml)
- [Plans](plans/openuv-plans-pricing.yml)
- [Fin Ops](finops/openuv-finops.yml)

## Common Properties

- [Website](https://www.openuv.io)
- [Portal](https://www.openuv.io)
- [Console](https://www.openuv.io/console)
- [Sign Up](https://www.openuv.io/auth/signup)
- [Login](https://www.openuv.io/auth/signin)
- [Pricing](https://www.openuv.io/console)
- [Plans](plans/openuv-plans-pricing.yml)
- [Rate Limits](rate-limits/openuv-rate-limits.yml)
- [Support](mailto:support@openuv.io)
- [Contact](mailto:support@openuv.io)
- [Blog](https://www.openuv.io/blog)
- [SDK](https://github.com/aershov24/openuv-node)
- [SDK](https://github.com/bachya/pyopenuv)
- [Tools](https://github.com/ag2-mcp-servers/openuv---global-real-time-uv-index-forecast-api)
- [Integrations](https://www.home-assistant.io/integrations/openuv/)
- [Integrations](https://www.openhab.org/addons/bindings/openuv/)
- [Integrations](https://homey.app/en-us/app/io.openuv/OpenUV/)
- [GitHub Organization](https://github.com/OpenUV)
- [Public APIs Listing](https://github.com/public-apis/public-apis)
- [Spectral Rules](rules/openuv-rules.yml)
- [Vocabulary](vocabulary/openuv-vocabulary.yml)
- [JSON Structure](json-structure/openuv-structure.json)
- [Fin Ops](finops/openuv-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
