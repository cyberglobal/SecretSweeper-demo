# SecretSweeper-Showcase
## Why SecretSweeper?
Teams routinely paste logs or snippets into chats or ticketing systems and accidentally leak secrets (API keys, tokens, passwords). **SecretSweeper lets you clean text fields locally** with zero network communication.

---

## Why it is safe

- **Client-side only**  
  Everything happens in the browser via `FileReader` and controlled regex passes.
- **Offline-first**  
  *Enforce Offline Mode* disables `fetch`, `XMLHttpRequest`, `WebSocket`, and `sendBeacon`.
- **Strict CSP**  
