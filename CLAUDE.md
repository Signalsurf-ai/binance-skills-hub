# Binance Skills Hub

Open skills marketplace for AI agents — native access to Binance centralized exchange (CEX) and Web3 DeFi.

## Structure

Each skill is a folder with a `SKILL.md` file containing YAML frontmatter (`name`, `description`, `metadata`) and markdown documentation with API specs.

```
skills/
├── binance-web3/   # On-chain / DeFi skills (token info, audits, signals, rankings)
└── binance/        # CEX trading skills (spot, futures, margin, earn, etc.)
```

## Skill Categories

**Web3 (on-chain):** query-token-info, query-token-audit, query-address-info, trading-signal, crypto-market-rank, meme-rush

**Binance (CEX):** spot, algo, alpha, assets, convert, fiat, margin-trading, simple-earn, sub-account, vip-loan, onchain-pay, square-post, derivatives-trading-coin-futures, derivatives-trading-options, derivatives-trading-usds-futures, derivatives-trading-portfolio-margin, derivatives-trading-portfolio-margin-pro

## Conventions

- Skill names use kebab-case matching their folder name
- Each SKILL.md documents API endpoints with request/response examples
- Authentication details (API keys) are specified per-skill where required
- Supported chains for Web3 skills: BSC (56), Base (8453), Solana (CT_501), Ethereum (1)
