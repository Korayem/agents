---
"@cloudflare/think": minor
---

Add `TurnConfig.onError`, forwarded to `streamText`, so a turn's stream errors can be logged without the AI SDK's default `console.error` of the raw error. See [Lifecycle hooks](https://github.com/cloudflare/agents/blob/main/docs/think/lifecycle-hooks.md).
