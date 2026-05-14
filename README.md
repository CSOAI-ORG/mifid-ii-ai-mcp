# MiFID II AI / Algorithmic Trading Compliance MCP

[![PyPI](https://img.shields.io/pypi/v/mifid-ii-ai-mcp)](https://pypi.org/project/mifid-ii-ai-mcp/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![MEOK AI Labs](https://img.shields.io/badge/MEOK_AI_Labs-governance--mcp-purple)](https://meok.ai)

MiFID II Article 17 algorithmic trading + RTS 6 testing/risk controls + best execution AI compliance for investment firms.

## Install

```bash
pip install mifid-ii-ai-mcp
```

## Tools

| Tool | Purpose |
|------|---------|
| `classify_algo_strategy` | Algo trading strategy classification (DEA, HFT, market making) |
| `rts_6_testing` | RTS 6 algo testing + risk-control + circuit-breaker requirements |
| `best_execution_audit` | Best execution policy audit per Article 27 |
| `market_abuse_overlay` | MAR Reg (EU) 596/2014 + algo flagging |
| `hft_notification` | HFT notification to home competent authority |

## Pairs with

- `meok-attestation-api` — POST results to https://meok-attestation-api.vercel.app/sign for cryptographically signed compliance certs
- `meok-attestation-verify` — public verification of any MEOK-signed cert
- Other MEOK governance MCPs via SOV3 `mcp_bridge_call`

## Pricing

- **Free**: 10 calls/day. No API key required.
- **Pro** £79/mo: unlimited + signed attestations. [Subscribe](https://buy.stripe.com/14A4gB3K4eUWgYR56o8k836)
- **Enterprise** £1,499/mo: white-label + on-premise + SLA. hello@meok.ai

## Status

Scaffold v1.0.0 ships the MCP framework + 5 tool stubs. v1.1.0 will add real regulation data ingestion.

If your team needs this MCP fully-loaded faster, ping hello@meok.ai for sponsored development.

## License

MIT © MEOK AI Labs

<!-- mcp-name: io.github.CSOAI-ORG/mifid-ii-ai-mcp -->
