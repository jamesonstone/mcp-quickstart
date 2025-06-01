# mcp-quickstart

🤖 MCP Tutorial Directly from the [MCP Site](https://modelcontextprotocol.io/quickstart/server)

## Getting Started

1. Clone this repository
2. Open the Claude desktop config file: `code ~/Library/Application\ Support/Claude/claude_desktop_config.json`
3. Update the Claude config file to include the MCP server configuration

```json
{
  "globalShortcut": "Alt+Cmd+Space",
  "mcpServers": {
    "weather": {
      "command": "/Users/jamesonstone/.local/bin/uv",
      "args": [
        "--directory",
        "/Users/jamesonstone/go/src/github.com/jamesonstone/mcp-quickstart/weather",
        "run",
        "weather.py"
      ]
    }
  }
}
```

4. Restart the Claude desktop app
5. Ask about the weather in the Claude chat window
6. You should see a response from the MCP server
