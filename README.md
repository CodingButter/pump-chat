# Pump Chat

A mono-repo for Pump.fun chat functionality, containing:

- **Client**: WebSocket client for connecting to Pump.fun chat
- **MCP Server**: Model Context Protocol server for LLM integration with Pump.fun chat

## Packages

### Client (`packages/client`)

WebSocket client that connects to Pump.fun for real-time chat interactions.

### MCP Server (`packages/mcp-server`)

MCP server that provides LLM-friendly interface for interacting with Pump.fun chat.

## Development

```bash
# Install dependencies
npm install

# Run all services in development mode
npm run dev

# Build all packages
npm run build
```

## License

MIT
