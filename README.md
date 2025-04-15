# MCP Configuration

This repository contains my Model Context Protocol (MCP) configuration for Cursor IDE.

## Configured Servers

- GitHub MCP Server
- Brave Search MCP Server
- Filesystem MCP Server
- Sequential Thinking MCP Server

## Setup

1. Copy the `mcp.json` file to your Cursor configuration directory (`.cursor/mcp.json`)
2. Update the environment variables with your own API keys:
   - `GITHUB_PERSONAL_ACCESS_TOKEN`: Your GitHub Personal Access Token
   - `BRAVE_API_KEY`: Your Brave Search API Key
3. Restart Cursor

## Note

Make sure to keep your API keys secure and never commit them directly to version control. The configuration file in this repository has placeholder values that need to be replaced with your actual API keys.