# MyCryptoProtocol (MCP)

## The Decentralized Intelligence Layer for Crypto

MyCryptoProtocol (MCP) is a protocol-level framework that connects AI agents (via Model Context Protocols) with crypto-native services, enabling seamless, standardized interaction across trading, DeFi, governance, and social platforms. It acts as an intelligent coordination layer, supporting discoverability, authentication, and execution across modular AI agents.

## Key Features

- **MCP Registry Layer**: Access curated AI agent backends through a standardized protocol
- **Agent-Based Execution**: Natural language processing with intelligent tool fallback
- **Modular & Interoperable**: Works with Solana, EVM chains, L2s, and off-chain systems
- **Governance-Ready**: Tokenized curation and incentive mechanisms

## Problem & Solution

AI integration with crypto is fragmented and non-scalable due to bespoke integrations. MCP standardizes this via a unified protocol that simplifies agent-to-service interaction, boosting accessibility and scalability.

## Repository Structure

This monorepo contains the following components:

- [**mcp-core**](https://github.com/MyCryptoProtocol/mcp-core): Core protocol logic with Solana programs for registry, permissions, and execution tracking
- [**mcp-agents**](https://github.com/MyCryptoProtocol/mcp-agents): Agent templates and execution engines with prebuilt AI agents
- [**mcp-server**](https://github.com/MyCryptoProtocol/mcp-server): Reference MCP server implementation with context handling and wallet integration
- [**mcp-examples**](https://github.com/MyCryptoProtocol/mcp-examples): Full workflow examples using real-world Solana services
- [**mcp-docs**](https://github.com/MyCryptoProtocol/mcp-docs): Protocol documentation, architecture, and tutorials
- [**community**](./community): Community resources, governance processes, and contribution guidelines

## Why Now?

AI is centralized, crypto is decentralized. This protocol bridges them, leveraging AI's usability and crypto's openness. The goal is to build a decentralized, AI-native interface that works like an OS for crypto workflows.

## MCP Defined

Each MCP server exposes context-aware, domain-specific functionality (e.g., Binance, Twitter, smart contracts) in a machine-readable format, enabling AI agents to interact securely and intelligently.

### MCP Server Ecosystem

The community has developed numerous specialized MCP servers that extend the protocol's capabilities:

- [**Binance MCP Server**](https://github.com/qeinfinity/binance-mcp-server): Real-time market data streaming for Binance markets
- [**CoinGecko MCP Server**](https://github.com/crazyrabbitLTC/mcp-coingecko-server): Cryptocurrency market data and price tracking
- [**Solana Agent Kit**](https://github.com/sendaifun/solana-mcp): Solana blockchain interaction and wallet management
- [**Crypto Sentiment MCP**](https://github.com/kukapay/crypto-sentiment-mcp): Cryptocurrency sentiment analysis from social media

See the [Community Showcase](./community/resources/SHOWCASE.md) for a complete list of community-built MCP servers.

## Token Model & Ecosystem

$MCP powers decentralized governance, usage, and staking, with network effects tied directly to protocol utility, not speculation.

## Getting Started

## Community

MCP is built with a community-first approach. We welcome contributions from developers, content creators, and crypto enthusiasts of all backgrounds.

- [**Contribution Guidelines**](./community/resources/CONTRIBUTING.md): How to contribute to the project
- [**Governance**](./community/governance): Decision-making processes and improvement proposals
- [**Events**](./community/events): Community calls, hackathons, and meetups
- [**Rewards Program**](./community/rewards): Incentives for community contributions

## Getting Started

To start developing with MCP:

```bash
# Clone the repository
git clone https://github.com/your-org/mycryptoprotocol.git
cd mycryptoprotocol

# Install dependencies for all packages
npm install

# Build the core components
cd mcp-core
anchor build

# Run examples
cd ../mcp-examples
npm run start:jupiter
```

## Launch Strategy

Started with an anonymous dev sharing ideas on social media. Transparent, community-first, and built in public with a light-touch rollout—no hype, no VC dominance, just real infrastructure and community involvement.

## Development Tools

- Solana CLI + Anchor (for smart contracts)
- TypeScript/JavaScript (for client applications)
- WebSockets/RPC listeners (for real-time events)
- gRPC/REST APIs (for service communication)

## Vision

MyCryptoProtocol is building the decentralized intelligence layer for crypto, where agents serve people, not platforms.

## Join the Community

- **Discord**: [Join our Discord server](https://discord.gg/mycryptoprotocol)
- **Twitter**: [@MyCryptoProtocol](https://twitter.com/MyCryptoProtocol)
- **GitHub Discussions**: [Start or join a discussion](https://github.com/MyCryptoProtocol/mcp-core/discussions)

We hold weekly community calls every Wednesday at 12:00 UTC. All are welcome to join and contribute!

## Contributing

We welcome contributions! Please see the [CONTRIBUTING.md](./CONTRIBUTING.md) file for guidelines.

## License

This project is licensed under the [MIT License](./LICENSE).
