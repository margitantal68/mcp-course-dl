> **Note:** The code is based on MCP: Build Rich-Context AI Apps with Anthropic course, [Lesson 4] (https://learn.deeplearning.ai/courses/mcp-build-rich-context-ai-apps-with-anthropic/lesson/pnd5n/creating-an-mcp-client) from DeepLearning.AI.
# MCP Chatbot

This project provides an MCP (Model Context Protocol) server implementation using [FastMCP](https://github.com/jlowin/fastmcp) in Python.

## Features

- **MCP Server**: Implemented in `mcp_research_server.py`
- **FastMCP**: Utilizes the FastMCP library for efficient protocol handling
- **Testing**: Compatible with MCP Inspector for server testing without a dedicated client

## Getting Started

### Prerequisites

- Python 3.8+
- FastMCP library

### Installation

```bash
pip install mcp fastmcp arxiv
```

### Running the Server

```bash
npx @modelcontextprotocol/inspector uv run mcp_research_server.py
```

### Testing

You can test the server using [MCP Inspector](https://github.com/your-org/mcp-inspector) without building a separate MCP client.

## Project Structure

```
mcp_chatbot/
├── mcp_research_server.py
└── README.md
```

