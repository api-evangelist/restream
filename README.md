# Restream

Restream is a multistreaming platform that enables content creators and businesses to simultaneously broadcast live video to 30+ platforms including YouTube, Twitch, Facebook, LinkedIn, and more. The platform provides REST APIs and WebSocket connections for managing streams, channels, events, and chat.

**Human URL:** [https://restream.io](https://restream.io)
**Developer Portal:** [https://developers.restream.io](https://developers.restream.io)
**Base URL:** `https://api.restream.io/v2`

## APIs

### Restream API (REST)

REST API for managing Restream channels, stream keys, events, and user profiles. Uses OAuth2 authorization code flow with scopes for profile, channels, streams, events, and chat.

- **Documentation:** [https://developers.restream.io/docs](https://developers.restream.io/docs)
- **Authentication:** [OAuth2 Authorization Code](https://developers.restream.io/guide/getting-started)
- **OpenAPI:** [openapi/restream-openapi.yml](openapi/restream-openapi.yml)

### Restream Streaming Updates API (WebSocket)

Real-time WebSocket stream for incoming/outgoing stream events and viewer statistics. Connect to `wss://streaming.api.restream.io/ws?accessToken={token}`.

- **Documentation:** [https://developers.restream.io/private-api/streaming-updates](https://developers.restream.io/private-api/streaming-updates)

### Restream Chat API (WebSocket)

WebSocket API for unified chat across all connected streaming platforms (Twitch, YouTube, Facebook, Discord, LinkedIn, DLive). Supports real-time message relay and reply actions.

- **Documentation:** [https://developers.restream.io/chat/getting-started](https://developers.restream.io/chat/getting-started)

## Common Properties

| Type | URL |
|------|-----|
| Website | https://restream.io |
| Developer Portal | https://developers.restream.io |
| Sign Up | https://app.restream.io/sign-up |
| Login | https://app.restream.io/login |
| Blog | https://restream.io/blog |
| Pricing | https://restream.io/pricing |
| Terms of Service | https://restream.io/terms |
| Privacy Policy | https://restream.io/privacy |
| GitHub Organization | https://github.com/restreamio |

## Artifacts

### OpenAPI Specifications

| File | Description |
|------|-------------|
| [openapi/restream-openapi.yml](openapi/restream-openapi.yml) | Restream REST API v2 — channels, events, stream keys, platforms |

### JSON Schemas

| File | Description |
|------|-------------|
| [json-schema/restream-channel-schema.json](json-schema/restream-channel-schema.json) | Channel object schema |
| [json-schema/restream-event-schema.json](json-schema/restream-event-schema.json) | Event object schema |
| [json-schema/restream-platform-schema.json](json-schema/restream-platform-schema.json) | Platform object schema |

### JSON Structures

| File | Description |
|------|-------------|
| [json-structure/restream-channel-structure.json](json-structure/restream-channel-structure.json) | Channel data structure |
| [json-structure/restream-event-structure.json](json-structure/restream-event-structure.json) | Event data structure |

### JSON-LD Context

| File | Description |
|------|-------------|
| [json-ld/restream-context.jsonld](json-ld/restream-context.jsonld) | JSON-LD context mapping Restream vocabulary to schema.org |

### Examples

| File | Description |
|------|-------------|
| [examples/restream-list-platforms-example.json](examples/restream-list-platforms-example.json) | List all platforms |
| [examples/restream-get-channel-example.json](examples/restream-get-channel-example.json) | Get a channel by ID |
| [examples/restream-get-stream-key-example.json](examples/restream-get-stream-key-example.json) | Retrieve stream key and SRT URL |
| [examples/restream-refresh-token-example.json](examples/restream-refresh-token-example.json) | Refresh OAuth2 access token |

### Spectral Rules

| File | Description |
|------|-------------|
| [rules/restream-rules.yml](rules/restream-rules.yml) | Spectral ruleset enforcing Restream API conventions |

### Capabilities

| File | Description |
|------|-------------|
| [capabilities/multistream-management.yaml](capabilities/multistream-management.yaml) | Multistream management workflow — channels, events, stream keys |
| [capabilities/shared/restream-api.yaml](capabilities/shared/restream-api.yaml) | Shared Restream REST API capability definition |

### Vocabulary

| File | Description |
|------|-------------|
| [vocabulary/restream-vocabulary.yml](vocabulary/restream-vocabulary.yml) | Domain vocabulary for Restream multistreaming concepts |

## Authentication

Restream uses **OAuth2 Authorization Code** flow. Key details:

- **Authorization URL:** `https://api.restream.io/oauth/authorize`
- **Token URL:** `https://api.restream.io/oauth/token`
- **Access Token Expiry:** 1 hour
- **Refresh Token Expiry:** 1 year
- **Key Scopes:** `profile.read`, `channels.read`, `channels.write`, `stream.read`, `events.read`, `events.write`, `chat.read`

## Maintainers

- **Kin Lane** — kin@apievangelist.com
