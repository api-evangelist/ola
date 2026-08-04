# Ola

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

India's leading ride-sharing and mobility platform with developer APIs for ride booking, tracking, corporate travel management, and AI-powered geospatial services.

**Developer Portal:** https://developers.olacabs.com/  
**Ola Maps:** https://maps.olakrutrim.com/

## APIs

| API | Description |
|-----|-------------|
| [Ola Ride Booking API](https://developers.olacabs.com/docs/overview) | Find, estimate fares, and book rides across 100+ Indian cities |
| [Ola Ride Tracking API](https://developers.olacabs.com/docs/cab-track-ride) | Real-time driver location and booking status via polling or webhooks |
| [Ola Ride Management API](https://developers.olacabs.com/docs/overview) | Trip history, cancellation, and feedback |
| [Ola Corporate API](https://corporate.olacabs.com/docs/overview) | Enterprise user, ride, and expense code management |
| [Ola Maps API](https://maps.olakrutrim.com/docs) | Routing, geocoding, places search, and map tiles optimized for India |

## Authentication

- **Ride APIs:** OAuth 2.0 bearer tokens via Ola's login/signup flow (invite-only affiliate access)
- **Corporate API:** `X-CORPORATE-TOKEN` header (issued by Ola corporate team)
- **Ola Maps:** API key (query parameter) or OAuth 2.0 client credentials

## Access

Ride APIs are **invite-only** — email affiliates@olacabs.com to request affiliate access and sandbox credentials. Ola Maps is **self-serve** via Krutrim Cloud (cloud.olakrutrim.com).

## Pricing

- **Ola Maps:** Free up to 500K API calls/month (5M/month promotional); usage-based above threshold at ~50% of Google Maps rates
- **Ride APIs:** Partner agreement (contact affiliates@olacabs.com)
- **Corporate API:** Enterprise agreement (contact corp_apisupport@olacabs.com)

## Rate Limits

- **Corporate API:** 1,000 requests per minute; HTTP 429 on breach
- **Ola Maps:** Monthly free-tier cap + per-minute throttle; HTTP 429 on breach
- **Ride APIs:** Governed by partner agreement

## Support

- Ride API partners: affiliates@olacabs.com
- Corporate API: corp_apisupport@olacabs.com
- Ola Maps: support@olakrutrim.com | sales@olakrutrim.com
