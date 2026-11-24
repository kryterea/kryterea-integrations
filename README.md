# Kryterea integrations

This repository contains installation materials for Kryterea's hosted MCP server. Cursor and Replit connectivity are under staging evaluation.

## Cursor Desktop

The Cursor package contains the plugin manifest, remote MCP configuration and Kryterea logo. A pilot operator supplies the MCP URL and the explicitly registered public OAuth client ID through the plugin settings. The OAuth client ID is an identifier. Sign in to Kryterea to authorize the connection and use a project grant for the fictional staging project.

For a local pilot using Cursor's MCP settings directly, use a project or user-level mcp.json and configure the same URL, client ID and scopes. See [Cursor's remote MCP OAuth documentation](https://cursor.com/docs/mcp#static-oauth-for-remote-servers).

The first acceptance test is a model-driven read of the pinned work brief, followed by a fresh read denied after the grant is revoked.

## Replit Agent

Replit connects to remote MCP servers through [its custom MCP setup](https://docs.replit.com/build/connect-via-mcp). The staging connection failed during initialization before OAuth consent. The Replit install link will be added after the OAuth flow is verified.

## Logo

[Blue Kryterea symbol](assets/logo.png)
