# MCP Security & OAuth 2.1

The threat model around an LLM that can act on behalf of a user — through arbitrary servers — and the spec mechanisms designed to keep it safe. OAuth 2.1, PKCE, RFC 8414 / 7591 / 8707 / 9728 discovery, audience binding, the confused-deputy attack, prompt injection through tool output, tool poisoning, sandboxing, and logging hygiene.

Updated for revision `2026-07-28`: new slide 03b on Client ID Metadata Documents (dynamic client registration is deprecated), `iss` validation (RFC 9207) and issuer-bound credentials; checklist extended. Sources: the [2026-07-28 client-registration page](https://modelcontextprotocol.io/specification/2026-07-28/basic/authorization/client-registration) and [changelog](https://modelcontextprotocol.io/specification/2026-07-28/changelog) (accessed 2026-10-08). Animated companion: [Agent Protocols Explained](https://agent-protocols-explained.vercel.app).

**Live site:** https://brendanjameslynskey.github.io/MCP_04_Security_and_OAuth/

Part of the [Model Context Protocol series](https://github.com/BrendanJamesLynskey/LLMs#model-context-protocol-mcp).
