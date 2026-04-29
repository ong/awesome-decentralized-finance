# Awesome Decentralized Finance  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome decentralized finance projects, software, and resources.

## What is Decentralized Finance?

Decentralized finance (#defi) is the movement that leverages open source software and decentralized networks to transform traditional financial products into trustless and transparent protocols that operate without unnecessary intermediaries. One could envision decentralized finance impacting the financial world the same way that open source software has changed software products.

## Contents

- [Decentralized Exchange Protocols](#decentralized-exchange-protocols)
- [Stablecoins](#stablecoins)
- [Lending Protocols](#lending-protocols)
- [Liquid Staking Protocols](#liquid-staking-protocols)
- [Yield Aggregators](#yield-aggregators)
- [Restaking Protocols](#restaking-protocols)
- [Derivative Protocols/Prediction Markets](#derivative-protocols)
- [Layer 2 Scaling Solutions](#layer-2-scaling-solutions)
- [Index Protocols](#bundling-protocols)
- [Asset Management](#fund-protocols)
- [Applications/Tools](#applications-tools)
- [Analytics](#analytics)
- [Misc](#misc)
- [Community](#community)

<a name="decentralized-exchange-protocols" />

## Decentralized Exchange Protocols

### Ethereum & EVM
- [Uniswap](https://uniswap.org) ([source code](https://github.com/Uniswap), [docs](https://docs.uniswap.org/)) - Largest DEX by volume. V4 adds customizable hooks for advanced functionality
- [Curve Finance](https://curve.fi) ([source code](https://github.com/curvefi), [docs](https://docs.curve.fi/)) - Specialized AMM for stablecoin and like-kind asset swaps with low slippage
- [Balancer](https://balancer.fi) ([source code](https://github.com/balancer), [docs](https://docs.balancer.fi/)) - Customizable AMM pools supporting multiple tokens with different weightings
- [PancakeSwap](https://pancakeswap.finance) ([source code](https://github.com/pancakeswap), [docs](https://docs.pancakeswap.finance/)) - Largest DEX on BNB Chain, now multi-chain
- [SushiSwap](https://sushi.com) ([source code](https://github.com/sushiswap), [docs](https://docs.sushi.com/)) - Multi-chain AMM with additional DeFi products
- [Aerodrome](https://aerodrome.finance) ([source code](https://github.com/aerodrome-finance), [docs](https://docs.aerodrome.finance/)) - Next-gen AMM on Base with ve(3,3) tokenomics

### DEX Aggregators
- [1inch](https://1inch.io) ([source code](https://github.com/1inch), [docs](https://docs.1inch.io/)) - Finds best swap routes across multiple DEXs
- [Matcha](https://matcha.xyz) - Aggregator by 0x with professional trading UI
- [ParaSwap](https://paraswap.io) ([source code](https://github.com/paraswap)) - Multi-chain aggregator with MEV protection
- [CoW Swap](https://cow.fi) ([source code](https://github.com/cowprotocol), [docs](https://docs.cow.fi/)) - MEV-protected trading via batch auctions and off-chain order matching

### Solana
- [Jupiter](https://jup.ag) ([source code](https://github.com/jup-ag)) - Leading Solana DEX aggregator with limit orders and DCA
- [Raydium](https://raydium.io) ([source code](https://github.com/raydium-io)) - AMM with concentrated liquidity integrated with Serum orderbook
- [Orca](https://www.orca.so) ([source code](https://github.com/orca-so)) - User-friendly DEX with concentrated liquidity (Whirlpools)

### Cross-Chain
- [THORChain](https://thorchain.org) ([source code](https://gitlab.com/thorchain), [docs](https://docs.thorchain.org/)) - Native cross-chain swaps (BTC, ETH, etc.) without wrapped tokens

<a name="stablecoins" />

## Stablecoins

### Fiat-Backed (Centralized)
- [Tether (USDT)](https://tether.to) ([docs](https://tether.to/en/transparency/)) - $144B+ market cap, most liquid stablecoin
- [USD Coin (USDC)](https://www.circle.com/en/usdc) ([source code](https://github.com/circlefin/stablecoin-evm), [docs](https://developers.circle.com/stablecoins/docs)) - $59B+ market cap, issued by Circle
- [Paxos Dollar (USDP)](https://paxos.com/usdp/) ([source code](https://github.com/paxosglobal/usdp-contracts)) - Regulated by NYDFS
- [Gemini Dollar (GUSD)](https://gemini.com/dollar) ([source code](https://github.com/gemini/dollar)) - Issued by Gemini exchange

### Crypto-Collateralized
- [DAI/USDS](https://makerdao.com) ([source code](https://github.com/makerdao), [docs](https://docs.makerdao.com/)) - $5B+ supply, overcollateralized by crypto (MakerDAO rebranded to Sky)
- [USDe](https://ethena.fi) ([docs](https://ethena-labs.gitbook.io/ethena-labs)) - Synthetic dollar using delta-neutral positions on perpetual futures
- [GHO](https://gho.aave.com) ([source code](https://github.com/aave/gho-core), [docs](https://docs.gho.xyz/)) - Minted by borrowing on Aave
- [crvUSD](https://crvusd.curve.fi) ([docs](https://docs.curve.fi/crvusd/)) - Soft liquidation mechanism (LLAMMA) reduces liquidation risk
- [LUSD](https://www.liquity.org) ([source code](https://github.com/liquity/dev), [docs](https://docs.liquity.org/)) - 0% interest, ETH-only collateral, immutable protocol
- [FRAX](https://frax.finance) ([source code](https://github.com/FraxFinance), [docs](https://docs.frax.finance/)) - Fractional-algorithmic design

### Wrapped BTC
- [WBTC](https://wbtc.network) ([source code](https://github.com/WrappedBTC/bitcoin-token-smart-contracts)) - Centralized custody, largest supply
- [tBTC](https://threshold.network/earn/btc) ([source code](https://github.com/keep-network/tbtc-v2)) - Decentralized Bitcoin bridge

### Historical Note
- ~~[Terra UST](https://terra.money)~~ - Collapsed May 2022 (~$40B lost). Pure algorithmic stablecoins have proven unreliable

<a name="lending-protocols" />

## Lending Protocols

- [Aave](https://aave.com) ([source code](https://github.com/aave), [docs](https://docs.aave.com/)) - $14.6B+ TVL, invented flash loans, multi-chain. V3 improves capital efficiency
- [Compound](https://compound.finance) ([source code](https://github.com/compound-finance/), [docs](https://docs.compound.finance/)) - Algorithmic interest rates. V3 adds isolated markets per asset
- [Morpho](https://morpho.org) ([source code](https://github.com/morpho-org), [docs](https://docs.morpho.org/)) - Improves rates by peer-to-peer matching on top of Aave/Compound
- [Spark](https://spark.fi) ([source code](https://github.com/marsfoundation/spark-protocol), [docs](https://docs.sparkprotocol.io/)) - MakerDAO's lending market, integrated with DAI Savings Rate
- [Euler](https://euler.finance) ([source code](https://github.com/euler-xyz), [docs](https://docs.euler.finance/)) - Permissionless listings with reactive interest rates
- [Radiant Capital](https://radiant.capital) ([docs](https://docs.radiant.capital/)) - Omnichain liquidity layer (borrow on one chain, deposit on another)
- [Venus](https://venus.io) ([source code](https://github.com/VenusProtocol), [docs](https://docs-v4.venus.io/)) - Largest lending market on BNB Chain
- [Benqi](https://benqi.fi) ([source code](https://github.com/Benqi-fi), [docs](https://docs.benqi.fi/)) - Avalanche lending market
- [Alchemix](https://alchemix.fi) ([source code](https://github.com/alchemix-finance), [docs](https://alchemix-finance.gitbook.io/)) - Self-repaying loans (debt paid from yield on collateral)

<a name="liquid-staking-protocols" />

## Liquid Staking Protocols

Stake PoS assets while keeping them liquid via receipt tokens (e.g., stake ETH, receive stETH to use in DeFi).

### Ethereum
- [Lido](https://lido.fi) ([source code](https://github.com/lidofinance), [docs](https://docs.lido.fi/)) - $10B+ TVL, ~29% of all staked ETH. Liquid token: stETH
- [Rocket Pool](https://rocketpool.net) ([source code](https://github.com/rocket-pool), [docs](https://docs.rocketpool.net/)) - Most decentralized, 3,800+ independent validators. Liquid token: rETH
- [Frax Ether](https://frax.finance/frxeth) ([source code](https://github.com/FraxFinance), [docs](https://docs.frax.finance/)) - Dual token system: frxETH (non-yielding) and sfrxETH (yielding)
- [Swell](https://swellnetwork.io) ([docs](https://docs.swellnetwork.io/)) - Liquid staking + restaking in one protocol

### Other Chains
- [Marinade Finance](https://marinade.finance) ([source code](https://github.com/marinade-finance), [docs](https://docs.marinade.finance/)) - Solana liquid staking (mSOL)
- [Jito](https://jito.network) - Solana liquid staking with MEV rewards (jitoSOL)
- [Stader](https://staderlabs.com) ([source code](https://github.com/stader-labs), [docs](https://www.staderlabs.com/docs/)) - Multi-chain (ETH, MATIC, BNB, etc.)

<a name="yield-aggregators" />

## Yield Aggregators

Auto-compound and optimize yields across multiple protocols.

- [Yearn Finance](https://yearn.fi) ([source code](https://github.com/yearn), [docs](https://docs.yearn.fi/)) - OG yield optimizer. $1B+ TVL, battle-tested strategies
- [Convex Finance](https://convexfinance.com) ([source code](https://github.com/convex-eth), [docs](https://docs.convexfinance.com/)) - $1.75B+ TVL, specializes in boosting Curve yields
- [Beefy Finance](https://beefy.finance) ([source code](https://github.com/beefyfinance), [docs](https://docs.beefy.finance/)) - Multi-chain auto-compounder (20+ chains)
- [Pendle](https://pendle.finance) ([source code](https://github.com/pendle-finance), [docs](https://docs.pendle.finance/)) - Trade future yield (separate principal from yield)
- [Yield Yak](https://yieldyak.com) ([source code](https://github.com/yieldyak), [docs](https://docs.yieldyak.com/)) - Avalanche-focused auto-compounder

<a name="restaking-protocols" />

## Restaking Protocols

Use staked ETH to secure additional networks beyond Ethereum (earn extra yield but with added slashing risk).

- [EigenLayer](https://eigenlayer.xyz) ([source code](https://github.com/Layr-Labs/eigenlayer-contracts), [docs](https://docs.eigenlayer.xyz/)) - $14.3B+ TVL, pioneered restaking concept. Secures "Actively Validated Services" (AVSs)
- [Symbiotic](https://symbiotic.fi) ([docs](https://docs.symbiotic.fi/)) - Flexible restaking with custom slashing conditions
- [Karak](https://karak.network) ([docs](https://docs.karak.network/)) - Multi-asset restaking (not just ETH)
- [Puffer Finance](https://puffer.fi) ([source code](https://github.com/PufferFinance), [docs](https://docs.puffer.fi/)) - Liquid restaking with anti-slashing tech

<a name="derivative-protocols" />

## Derivative Protocols/Prediction Markets

### Perpetuals (Decentralized Leverage Trading)
- [GMX](https://gmx.io) ([source code](https://github.com/gmx-io), [docs](https://docs.gmx.io/)) - $1B+ daily volume, up to 50x leverage. Uses GLP pool as counterparty
- [dYdX](https://dydx.exchange) ([source code](https://github.com/dydxprotocol), [docs](https://docs.dydx.exchange/)) - Orderbook-based, now on standalone blockchain. Highest volume perp DEX
- [Hyperliquid](https://hyperliquid.xyz) - Fully on-chain orderbook L1, fastest-growing perp DEX
- [Synthetix Perps](https://synthetix.io) ([source code](https://github.com/Synthetixio/synthetix), [docs](https://docs.synthetix.io/)) - Debt pool model, deep liquidity for crypto and forex
- [Gains Network (gTrade)](https://gains.trade) ([source code](https://github.com/GainsNetwork), [docs](https://docs.gains.trade/)) - Synthetic leverage on forex, commodities, stocks
- [Vertex Protocol](https://vertexprotocol.com) ([docs](https://docs.vertexprotocol.com/)) - Hybrid AMM + orderbook on Arbitrum
- [Kwenta](https://kwenta.io) ([source code](https://github.com/Kwenta/kwenta), [docs](https://docs.kwenta.io/)) - Perps powered by Synthetix liquidity

### Options
- [Lyra](https://lyra.finance) ([source code](https://github.com/lyra-finance), [docs](https://docs.lyra.finance/)) - Options AMM with dynamic pricing
- [Premia](https://premia.finance) ([source code](https://github.com/Premian-Labs), [docs](https://docs.premia.finance/)) - Peer-to-pool options trading
- [Dopex](https://dopex.io) ([docs](https://docs.dopex.io/)) - Options with rebates to reduce losses
- [Ribbon Finance](https://ribbon.finance) ([source code](https://github.com/ribbon-finance), [docs](https://docs.ribbon.finance/)) - Automated options strategies (covered calls, put selling)

### Prediction Markets
- [Polymarket](https://polymarket.com) ([docs](https://docs.polymarket.com/)) - Largest prediction market, $2B+ in 2024 volume betting on real-world events
- [Augur](https://augur.net) ([source code](https://github.com/AugurProject/augur), [docs](https://docs.augur.net/)) - OG prediction market protocol
- [Azuro](https://azuro.org) - Sports betting prediction market

<a name="layer-2-scaling-solutions" />

## Layer 2 Scaling Solutions

Faster, cheaper transactions while inheriting Ethereum security.

### Optimistic Rollups
- [Arbitrum](https://arbitrum.io) ([source code](https://github.com/OffchainLabs/arbitrum), [docs](https://docs.arbitrum.io/)) - $3.9B TVL, most DeFi activity (GMX, Uniswap, Aave, etc.)
- [Base](https://base.org) ([docs](https://docs.base.org/)) - $4.3B TVL, 55% of L2 transaction volume. Built by Coinbase on OP Stack
- [Optimism](https://optimism.io) ([source code](https://github.com/ethereum-optimism/optimism), [docs](https://docs.optimism.io/)) - $843M TVL, created OP Stack used by Base and others (Superchain)

### ZK Rollups
- [zkSync Era](https://zksync.io) ([source code](https://github.com/matter-labs/zksync-era), [docs](https://docs.zksync.io/)) - Native account abstraction, low fees
- [Starknet](https://starknet.io) ([source code](https://github.com/starkware-libs), [docs](https://docs.starknet.io/)) - Uses STARK proofs, Cairo programming language
- [Polygon zkEVM](https://polygon.technology/polygon-zkevm) ([source code](https://github.com/0xPolygonHermez), [docs](https://docs.polygon.technology/zkEVM/)) - EVM-equivalent ZK rollup
- [Scroll](https://scroll.io) ([source code](https://github.com/scroll-tech), [docs](https://docs.scroll.io/)) - Bytecode-compatible zkEVM

### Sidechains
- [Polygon PoS](https://polygon.technology) ([source code](https://github.com/maticnetwork), [docs](https://docs.polygon.technology/)) - Mature DeFi ecosystem, faster but less secure than rollups

<a name="bundling-protocols" />

## Index Protocols

Tokenized portfolios/baskets of crypto assets.

- [Index Coop](https://indexcoop.com) ([source code](https://github.com/IndexCoop), [docs](https://docs.indexcoop.com/)) - DeFi index products (DPI, MVI, ETH2x-FLI)
- [Set Protocol](https://www.setprotocol.com/) ([source code](https://github.com/SetProtocol/set-protocol-v2), [docs](https://docs.tokensets.com/)) - Infrastructure for creating/managing tokenized portfolios

<a name="fund-protocols" />

## Asset Management

On-chain fund management platforms.

- [Enzyme Finance](https://enzyme.finance) ([source code](https://github.com/enzymefinance), [docs](https://docs.enzyme.finance/)) - Create and manage on-chain investment funds
- [dHEDGE](https://dhedge.org) ([source code](https://github.com/dhedge), [docs](https://docs.dhedge.org/)) - Social asset management (copy successful managers)


<a name="applications-tools" />

## Applications/Tools

### Wallets
- [MetaMask](https://metamask.io) ([source code](https://github.com/MetaMask), [docs](https://docs.metamask.io/)) - Most popular Ethereum wallet, built-in swaps
- [Rainbow](https://rainbow.me) - Mobile-friendly Ethereum wallet
- [Rabby](https://rabby.io) ([source code](https://github.com/RabbyHub/Rabby)) - Desktop wallet with better multi-chain UX
- [Safe](https://safe.global) ([source code](https://github.com/safe-global), [docs](https://docs.safe.global/)) - Multi-sig wallet (formerly Gnosis Safe)

### Portfolio Trackers
- [DeBank](https://debank.com) - Track positions across 1000+ protocols
- [Zapper](https://zapper.xyz) - Portfolio tracker + easy DeFi interactions
- [Zerion](https://zerion.io) ([source code](https://github.com/zeriontech)) - Portfolio + trading interface

### Advanced DeFi Tools
- [DeFi Saver](https://defisaver.com) - Automation for lending positions (MakerDAO, Aave, Compound)
- [Revert Finance](https://revert.finance) - Manage Uniswap V3 liquidity
- [Instadapp](https://instadapp.io) ([source code](https://github.com/Instadapp)) - Smart wallet for advanced DeFi interactions

### Developer Infrastructure
- [The Graph](https://thegraph.com) ([source code](https://github.com/graphprotocol), [docs](https://thegraph.com/docs/)) - Index and query blockchain data
- [WalletConnect](https://walletconnect.com) ([source code](https://github.com/WalletConnect), [docs](https://docs.walletconnect.com/)) - Connect wallets to dapps

<a name="analytics" />

## Analytics

### DeFi Dashboards
- [DeFiLlama](https://defillama.com) ([source code](https://github.com/DefiLlama)) - Best DeFi data source: TVL, yields, stablecoins, unlocks across all chains
- [Dune Analytics](https://dune.com) - Create custom dashboards with SQL queries on blockchain data
- [Token Terminal](https://tokenterminal.com) - Protocol financials (revenue, fees, P/E ratios)

### DEX & Trading
- [DEX Screener](https://dexscreener.com) - Real-time charts for any DEX pair across all chains
- [GeckoTerminal](https://geckoterminal.com) - DEX analytics by CoinGecko
- [Dex.Guru](https://dex.guru) - Advanced DEX trading terminal

### Block Explorers
- [Etherscan](https://etherscan.io) - Ethereum
- [Arbiscan](https://arbiscan.io) - Arbitrum
- [Basescan](https://basescan.org) - Base

### Research & Intelligence
- [Messari](https://messari.io) - Research reports and protocol data
- [Nansen](https://nansen.ai) - On-chain analytics with labeled wallets (tracks smart money)
- [Arkham](https://arkaham.com) - Track entities and wallets
- [Glassnode](https://glassnode.com) - On-chain metrics and market intelligence

<a name="misc" />

## Misc

### Real-World Assets (RWA)
Bringing traditional assets on-chain.

- [Ondo Finance](https://ondo.finance) ([docs](https://docs.ondo.finance/)) - Tokenized US Treasuries and bonds
- [Centrifuge](https://centrifuge.io) ([source code](https://github.com/centrifuge), [docs](https://docs.centrifuge.io/)) - Tokenize real-world assets (invoices, real estate)
- [Maple Finance](https://maple.finance) ([source code](https://github.com/maple-labs), [docs](https://docs.maple.finance/)) - Under-collateralized loans to institutions
- [Goldfinch](https://goldfinch.finance) ([source code](https://github.com/goldfinch-eng), [docs](https://docs.goldfinch.finance/)) - Real-world loans without crypto collateral

### Cross-Chain Bridges
- [Across Protocol](https://across.to) ([source code](https://github.com/across-protocol), [docs](https://docs.across.to/)) - Fast, capital-efficient bridge using intents
- [Stargate](https://stargate.finance) ([source code](https://github.com/stargate-protocol), [docs](https://stargateprotocol.gitbook.io/)) - LayerZero-based composable bridge

### Privacy
- [Aztec](https://aztec.network) ([source code](https://github.com/AztecProtocol), [docs](https://docs.aztec.network/)) - Privacy-focused ZK rollup
- [Railgun](https://railgun.org) ([docs](https://docs.railgun.org/)) - Private DeFi transactions via ZK-SNARKs

### Governance Tools
- [Snapshot](https://snapshot.org) ([source code](https://github.com/snapshot-labs)) - Gasless off-chain voting for DAOs
- [Tally](https://tally.xyz) ([docs](https://docs.tally.xyz/)) - On-chain governance interface

<a name="community" />

## Community

### News & Media
- [Bankless](https://bankless.com) - Newsletter and podcast
- [The Defiant](https://thedefiant.io) - DeFi news
- [DeFi Reddit](https://www.reddit.com/r/defi/) - Community discussions

### Learning

- [链新社 - Chinese DeFi & Blockchain Learning Resources](https://www.lianxinshe666.com/special/blockchain/) - Comprehensive Chinese-language learning platform covering DeFi protocols, DEX trading, yield farming, NFTs, and blockchain fundamentals
- [Finematics](https://finematics.com) - Educational videos
- [DeFi Prime](https://defiprime.com) - Directory of DeFi products

### For Developers
- [ETHGlobal](https://ethglobal.com) - Hackathons and community

<a name="contributions" />

## Contributions

Your contributions are always welcome!

If you want to contribute to this list (please do), send me a pull request or contact me [@edwin](https://twitter.com/edwin).

## Other Awesome Lists

If you are interested in AI search, check out this [awesome generative engine optimization list](https://github.com/amplifying-ai/awesome-generative-engine-optimization).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
