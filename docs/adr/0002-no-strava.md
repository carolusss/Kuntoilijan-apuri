# ADR 0002: <no strava>

- **Status:** Accepted
- **Date:** 2026-10-10

## Context
I initially wanted to connect with strava to get suggestions based on training history. Strava API-rules state, though, that API data is not possible to use in AI models and such models. API access now requires a paid developer subscription.

## Decision
Instead we are going to upload FIT/GPX files and demo data through ActivitySource-adapter.

## Alternatives considered
| Option | Pros | Cons |
| --- | --- | --- |
| Using strava | best UX | violates rules |
| Garmin or other vendor | Good UX | needs permission, tied to one vendor |

## Consequences
There is no automatic synchronization. Improvement in compliance and not being tied to one service. With the described adapter easy sources are also easy to add.