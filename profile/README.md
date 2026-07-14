# Tethro

> Tether your agents. Set them free when they're safe.

The security control plane for autonomous AI coding agents. Sandbox every session, review every diff with live-thread feedback, and sign every action to a human — before a rogue agent touches production.

## Open source (Apache 2.0)

Developer-facing tools. Free forever.

| Repo | What |
|------|------|
| [`tethro-cli`](https://github.com/tethro/tethro-cli) | CLI — `tethro run claude-code "fix the bug"` |
| [`tethro-credential-proxy`](https://github.com/tethro/tethro-credential-proxy) | Credential isolation (agents never see your API keys) |
| [`tethro-mcp-proxy`](https://github.com/tethro/tethro-mcp-proxy) | Local MCP security gateway |
| [`tethro-audit-ws`](https://github.com/tethro/tethro-audit-ws) | Real-time audit event streaming |
| [`tethro-vscode`](https://github.com/tethro/tethro-vscode) | VS Code extension |
| [`homebrew-tap`](https://github.com/tethro/homebrew-tap) | `brew install tethro/tap/tethro` |

## Commercial (source not public)

Everything that protects the company:

- Hosted web console
- Cloud sandbox execution
- SSO / SAML / SCIM
- SIEM integrations
- Long-term audit retention
- Compliance packs (SOC 2 evidence, EU AI Act technical docs)
- Dedicated support + SLA

Local console builds and enterprise on-prem are available under a commercial license — not Apache 2.0.

## Install

```bash
brew install tethro/tap/tethro
# or
npm i -g tethro-cli

tethro doctor
tethro run claude-code "add idempotency to the refund webhook"
```

## Links

- Website: https://tethro.dev
- Docs: https://tethro.dev/docs
- Blog: https://tethro.dev/blog
