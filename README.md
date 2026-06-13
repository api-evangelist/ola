# Ola

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
