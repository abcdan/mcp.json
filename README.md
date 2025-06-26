# mcp.json 🤖
This repository contains my Model Context Protocol (MCP) server configurations for both professional and personal use. These configurations are compatible with Cursor, Claude.ai, and Claude Code.

## Prerequisites
Before setting up MCP servers, ensure you have:

- **Node.js**: A recent version (recommended: v18 or higher)
- **Figma API Key**: Required for Figma integration
  - Follow the [official Figma guide](https://help.figma.com/hc/en-us/articles/8085703771159-Manage-personal-access-tokens) to generate your personal access token
- **Cursor**: A license
- **Claude.ai**: A license, preferably Max 5x.

## Installation & Setup

### Cursor IDE Setup
1. Open the command palette using `Cmd+P` (Mac) or `Ctrl+P` (Windows/Linux)
2. Type `>MCP` in the command palette
3. Copy and paste the contents from the `mcp.json` file into the configuration

<img width="240" alt="Cursor MCP Setup" src="https://github.com/user-attachments/assets/038d90f2-7b09-413f-8f4c-3d2a5ae3bb06" />

### Claude.ai Setup
#### Configuring Atlassian Integration
1. Navigate to the MCP settings in Claude.ai
2. Locate the Atlassian integration option
3. Click the **Connect** button to authenticate your account

![Atlassian Integration Setup](https://github.com/user-attachments/assets/b61c85dd-a2fa-432d-898b-b709f7358c81)

### Claude Code Setup

To add the browser MCP server to Claude Code, run the following command in your terminal:

```bash
claude mcp add browser npx @browsermcp/mcp@latest -s user
```

## Configuration File

The `mcp.json` file contains all server configurations. Make sure to review and customize the settings according to your needs before applying them to your development environment.

## Support

If you encounter any issues during setup, please refer to the official documentation for each tool:
- [Cursor Documentation](https://cursor.sh/docs)
- [Claude.ai Help Center](https://support.anthropic.com)
- [MCP Protocol Documentation](https://modelcontextprotocol.io)

## Contributing
Feel free to suggest me new tools through the issues tab :)
