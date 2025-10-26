# SecretSweeper-demo
## Why SecretSweeper?
Teams routinely paste logs or snippets into chats/tickets and accidentally leak secrets (API keys, tokens, passwords). **SecretSweeper lets you clean text fields locally**—no servers, no analytics, no CDNs.

- **Client-side only**: Everything happens in the browser via `FileReader` + regex passes.
- **Offline-first**: An optional *Enforce offline mode* toggle disables `fetch`, `XMLHttpRequest`, `WebSocket`, and `sendBeacon`.
- **Strict CSP**:  
  ```text
  default-src 'self'; object-src 'none'; base-uri 'self'; frame-ancestors 'none';
  script-src 'self'; style-src 'self' 'unsafe-inline'; img-src 'self' data:;
