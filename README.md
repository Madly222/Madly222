### Self-hosted AI tooling for network operations, customer support, procurement and documents

Claude models do the reading and reasoning; plain code does everything that must be exact.
Each project ships with its deployment files (systemd or Docker) and is documented with screenshots.

| Project | What it does | Stack |
|---|---|---|
| [**MCPforMonitoring**](https://github.com/Madly222/MCPforMonitoring) | ISP network operations: watches a Linux server fleet over SSH, GPON ONU monitoring, NetBox auto-fill, plain-language commands interpreted by Claude, and a read-only MCP server for Claude Desktop / Claude Code | Python · FastAPI · Claude API · MCP · asyncssh · SNMP |
| [**mcp4tender**](https://github.com/Madly222/mcp4tender) | Collects public tenders every day, reads their documents and tells which ones the company can win and at what margin; worker / verifier LLM stages, margins computed in code | Python · FastAPI · SQLite · Claude API · PyMuPDF |
| [**voice_responder_AI**](https://github.com/Madly222/voice_responder_AI) | Voice agent for an ISP support line in Romanian and Russian: FAQ answers, billing lookup, SSH diagnostics of the subscriber's switch, a Telegram report for every call | Asterisk · Ultravox · Node.js · Python / Flask · Docker |
| [**pdf-display**](https://github.com/Madly222/pdf-display) | PDF embedding for client websites with per-site access rules, plus in-memory Word / Excel / PowerPoint preview for Odoo 18 | Python · FastAPI · PDF.js · LibreOffice · nginx |

Screenshots in every repository use made-up demo data.
