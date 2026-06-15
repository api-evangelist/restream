# Restream (restream)

Restream is a multistreaming platform that enables content creators and businesses to simultaneously broadcast live video to 30+ platforms including YouTube, Twitch, Facebook, LinkedIn, and more. The platform offers REST APIs and WebSocket connections for managing streams, channels, events, and chat.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/restream/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/restream/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Broadcast
- Chat
- Content Delivery
- Live Streaming
- Multistreaming
- Video Streaming

## Timestamps

- **Created:** 2025-03-15
- **Modified:** 2026-05-19

## APIs

### Restream API

REST API for managing Restream channels, stream keys, events, and user profiles. Uses OAuth2 authorization code flow for authentication with scopes for profile, channels, streams, events, and chat. Base URL is https://api.restream.io/v2.

- **Human URL:** [https://developers.restream.io](https://developers.restream.io)
- **Base URL:** `https://api.restream.io/v2`

#### Tags

- Channels
- Events
- Live Video
- OAuth2
- Streaming
- Users

#### Properties

- [Documentation](https://developers.restream.io/docs)
- [Authentication](https://developers.restream.io/guide/getting-started)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/restream/refs/heads/main/openapi/restream-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/restream.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/restream.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Restream Streaming Updates API

WebSocket API for real-time streaming status updates. Connect to wss://streaming.api.restream.io/ws with an OAuth access token to receive incoming and outgoing stream events, platform status updates, and viewer counts in real time.

- **Human URL:** [https://developers.restream.io/private-api/streaming-updates](https://developers.restream.io/private-api/streaming-updates)
- **Base URL:** `wss://streaming.api.restream.io`

#### Tags

- Real-Time
- Streaming
- WebSocket

#### Properties

- [Documentation](https://developers.restream.io/private-api/streaming-updates)
- [Postman Collection](collections/restream.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/restream.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Restream Chat API

WebSocket API for accessing and managing Restream Chat. Receive real-time chat messages from all connected streaming platforms (Twitch, YouTube, Facebook, Discord, LinkedIn, DLive) in a unified event stream. Supports reply and relay actions.

- **Human URL:** [https://developers.restream.io/chat/getting-started](https://developers.restream.io/chat/getting-started)
- **Base URL:** `wss://chat.api.restream.io`

#### Tags

- Chat
- Real-Time
- Streaming
- WebSocket

#### Properties

- [Documentation](https://developers.restream.io/chat/getting-started)
- [Postman Collection](collections/restream.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/restream.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/restreamio)
- [Terms of Service](https://restream.io/terms)
- [Privacy Policy](https://restream.io/privacy)
- [Sign Up](https://app.restream.io/sign-up)
- [Login](https://app.restream.io/login)
- [Blog](https://restream.io/blog)
- [Pricing](https://restream.io/pricing)
- [Website](https://restream.io)
- [Developer  Portal](https://developers.restream.io)
- [Authentication](https://developers.restream.io/guide/getting-started)
- [GitHub Organization](https://github.com/restreamio)
- [Integrations](https://restream.io/integrations/)
- [L L Ms Txt](https://developers.restream.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
