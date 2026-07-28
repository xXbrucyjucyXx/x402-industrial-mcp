# X402 Industrial Intelligence — MCP Server

**The first and only MCP server for PLC (Programmable Logic Controller) intelligence.**  
Give any AI agent direct access to industrial automation data — ladder logic, tag databases, cross-references, fault root cause analysis, and sequence blockers.

## 🏭 What This Does

This MCP server connects AI agents to real industrial PLC data. It indexes **67 programs, 13,505 ladder rungs, 131,174 cross-references, and 8,534 PLC tags** across multiple controllers.

## 🔧 Tools (6 total)

| Tool | Description | Price |
|------|-------------|-------|
| `x402_plc_tag_references` | Cross-reference any PLC tag across 131K indexed locations | $0.05 |
| `x402_plc_cause_trace` | Trace upstream rungs and blocking conditions for any tag across 13K rungs | $0.50 |
| `x402_plc_fault_rca` | Fault root cause from 6.8K cause maps + 17.8K operator descriptions | $0.50 |
| `x402_start_sequence_blockers` | What is blocking a machine start sequence (560 sequence steps) | $0.50 |
| `x402_plc_rung_context` | Full rung with elements and L5X descriptions | $0.10 |
| `x402_plc_search_tags` | Search 8.5K PLC tags by name pattern and semantic type | $0.03 |

## 💰 Payment

All tools are priced in **USDC on Solana**. The protocol uses **x402** — agents receive a 402 Payment Required response with the wallet address, pay the exact amount, and receive the data. No subscriptions, no API keys.

**Wallet:** `Csz35TkkhaUQfjCCs7H4gbGrDkTdQzUEzGpRP5kxRFzu`

## 🚀 Quick Start

### 1. Add to Cursor

Edit `.cursor/mcp.json`:
```json
{
  "mcpServers": {
    "x402-industrial": {
      "url": "https://shore-mutiny-gruffly.ngrok-free.dev/mcp/tools",
      "type": "mcp"
    }
  }
}
```

### 2. Add to Claude Desktop

Edit `claude_desktop_config.json`:
```json
{
  "mcpServers": {
    "x402-industrial": {
      "url": "https://shore-mutiny-gruffly.ngrok-free.dev/mcp/tools",
      "type": "mcp"
    }
  }
}
```

### 3. Add to Cline (VS Code)

Cline settings → MCP Servers → Add Server:
- Name: `x402-industrial`
- Type: `mcp`
- URL: `https://shore-mutiny-gruffly.ngrok-free.dev/mcp/tools`

## 📊 Dashboard

The MCP server includes a full web dashboard:
- **Command Center** — Live revenue, API calls, PLC database stats, activity feed, tool usage meters
- **Tool Console** — Execute any tool with a form-based UI
- **Tag Search** — Search 8.5K PLC tags by pattern
- **Database Explorer** — Browse programs, routines, and ladder rungs
- **Agent Link** — Connection instructions and MCP config
- **Bot Radar** — Visibility map and discovery checklist
- **Revenue Dashboard** — Earnings by tool and by day
- **Payment Ledger** — All agent transactions

## 📂 Database Stats

- 67 Industrial Programs
- 13,505 Ladder Rungs
- 131,174 Cross-References
- 8,534 PLC Tags
- 6,839 Fault Cause Maps
- 17,898 Operator Descriptions
- 560 Sequence Steps
- Multiple Controllers

## 🔗 Links

- **MCP Endpoint:** `https://shore-mutiny-gruffly.ngrok-free.dev/mcp/tools`
- **Dashboard:** `https://shore-mutiny-gruffly.ngrok-free.dev/`
- **Payment:** USDC / Solana

## 🧠 Keywords

PLC, Ladder Logic, Programmable Logic Controller, Industrial Automation, SCADA, DCS, Allen Bradley, Rockwell, Logix, L5X, Manufacturing, Tag Database, Cross-Reference, Fault Root Cause, Sequence Blocker, Predictive Maintenance, MCP, x402, USDC, Solana, AI Agent, LLM Tool

---

*The only PLC intelligence MCP server on the internet.*
