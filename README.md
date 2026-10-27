# facebook-mcp-server — Facebook Page management via MCP + Graph API

> An MCP server that exposes Facebook Page tools to any AI agent — create posts, moderate comments, fetch insights, and filter negative feedback through the Graph API.

[![OpenClaw Skill](https://img.shields.io/badge/OpenClaw-Skill-blueviolet)](https://github.com/NachaFromMars)

## Overview
facebook-mcp-server is a Model Context Protocol server that wraps Facebook Graph API operations for Page management. It exposes structured tools that agents can call to create posts, moderate comments, fetch page and post insights, and filter out negative feedback. Requires a Facebook Graph API token with appropriate Page permissions and Python 3.x.

## Features
- **Create posts** — publish content to managed Pages
- **Moderate comments** — list, hide, and manage comments
- **Fetch insights** — page and post performance metrics
- **Filter negative feedback** — identify and handle unwanted content
- **MCP protocol** — works with any MCP-compatible AI agent

## Usage / Quick Start
```bash
# Set your Graph API token
export FACEBOOK_PAGE_TOKEN="your-token-here"

# Run the MCP server
python3 server.py
```
Requires: Facebook Graph API token with Page permissions.

## Trigger Keywords (OpenClaw)
Facebook page MCP, manage Facebook page programmatically, Facebook Graph API, post to Facebook page, moderate comments

## Related Skills
- [facebook-page-manager](https://github.com/NachaFromMars/facebook-page-manager) — Node.js Graph API page manager
- [facebook-humanmode](https://github.com/NachaFromMars/facebook-humanmode) — browser-based Facebook automation

---
Part of the [NachaFromMars](https://github.com/NachaFromMars) OpenClaw skill ecosystem.
