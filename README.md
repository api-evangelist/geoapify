# Geoapify (geoapify)

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

Geoapify Location Platform APIs for location-based services and mapping solutions.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/geoapify/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/geoapify/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Geocoding
- Geospatial
- Location
- Maps

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Map Tiles API

Retrieve map tiles for various types and styles.

- **Human URL:** [https://apidocs.geoapify.com/maps/map-tiles](https://apidocs.geoapify.com/maps/map-tiles)
- **Base URL:** `https://maps.geoapify.com/maptiles`

#### Tags

- Maps

#### Properties

- [Documentation](https://apidocs.geoapify.com/maps/map-tiles)
- [Postman Collection](collections/geoapify-forward-geocoding-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/geoapify-forward-geocoding-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Static Maps API

Generate static map images for embedding in applications.

- **Human URL:** [https://apidocs.geoapify.com/maps/static-maps-api](https://apidocs.geoapify.com/maps/static-maps-api)
- **Base URL:** `https://maps.geoapify.com/staticmap`

#### Tags

- Maps

#### Properties

- [Documentation](https://apidocs.geoapify.com/maps/static-maps-api)
- [Postman Collection](collections/geoapify-forward-geocoding-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/geoapify-forward-geocoding-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Forward Geocoding API

Convert addresses into geographic coordinates.

- **Human URL:** [https://apidocs.geoapify.com/addresses-location/forward-geocoding-api](https://apidocs.geoapify.com/addresses-location/forward-geocoding-api)
- **Base URL:** `https://api.geoapify.com/geocode/search`

#### Tags

- Geocoding

#### Properties

- [Documentation](https://apidocs.geoapify.com/addresses-location/forward-geocoding-api)
- [OpenAPI](openapi/geoapify-forward-geocoding-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/geoapify-forward-geocoding-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/geoapify-forward-geocoding-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Reverse Geocoding API

Convert geographic coordinates into addresses.

- **Human URL:** [https://apidocs.geoapify.com/addresses-location/reverse-geocoding-api](https://apidocs.geoapify.com/addresses-location/reverse-geocoding-api)
- **Base URL:** `https://api.geoapify.com/geocode/reverse`

#### Tags

- Geocoding

#### Properties

- [Documentation](https://apidocs.geoapify.com/addresses-location/reverse-geocoding-api)
- [Postman Collection](collections/geoapify-forward-geocoding-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/geoapify-forward-geocoding-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Address Autocomplete API

Address autocomplete suggestions for search fields.

- **Human URL:** [https://apidocs.geoapify.com/addresses-location/address-autocomplete](https://apidocs.geoapify.com/addresses-location/address-autocomplete)
- **Base URL:** `https://api.geoapify.com/geocode/autocomplete`

#### Tags

- Geocoding

#### Properties

- [Documentation](https://apidocs.geoapify.com/addresses-location/address-autocomplete)
- [Postman Collection](collections/geoapify-forward-geocoding-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/geoapify-forward-geocoding-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IP Geolocation API

Identify the location of an IP address.

- **Human URL:** [https://apidocs.geoapify.com/addresses-location/ip-geolocation-api](https://apidocs.geoapify.com/addresses-location/ip-geolocation-api)
- **Base URL:** `https://api.geoapify.com/geocode/ip`

#### Tags

- Geolocation

#### Properties

- [Documentation](https://apidocs.geoapify.com/addresses-location/ip-geolocation-api)
- [Postman Collection](collections/geoapify-forward-geocoding-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/geoapify-forward-geocoding-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Routing API

Provides routing directions between multiple points.

- **Human URL:** [https://apidocs.geoapify.com/routes-optimization/routing-api](https://apidocs.geoapify.com/routes-optimization/routing-api)
- **Base URL:** `https://api.geoapify.com/routing`

#### Tags

- Routing

#### Properties

- [Documentation](https://apidocs.geoapify.com/routes-optimization/routing-api)
- [Postman Collection](collections/geoapify-forward-geocoding-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/geoapify-forward-geocoding-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Places API

Discover places based on various categories and parameters.

- **Human URL:** [https://apidocs.geoapify.com/places-details/places-api](https://apidocs.geoapify.com/places-details/places-api)
- **Base URL:** `https://api.geoapify.com/places`

#### Tags

- Places

#### Properties

- [Documentation](https://apidocs.geoapify.com/places-details/places-api)
- [Postman Collection](collections/geoapify-forward-geocoding-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/geoapify-forward-geocoding-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Boundaries API

Retrieve boundary data for administrative regions.

- **Human URL:** [https://apidocs.geoapify.com/boundaries/about-boundaries-api](https://apidocs.geoapify.com/boundaries/about-boundaries-api)
- **Base URL:** `https://api.geoapify.com/boundaries`

#### Tags

- Boundaries

#### Properties

- [Documentation](https://apidocs.geoapify.com/boundaries/about-boundaries-api)
- [Postman Collection](collections/geoapify-forward-geocoding-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/geoapify-forward-geocoding-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Isoline API

Generate isolines to represent reachable areas.

- **Human URL:** [https://apidocs.geoapify.com/reachability/isolines](https://apidocs.geoapify.com/reachability/isolines)
- **Base URL:** `https://api.geoapify.com/isolines`

#### Tags

- Reachability

#### Properties

- [Documentation](https://apidocs.geoapify.com/reachability/isolines)
- [Postman Collection](collections/geoapify-forward-geocoding-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/geoapify-forward-geocoding-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/geoapify)
- [LinkedIn](https://www.linkedin.com/company/geoapify)
- [Website](https://www.geoapify.com/)
- [Documentation](https://apidocs.geoapify.com/)
- [Sign Up](https://myprojects.geoapify.com/register)
- [Terms of Service](https://www.geoapify.com/terms)
- [Privacy Policy](https://www.geoapify.com/privacy)
- [Features](undefined)
- [L L Ms Txt](https://apidocs.geoapify.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
