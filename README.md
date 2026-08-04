# OpenUV (openuv)

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
