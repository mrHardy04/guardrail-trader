# Guardrail Trader

Track A agent for the Binance Agent OS Mini Hackathon.

Categories:
- Data and Analysis
- Trading Workflows

What it does:
- Reads live Binance market data through MCP
- Applies a simple 24-hour change rule
- Gives a short signal: WAIT, NO TRADE, or TINY LONG
- Can automatically prepare a tiny Spot order
- Does not place the order until the user types yes
- Never withdraws

Files:
- AGENT.md — rules
- DEMO.md — data scan
- STRATEGY.md — signal rules
- AUTO.md — one-prompt automated action
- TRADE.md — guarded order prompt

How to run:
1. Open this folder in VS Code
2. Start the Binance MCP server in .vscode/mcp.json
3. Open Copilot Chat in Agent mode
4. Paste a prompt from DEMO.md, STRATEGY.md, or AUTO.md