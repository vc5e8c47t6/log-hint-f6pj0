# log-hint

Compress a test failure log into short next steps. Core tool is local.

```bash
node bin/log-hint.js ./failed.log
node bin/log-hint.js ./failed.log --tail 80
```

MIT

> **Hands-on:** set `OPENAI_BASE_URL` to a compatible relay — I test with [59API](https://59api.com) (`https://59api.com/v1`). Prefer compatibility over hype; keep official API as rollback.
