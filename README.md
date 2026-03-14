# carapace-docs

![Carapace](site/assets/carapace-logo.png)

Public documentation source for the Carapace ecosystem.

Support Carapace on Patreon: <https://www.patreon.com/carapacehq>

## What Carapace Is

Carapace helps developers and operators detect suspicious or abusive agent behavior before it becomes a production incident.

The first slice is intentionally narrow:

- shared event schemas for AI-facing API telemetry
- JavaScript middleware that emits normalized events
- transparent starter rules that flag suspicious behavior
- a local-first demo loop that shows detections and policy actions

## First Package

The first package target is `@carapacehq/express`.

That package will capture request and auth telemetry from an Express app, align it with the shared schemas, and hand it to local scoring and policy hooks.

## Repo Map

- [`carapace-schemas`](https://github.com/CarapaceHQ/carapace-schemas): canonical event schemas and telemetry contracts
- [`carapace-js`](https://github.com/CarapaceHQ/carapace-js): JavaScript packages and middleware, starting with `@carapacehq/express`
- [`carapace-detection-rules`](https://github.com/CarapaceHQ/carapace-detection-rules): maintained starter rules and scoring semantics
- [`carapace-playground`](https://github.com/CarapaceHQ/carapace-playground): local demo app and suspicious-vs-normal traffic examples
- [`carapace-docs`](https://github.com/CarapaceHQ/carapace-docs): public docs, quick starts, and architecture overviews

## Current State

The repo surfaces are live. The `draft-source/` directory contains extracted material that still needs cleanup before it becomes polished public documentation.

## Near-Term Milestones

1. Publish a concise quick start for the first local demo loop.
2. Add docs for the first supported event set and starter rules.
3. Keep the public docs aligned with the narrow first implementation slice.

## License

Apache-2.0
