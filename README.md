# AraraHQ Postman Collection

[![Docs](https://img.shields.io/badge/Docs-docs.ararahq.com-orange)](https://docs.ararahq.com)

Official Postman collection for the [AraraHQ API](https://ararahq.com). Test every endpoint without writing code.

## Quick Start

1. **Import** — Open Postman → Import → drag `AraraHQ.postman_collection.json`
2. **Set API Key** — Go to the collection's Variables tab → set `api_key` to your `ara_live_...` key
3. **Send** — Pick any request and hit Send

## What's Included

| Folder | Endpoints | Description |
|--------|-----------|-------------|
| Messages | 5 | Send templates, freeform, media, scheduled messages |
| Templates | 6 | Create, list, status, analytics, delete |
| Campaigns | 5 | Create, list, estimate cost, CSV import |
| Conversations | 4 | List, history, reply, send template |
| Contacts | 4 | List, get, batch upsert, stats |
| AI Brain | 11 | Knowledge base, rules, sources, audit, analytics |
| API Keys | 4 | Create, list, reveal sandbox, revoke |
| Phone Numbers | 1 | List organization numbers |
| Console | 9 | Wallet, billing, metrics, test messages |
| Webhooks | 1 | Cart abandonment |
| Public | 1 | Health check |

**51 requests** covering all API key-authenticated endpoints.

## Authentication

All requests use Bearer token auth with your API key:

```
Authorization: Bearer ara_live_...
```

Use `ara_test_` keys for sandbox mode — same endpoints, no real messages sent.

## Get Your API Key

1. Sign up at [ararahq.com](https://ararahq.com)
2. Go to Console → API Keys
3. Create a LIVE or TEST key

## License

MIT - [AraraHQ](https://ararahq.com)
