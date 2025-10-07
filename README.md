# Installation Steps

To install the `Server Example` MCP server, run the following command:

```json
{
  "mcpServers": {
    "Server Example": {
      "command": "uvx",
      "args": [
        "--from",
        "git+https://github.com/henryhabib/mcpserverexample.git",
        "mcp-server"
      ]
    }
  }
}
```

This will fetch and set up the `mcp-server` from the specified GitHub repository.