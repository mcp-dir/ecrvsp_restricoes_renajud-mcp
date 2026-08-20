# Instalação detalhada

ECRVSP Restrições: Bloqueios Judiciais RENAJUD é um servidor MCP remoto. Aponte seu cliente pra `https://api.mcp.ai/p_ecrvsp_restricoes_renajud`. Snippets rápidos: [INSTALL.md](../INSTALL.md).

| Cliente | URL | Auth |
|---|---|---|
| Claude Desktop | `https://api.mcp.ai/p_ecrvsp_restricoes_renajud` | OAuth 2.1 ou agent-auth |
| Cursor | `https://api.mcp.ai/p_ecrvsp_restricoes_renajud` | OAuth 2.1 ou agent-auth |
| VS Code (Copilot) | `https://api.mcp.ai/p_ecrvsp_restricoes_renajud` | OAuth 2.1 ou agent-auth |

A config JSON é a mesma em todos: só a URL, sem headers.

## Desinstalar

Remova o bloco `mcpServers.ecrvsp_restricoes_renajud` (ou `servers.ecrvsp_restricoes_renajud` no VS Code) do config do cliente e reinicie.
