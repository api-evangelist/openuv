# OpenUV (openuv)

OpenUV provides a global real-time UV index API. The service combines meteorological inputs (ozone, cloud cover, area reflection) with NASA satellite sources to return current UV index, daily maximum UV, ozone level, safe sun-exposure times per Fitzpatrick skin type, and a recommended sun protection window for any geographic coordinate.

**URL:** [Visit APIs.json URL](https://www.openuv.io)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Weather, UV Index, Sun, Solar, Geolocation, Forecast, Public APIs

## Timestamps

- **Created:** 2026-05-28
- **Modified:** 2026-05-29

## APIs

### OpenUV

Real-time global UV index API returning current UV index, daily maximum UV, ozone, sun position, and safe exposure times by skin type for any latitude/longitude. Supports forecast windows and recommended sun-protection time windows. All endpoints are GET-only, authenticated via x-access-token header.

**Human URL:** [https://www.openuv.io](https://www.openuv.io)

**Base URL:** `https://api.openuv.io/api/v1`

#### Tags:

 - Weather, UV Index, Forecast

#### Properties

- [Documentation](https://www.openuv.io)
- [APIReference](https://www.openuv.io/api/json)
- [OpenAPI](openapi/openuv-openapi.yml)
- [JSONSchema — UV Index](json-schema/openuv-uv-index-schema.json)
- [JSONSchema — UV Forecast](json-schema/openuv-uv-forecast-schema.json)
- [JSONSchema — Protection Window](json-schema/openuv-protection-window-schema.json)
- [JSONSchema — API Statistics](json-schema/openuv-api-statistics-schema.json)
- [JSONStructure — UV Index](json-structure/openuv-uv-index-structure.json)
- [JSONStructure — UV Forecast](json-structure/openuv-uv-forecast-structure.json)
- [JSONStructure — Protection Window](json-structure/openuv-protection-window-structure.json)
- [JSON-LD Context](json-ld/openuv-context.jsonld)
- [Example — UV Index](examples/openuv-uv-index-example.json)
- [Example — UV Forecast](examples/openuv-uv-forecast-example.json)
- [Example — Protection Window](examples/openuv-protection-window-example.json)
- [Example — API Statistics](examples/openuv-api-statistics-example.json)
- [Example — API Status](examples/openuv-api-status-example.json)
- [Authentication](https://www.openuv.io/console)
- [Rate Limits](rate-limits/openuv-rate-limits.yml)
- [Plans](plans/openuv-plans-pricing.yml)
- [FinOps](finops/openuv-finops.yml)

#### Naftiko Capabilities

- [openuv-uv-index](capabilities/openuv-uv-index.yaml) — UV Index surface (2 operations: getCurrentUVIndex, getUVForecast)
- [openuv-protection](capabilities/openuv-protection.yaml) — Sun protection window (1 operation: getProtectionWindow)
- [openuv-account](capabilities/openuv-account.yaml) — Account and observability (2 operations: getApiStatus, getApiStatistics)

## Common Properties

- [Website](https://www.openuv.io)
- [Portal](https://www.openuv.io)
- [Console](https://www.openuv.io/console)
- [SignUp](https://www.openuv.io/auth/signup)
- [Login](https://www.openuv.io/auth/signin)
- [Pricing](https://www.openuv.io/console)
- [Plans](plans/openuv-plans-pricing.yml)
- [Rate Limits](rate-limits/openuv-rate-limits.yml)
- [FinOps](finops/openuv-finops.yml)
- [Support](mailto:support@openuv.io)
- [Contact](mailto:support@openuv.io)
- [Blog](https://www.openuv.io/blog)
- [SDK — openuv-node (community)](https://github.com/aershov24/openuv-node)
- [SDK — pyopenuv (community)](https://github.com/bachya/pyopenuv)
- [Tools — Community OpenUV MCP Server](https://github.com/ag2-mcp-servers/openuv---global-real-time-uv-index-forecast-api)
- [Integrations — Home Assistant](https://www.home-assistant.io/integrations/openuv/)
- [Integrations — openHAB](https://www.openhab.org/addons/bindings/openuv/)
- [Integrations — Homey](https://homey.app/en-us/app/io.openuv/OpenUV/)
- [GitHubOrganization](https://github.com/OpenUV)
- [PublicAPIsListing](https://github.com/public-apis/public-apis)
- [SpectralRules](rules/openuv-rules.yml)
- [Vocabulary](vocabulary/openuv-vocabulary.yml)
- [JSONStructure — Catalog](json-structure/openuv-structure.json)

## Features

| Name | Description |
|------|-------------|
| Real-Time UV Index | Current UV index for any latitude/longitude with ozone-adjusted and cloud-adjusted calculations. |
| UV Forecast | Time-series UV index forecast (hourly) including sun position at each forecast step. |
| Sun Protection Window | Recommended start/end times each day when UV index crosses configurable protection thresholds (default 3.5). |
| Safe Exposure Times | Minutes of safe unprotected sun exposure for all six Fitzpatrick skin types (st1-st6). |
| Ozone Data | Live total column ozone in Dobson units used in the UV calculation. |
| Altitude Adjustment | Optional altitude parameter for elevation-corrected UV readings. |
| Sun Position | Solar azimuth and altitude returned with each UV reading and at each forecast step. |
| API Usage Statistics | Per-key request and cost statistics for today, yesterday, this month and last month. |
| Health Check | Lightweight /status endpoint for uptime checks before making metered requests. |

## Use Cases

| Name | Description |
|------|-------------|
| Weather Apps | Add live UV index, daily UV max and skin-type-specific exposure recommendations to consumer weather apps. |
| Smart Home Automation | Trigger blinds, awnings or wearable reminders when UV crosses a threshold (e.g. via Home Assistant or openHAB). |
| Outdoor Activity Planning | Surface safe-exposure minutes and protection windows in hiking, running, cycling and sailing apps. |
| Sunscreen Reminders | Notify users when to apply or reapply sunscreen based on the protection window endpoint. |
| Solar and Agriculture | Combine UV, ozone and sun position with solar generation or crop UV-stress models. |
| Public Health Research | Aggregate UV exposure data across populations and geographies for skin-cancer research. |
| Travel Advisories | Show destination-specific UV risk to travelers before and during trips. |

## Integrations

| Name | Description |
|------|-------------|
| Home Assistant | Official OpenUV integration providing UV index, max UV, ozone, protection window and safe-exposure sensors. |
| openHAB | openHAB binding for OpenUV exposing UV channels in smart-home rule engines. |
| Homey | Homey app integration for triggering UV-based flows. |
| ioBroker | Community ioBroker adapters (ioBroker.openuv, ioBroker.uv-protect) for the ioBroker IoT platform. |
| RapidAPI | OpenUV is also published on the RapidAPI marketplace. |
| Sulu | OpenUV is listed on the Sulu API platform. |

## Solutions

| Name | Description |
|------|-------------|
| Consumer Weather | Drop-in UV layer for mobile and web weather products. |
| Smart Home | Automation triggers for sun-aware homes and devices. |
| Health and Wellness | Skin-type-aware sun safety nudges for wellness apps. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [OpenUV OpenAPI](openapi/openuv-openapi.yml) — 5 GET operations across UV Index, Protection, and Account

### JSON Schema

- [UV Index](json-schema/openuv-uv-index-schema.json)
- [UV Forecast](json-schema/openuv-uv-forecast-schema.json)
- [Protection Window](json-schema/openuv-protection-window-schema.json)
- [API Statistics](json-schema/openuv-api-statistics-schema.json)

### JSON Structure

- [OpenUV Catalog](json-structure/openuv-structure.json)
- [UV Index](json-structure/openuv-uv-index-structure.json)
- [UV Forecast](json-structure/openuv-uv-forecast-structure.json)
- [Protection Window](json-structure/openuv-protection-window-structure.json)

### JSON-LD

- [OpenUV Context](json-ld/openuv-context.jsonld)

### Examples

- [UV Index](examples/openuv-uv-index-example.json)
- [UV Forecast](examples/openuv-uv-forecast-example.json)
- [Protection Window](examples/openuv-protection-window-example.json)
- [API Statistics](examples/openuv-api-statistics-example.json)
- [API Status](examples/openuv-api-status-example.json)

## Capabilities

Self-contained Naftiko 1.0.0-alpha2 capabilities — each file bundles its consumes block, a REST exposer (port 8080) and an MCP exposer (port 9090) for one OpenAPI tag.

| Capability | File | Operations |
|------------|------|------------|
| UV Index | [openuv-uv-index.yaml](capabilities/openuv-uv-index.yaml) | 2 |
| Protection | [openuv-protection.yaml](capabilities/openuv-protection.yaml) | 1 |
| Account | [openuv-account.yaml](capabilities/openuv-account.yaml) | 2 |

## Vocabulary

- [OpenUV Vocabulary](vocabulary/openuv-vocabulary.yml) — Controlled vocabulary covering 4 domains, 10 concepts, 6 Fitzpatrick skin types, and 5 operations.

## Rules

- [OpenUV Spectral Rules](rules/openuv-rules.yml) — 14 rules enforcing HTTPS, api.openuv.io host, x-access-token API key auth, GET-only surface, Title Case summaries, lat/lng requirements, result envelope, and documented 429 responses.

## Plans

- [OpenUV Plans Pricing](plans/openuv-plans-pricing.yml) — 5 tiers (Free, Hobbyist, Personal, Pro, Enterprise) covering 50 to 15,000 to unlimited daily requests, in API Commons Plans 0.1 format.

## Rate Limits

- [OpenUV Rate Limits](rate-limits/openuv-rate-limits.yml) — Per-tier daily-request quotas in API Commons Rate Limits 0.1 format. Hard cap; 429 on exhaustion.

## FinOps

- [OpenUV FinOps Profile](finops/openuv-finops.yml) — FOCUS 1.3 aligned profile mapping OpenUV's subscription + hard-quota billing model and the /stat-exposed cost meters to the FinOps Framework.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
