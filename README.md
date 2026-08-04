# Particle Space (particle-space)

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

Particle Space is proptech infrastructure that exposes real-estate and property data through a REST API, Dashboard, SDKs, and white-labeled UIs. The platform provides real-time access to millions of properties for sale, rent, and off-market - property records, address and property search, valuations, comparables, and listings - using publishable and secret API keys with live and test modes.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/particle-space/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/particle-space/refs/heads/main/apis.yml)

> Note: Particle Space (real estate / property data) is a distinct company from Particle / particle.io (the IoT device cloud) and from mParticle (a customer data platform). This catalog covers Particle Space only. The OpenAPI and the plans, rate-limits, and finops artifacts model Particle Space's documented product areas and are marked unreconciled pending verification against the live API reference at docs.particlespace.com.

## Tags

- Real Estate
- Property Data
- PropTech
- Listings
- Valuations

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Particle Space Property Records API

Resource-oriented access to property records and detailed attributes for residential properties across the United States. Modeled from Particle Space's documented data-platform product; exact resource paths to be confirmed against the live API reference.

- **Human URL:** [https://docs.particlespace.com/docs/intro/](https://docs.particlespace.com/docs/intro/)
- **Base URL:** `https://api.particlespace.com`

#### Tags

- Property Records
- Property Details
- Real Estate

#### Properties

- [Documentation](https://docs.particlespace.com/docs/intro/)
- [OpenAPI](openapi/particle-space-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/particle-space.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/particle-space.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Particle Space Address Search API

Search and look up properties by address or query, resolving an address to a property record for downstream records, valuations, and listings lookups. Modeled from Particle Space's documented data-platform product.

- **Human URL:** [https://docs.particlespace.com/docs/intro/](https://docs.particlespace.com/docs/intro/)
- **Base URL:** `https://api.particlespace.com`

#### Tags

- Address Search
- Autocomplete
- Geocoding

#### Properties

- [Documentation](https://docs.particlespace.com/docs/intro/)
- [OpenAPI](openapi/particle-space-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/particle-space.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/particle-space.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Particle Space Valuations API

Automated valuation model (AVM) estimates for property value and rent for a given property or address. Modeled from Particle Space's documented data-platform product; specific estimate fields to be confirmed against the live API reference.

- **Human URL:** [https://docs.particlespace.com/docs/intro/](https://docs.particlespace.com/docs/intro/)
- **Base URL:** `https://api.particlespace.com`

#### Tags

- AVM
- Valuations
- Estimates

#### Properties

- [Documentation](https://docs.particlespace.com/docs/intro/)
- [OpenAPI](openapi/particle-space-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/particle-space.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/particle-space.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Particle Space Comparables API

Comparable properties (comps) for a subject property to support valuation, underwriting, and pricing workflows. Modeled from Particle Space's documented data-platform product.

- **Human URL:** [https://docs.particlespace.com/docs/intro/](https://docs.particlespace.com/docs/intro/)
- **Base URL:** `https://api.particlespace.com`

#### Tags

- Comps
- Comparables
- Market Data

#### Properties

- [Documentation](https://docs.particlespace.com/docs/intro/)
- [OpenAPI](openapi/particle-space-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/particle-space.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/particle-space.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Particle Space Listings API

Real-time access to property listings for sale, for rent, and off-market, the core of Particle Space's real-estate data platform. Modeled from Particle Space's documented data-platform product.

- **Human URL:** [https://docs.particlespace.com/docs/intro/](https://docs.particlespace.com/docs/intro/)
- **Base URL:** `https://api.particlespace.com`

#### Tags

- Listings
- For Sale
- For Rent
- Off-Market

#### Properties

- [Documentation](https://docs.particlespace.com/docs/intro/)
- [OpenAPI](openapi/particle-space-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/particle-space.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/particle-space.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/particlespace)
- [LinkedIn](https://www.linkedin.com/company/particle-space)
- [Website](https://particlespace.com/)
- [Documentation](https://docs.particlespace.com/)
- [Plans](plans/particle-space-plans-pricing.yml)
- [Rate Limits](rate-limits/particle-space-rate-limits.yml)
- [Fin Ops](finops/particle-space-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
