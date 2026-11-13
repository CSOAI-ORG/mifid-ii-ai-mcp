[![MCP Scorecard: 90/100](https://img.shields.io/badge/proofof.ai-90%2F100-5b21b6)](https://proofof.ai/scorecard/mifid-ii-ai-mcp.html)

# Mifid Ii Ai MCP

[![MEOK AI Labs](https://img.shields.io/badge/MEOK-AI%20Labs-667eea)](https://meok.ai)
[![GSPC](https://img.shields.io/badge/GSPC-UNMEASURED-9ca3af)](https://councilof.ai/api/gspc)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![PyPI](https://img.shields.io/badge/PyPI-Install-3775a9)](https://pypi.org/project/mifid_ii_ai_mcp/)
mcp-name: io.github.CSOAI-ORG/mifid-ii-ai-mcp

# MiFID II AI / Algorithmic Trading Compliance MCP


> **Signed attestations + unlimited audits + email support.**
> 👉 **[Subscribe at meok.ai](https://meok.ai/pricing)** — instant HMAC signing key + Stripe-managed billing.
>

[![PyPI](https://img.shields.io/pypi/v/mifid-ii-ai-mcp)](https://pypi.org/project/mifid-ii-ai-mcp/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![MEOK AI Labs](https://img.shields.io/badge/MEOK_AI_Labs-governance--mcp-purple)](https://meok.ai)

> MiFID II Article 17 algorithmic trading compliance MCP

MiFID II Article 17 algorithmic trading compliance MCP. MIT

---

## 🚀 Quick Start

```bash
# Install via pip
pip install mifid_ii_ai_mcp

# Or install via Smithery
npx -y @smithery/cli@latest install mifid-ii-ai-mcp --client claude
```

## ✨ Features

- MCP protocol compliant
- Easy installation
- Well-documented API
- Production-ready
- Active maintenance

## 📖 Documentation

- [Full Documentation](https://docs.meok.ai/mifid-ii-ai-mcp)
- [API Reference](https://api.meok.ai)
- [EU AI Act Compliance Guide](https://councilof.ai/compliance)

## 🛡️ Compliance

This MCP server is built with **EU AI Act compliance** built-in:
- **Free**: 10 calls/day. No API key required.

- ✅ Article 9 — Risk Management System
- ✅ Article 13 — Transparency & Instructions for Use
- ✅ Article 15 — Bias Detection & Testing
- ✅ Article 26 — FRIA Support (where applicable)
- ✅ Article 50 — AI Content Watermarking (where applicable)

Need help getting compliant? **[Book a free 15-min diagnostic →](https://cal.com/csoai/august-audit)**

## How MEOK charges

MEOK has no subscriptions and no tiers. You pay per job, and only when the agreed artifact has been delivered to you. There is no public price list. See <https://meok.ai/pricing>.

This repository's source is MIT-licensed and free to self-host.

## 🤝 Part of the MEOK Ecosystem

This server is part of the **[MEOK AI Labs](https://meok.ai)** ecosystem — 300+ MCP servers for sovereign AI governance.

| Domain | Purpose |
|--------|---------|
| [councilof.ai](https://councilof.ai) | EU AI Act compliance marketplace |
| [safetyof.ai](https://safetyof.ai) | AI safety & monitoring |
| [meok.ai](https://meok.ai) | Sovereign AI platform |
| [cobolbridge.ai](https://cobolbridge.ai) | Legacy modernization |

## 📜 License

MIT © [CSOAI-ORG](https://github.com/CSOAI-ORG)

---

<p align="center">
  <sub>Built with 💜 by <a href="https://meok.ai">MEOK AI Labs</a> · UK Companies House 16939677</sub>
</p>
<!-- mcp-name: io.github.CSOAI-ORG/mifid-ii-ai-mcp -->



## Configuration

Add to your `claude_desktop_config.json` (Claude Desktop) or your MCP client config:

```json
{
  "mcpServers": {
    "mifid-ii-ai-mcp": {
      "command": "uvx",
      "args": ["mifid-ii-ai-mcp"]
    }
  }
}
```

Or: `pip install mifid-ii-ai-mcp` then run the `mifid-ii-ai-mcp` command (stdio transport).

## Examples

Once configured, ask your assistant, for example:
- "Use `classify_algo_strategy` to …"
- "Use `rts_6_testing` to …"
- "Use `best_execution_audit` to …"
