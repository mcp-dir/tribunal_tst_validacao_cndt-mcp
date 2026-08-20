# Instalação detalhada

Tribunal TST: Validação de CNDT é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_tribunal_tst_validacao_cndt`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_tribunal_tst_validacao_cndt` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_tribunal_tst_validacao_cndt` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_tribunal_tst_validacao_cndt` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.tribunal_tst_validacao_cndt` (ou `servers.tribunal_tst_validacao_cndt` no VS Code) do config do cliente e reinicie.
