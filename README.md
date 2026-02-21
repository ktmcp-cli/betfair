# @ktmcp/betfair

MCP server for Betfair: Exchange Streaming API

## Installation

```bash
npm install -g @ktmcp/betfair
```

## Usage

Add to your MCP settings:

```json
{
  "mcpServers": {
    "betfair": {
      "command": "mcp-betfair"
    }
  }
}
```

## Description

API to receive streamed updates. This is an ssl socket connection of CRLF delimited json messages (see RequestMessage & ResponseMessage)

## Category

api
