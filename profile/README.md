# Tethro

> Tether your agents. Set them free when they're safe.

The security control plane for autonomous AI coding agents. Sandbox every session in a microVM, review every diff with live-thread feedback, and sign every action to a human — before a rogue agent touches production.

## What's here

| Repo | What |
|------|------|
| [`tethro`](https://github.com/tethro/tethro) | Web console + landing page + docs + blog |
| [`tethro-cli`](https://github.com/tethro/tethro-cli) | CLI — `tethro run claude-code "fix the bug"` |
| [`tethro-mcp-proxy`](https://github.com/tethro/tethro-mcp-proxy) | MCP security gateway with dynamic tool registration |
| [`tethro-credential-proxy`](https://github.com/tethro/tethro-credential-proxy) | Credential isolation proxy (agents never see your keys) |
| [`tethro-audit-ws`](https://github.com/tethro/tethro-audit-ws) | Real-time audit log streaming |
| [`tethro-vscode`](https://github.com/tethro/tethro-vscode) | VS Code extension |

## Install

```bash
brew install tethro/tap/tethro
tethro doctor
```

## Quickstart

```bash
tethro run claude-code "add idempotency to the refund webhook"
```

## License

Apache 2.0 — CLI, proxies, and WebSocket service are open source.
The hosted console and enterprise features (SSO, SIEM, compliance) are commercial.

## Links

- Website: https://tethro.dev
- Docs: https://tethro.dev/docs
- Blog: https://tethro.dev/blog
