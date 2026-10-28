# QMS Agent Kit

> Status: early stage (idea / design). No working code yet.

Open-source MCP server and SDK that will let AI agents (Hermes Agent, Claude, any MCP client) use the QMS network.

## Planned scope

**Phase 1: testnet basics**
- Wallet, balances, transfers
- Contract calls through QMS's EVM layer

**Phase 2: Proof-of-Useful-Work**
- Turn a plain-language task (delivery routes, portfolio rebalancing) into an optimization job
- Submit it to the QMS useful-work marketplace, lock the fee, return the best-ranked solution
- Depends on the public marketplace API

## Who it's for
Agent developers and small businesses who need optimization but don't want to write solvers or manage wallets.

## Author
[sprmn24](https://github.com/sprmn24)
