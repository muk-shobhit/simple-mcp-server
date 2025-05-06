# simple-mcp-server

This project demonstrates how to build simple MCP (Model Context Protocol) servers for fetching weather information and stock prices. It includes two agents: `weather-agent` and `stocks-agent`.

---

[![Create Your First MCP Server](https://img.youtube.com/vi/scpdWIzwpuc/0.jpg)](https://www.youtube.com/watch?v=scpdWIzwpuc)

## Features

- **Weather Agent**: Fetches real-time weather information (temperature and conditions) for a given city.
- **Stocks Agent**: Provides real-time stock prices for various symbols in the Indian share market.

## Prerequisites

- Node.js (v16 or higher)
- NPM or Yarn

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd simple-mcp-server
   ```

2. Install dependencies for each agent:
   ```bash
   cd src/weather-agent
   npm install
   cd ../stocks-agent
   npm install
   ```

## Adding MCP Servers to  VS Code

The `.vscode/mcp.json` file contains the configuration for running the servers using the MCP protocol. Ensure the paths to the `index.js` files are correct.

## Starting MCP Servers

From `.vscode/mcp.json` start both MCP servers. You will observe tools from both servers are listed now in VS Code MCP Server.

## Testing MCP Servers

Now you can ask questions related to weather or stocks. 

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
