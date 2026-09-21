# Document MCP Server (`my-first-mcp-server`)

A FastMCP server built as part of the Claude Academy Model Context Protocol learning series.

## Overview
This server exposes document management tools to LLM clients (such as Claude Desktop or MCP Inspector).

## Tools
- `read_doc_contents`: Takes a `doc_id` and returns the document content.
- `edit_doc_contents`: Takes `doc_id`, `old_str`, and `new_str` to update document content.

## Running the Server
```bash
.\dev.bat
```
This starts the MCP Inspector to interact with the server.
