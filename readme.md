# Awesome Decentralized Finance  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of awesome decentralized finance projects, software, and resources.

## What is Decentralized Finance?

Decentralized finance (#defi) is the movement that leverages open source software and decentralized networks to transform traditional financial products into trustless and transparent protocols that operate without unnecessary intermediaries. One could envision decentralized finance impacting the financial world the same way that open source software has changed software products.

## Contents

- [Decentralized Exchange Protocols](#decentralized-exchange-protocols)
- [Stablecoins](#stablecoins)
- [Lending Protocols](#lending-protocols)
- [Derivative Protocols/Prediction Markets](#derivative-protocols)
- [Bundling Protocols](#bundling-protocols)
- [Tokenization Protocols](#tokenization-protocols)
- [Fund Protocols](#fund-protocols)
- [KYC/AML/Identity](#kyc-aml-identity)
- [Applications/Tools](#applications-tools)
- [Analytics](#analytics)
- [Misc](#misc)
- [Community](#community)

<a name="decentralized-exchange-protocols" />

## Decentralized Exchange Protocols

- [BitShares](https://bitshares.org/technology/decentralized-asset-exchange) ([source code](https://github.com/bitshares), [white paper](https://www.bitshares.foundation/download/articles/BitSharesBlockchain.pdf)) - Decentralized exchange protocol based on the Graphene blockchain
- Bitcoin
  - [Bisq](https://bisq.network) ([source code](https://github.com/bisq-network/bisq), [white paper](https://github.com/bisq-network/bisq-docs/blob/master/exchange/whitepaper.adoc)) - Protocol for peer-to-peer exchange of bitcoin
- Ethereum
  - [0x](https://0x.org/) ([source code](https://github.com/0xProject), [white paper](https://0x.org/pdfs/0x_white_paper.pdf)) - Protocol for decentralized exchange of Ethereum assets using relayers, now on version 2
  - [Bancor Protocol](https://about.bancor.network/protocol/) ([source code](https://github.com/bancorprotocol/contracts), [white paper](https://storage.googleapis.com/website-bancor/2018/04/01ba8253-bancor_protocol_whitepaper_en.pdf)) - Protocol for converting one token to another using "smart tokens"
  - [DutchX](https://dutchx.readthedocs.io/en/latest/index.html) ([source code](https://github.com/gnosis/dx-contracts), [docs](https://github.com/gnosis/dx-docs/blob/master/source/_static/docs/DutchX_Documentation.pdf)) - Decentralized trading protocol for ERC-20s that uses the Dutch auction model to achieve fair prices
  - [Hydro Protocol](https://hydroprotocol.io/) ([fork announcement](https://medium.com/hydro-protocol/why-we-are-forking-0x-97dc48ee0426), [source code](https://github.com/HydroProtocol), original white paper removed from website but is archived [here](https://whitepaper.io/document/170/hydro-protocol-whitepaper)) - A fork of 0x from DDEX with new order schema, a new matching engine, a different liquidity sharing model, and no ZRX token
  - [Kyber](https://kyber.network) ([source code](https://github.com/kybernetwork), [white paper](https://files.kyber.network/Kyber_Protocol_22_April_v0.1.pdf)) - On-chain protocol for decentralized token swaps and for easy application integration
  - [Loopring](https://loopring.org) ([source code](https://github.com/loopring), [white paper](https://loopring.org/resources.html)) - Protocol for building decentralized exchanges
  - [Ren](https://renproject.io/) ([source code](https://github.com/renproject), [white paper](https://renproject.io/litepaper.pdf)) - Decentralized dark pool protocol for atomic swaps of digital assets formerly known as Republic
  - [Swap / AirSwap's Protocol](https://airswap.io) ([source code](https://github.com/airswap), [white paper](https://swap.tech/whitepaper/)) - Protocol for peer-to-peer trading of ERC-20 tokens
  - [Uniswap](https://uniswap.io) ([source code](https://github.com/Uniswap), [white paper](https://hackmd.io/C-DvwDSfSxuh-Gd4WKE_ig)) - "Public good"-oriented interface for ERC-20 token exchange with zero rent-extraction.

- [Stellar](https://www.stellar.org/developers/guides/concepts/exchange.html) ([source code](https://github.com/stellar), [white paper](https://www.stellar.org/papers/stellar-consensus-protocol.pdf)) - Decentralized protocol for financial applications, including support for decentralized exchange
  - [StellarX](https://www.stellarx.com/) (closed source) - A UI for the native Stellar DEX built by [Interstellar](https://interstellar.com/)
  - [Interstellar.exchange](https://interstellar.exchange/) (closed source) - A UI for the native Stellar DEX built by [Fintech](https://www.fintech.cm/) (not related to the company Interstellar)
  - [Stellarport](https://stellarport.io) (closed source) - A UI for the Stellar DEX
  - [Stellarterm](https://stellarterm.com/) ([source code](https://github.com/stellarterm/stellarterm)) - An open-source UI for the Stellar Dex

<a name="stablecoins" />

## Stablecoins

- IOU / Centralized
  - Bitcoin / Omni
    - [Tether](https://tether.to) (closed source, [white paper](https://tether.to/wp-content/uploads/2016/06/TetherWhitePaper.pdf)) - Controversial USD-backed token connected to Bitfinex
  - Ethereum
    - [CENTRE USDC](https://www.centre.io/usdc) ([source code](https://github.com/centrehq), [white paper](https://www.centre.io/pdfs/centre-whitepaper.pdf)) - ERC-20 stablecoin originally issued by [Circle](https://www.circle.com/en/usdc) and now embraced by [Coinbase](https://blog.coinbase.com/coinbase-and-circle-announce-the-launch-of-usdc-a-digital-dollar-2cd6548d237)
    - [Gemini Dollar](https://gemini.com/dollar/) ([source code](https://github.com/gemini/dollar), [white paper](https://gemini.com/wp-content/themes/gemini/assets/img/dollar/gemini-dollar-whitepaper.pdf)) - ERC-20 stablecoin issued by Gemini
    - [Paxos](https://www.paxos.com/pax/) ([source code](https://github.com/paxosglobal/pax-contracts), [white paper](https://www.paxos.com/wp-content/uploads/2019/02/PAX_Whitepaper.pdf)) - ERC-20 stablecoin issued by Paxos Trust Company
    - [TrueUSD](https://www.trusttoken.com/trueusd/) ([source code](https://github.com/trusttoken/true-currencies)) - ERC-20 stablecoin with KYC/AML issued by TrustToken
    - [DGX Token from Digix](https://digix.global/dgx) ([source code](https://github.com/DigixGlobal), [white paper](https://github.com/DigixGlobal/digix-press-kit/blob/master/digix-whitepaper.pdf)) - Token which represents 1 gram of gold on Ethereum
  - Stellar
    - [AnchorUSD](https://www.anchorusd.com/) (closed source) - KYC/AML compliant stellar-based token that promises deposits are held 1:1 in audited, US-based bank accounts
    - [Stronghold](https://stronghold.co/stronghold-usd/) (closed source, [white paper](https://docsend.com/view/gg3p9ce)) - Stellar-based token that provides a KYC/AML compliant USD stablecoin
    - [White Standard](https://thewhitecompanyus.com/white-standard/) ([source code](https://github.com/thewhitecompany/whitestandard#), [white paper](https://thewhitecompanyus.com/white-paper)) - Stellar-based tokens that provide stablecoins for a variety of currencies
- Collateralized
  - [Celo](https://celo.org) ([white paper](https://storage.googleapis.com/celo_whitepapers/Celo__A_Multi_Asset_Cryptographic_Protocol_for_Decentralized_Social_Payments.pdf)) - Over-collateralized stablecoin targeting the unbanked using its own distributed ledger
  - Ethereum
    - [Dai Stablecoin from Maker](https://makerdao.com/dai) ([source code](https://github.com/makerdao), [white paper](https://makerdao.com/whitepaper/)) - Stablecoin based on smart contracts for creating collateralized debt positions
    - [Synthetix](https://www.synthetix.io/) ([rebranding announcement](https://blog.synthetix.io/havven-is-transforming-into-synthetix/), [source code](https://github.com/Synthetixio/synthetix), [white paper](https://www.synthetix.io/uploads/synthetix_whitepaper.pdf)) - Decentralized stablecoin modeled on centralized closed loop payment networks formerly known as Havven
     - [WBTC](https://www.wbtc.network) ([source code](https://github.com/WrappedBTC/bitcoin-token-smart-contracts), [white paper](https://www.wbtc.network/assets/wrapped-tokens-whitepaper.pdf)) - ERC-20 token backed 1:1 by Bitcoin
- Algorithmic
  - Ethereum
    - [Ampleforth](https://www.ampleforth.org/) ([rebranding announcement](https://medium.com/ampleforth/fragments-to-ampleforth-thoughts-behind-the-name-change-e38bf95077b2), [source code](https://github.com/ampleforth), [white paper](https://www.ampleforth.org/paper/)) - Monetary policy-based stablecoin protocol formerly known as Fragments
    - ~~[Basis](https://www.basis.io) ([white paper](https://www.basis.io/basis_whitepaper_en.pdf)) - Algorithmic stablecoin that "can be robustly pegged to arbitrary assets or baskets of goods"~~ - shut down due to inability to release tokens without securities classification in the US
    - [Carbon](https://www.carbon.money/) ([white paper](https://www.carbon.money/static/media/explainer.964136d4.pdf)) - Stablecoin that will be composed of a basket of whitelisted tokens that is "functionally fiat-backed with the potential to whitelist an algorithmic stablecoin"
    - [Terra](https://terra.money) ([source code](https://github.com/terra-project), [white paper](https://s3.ap-northeast-2.amazonaws.com/terra.money.home/static/Terra_White_paper.pdf?fab2019)) - Protocol that ensures price-stability by algorithmically expanding and contracting supply

<a name="lending-protocols" />

## Lending Protocols

- Ethereum
  - [Compound](https://compound.finance) ([source code](https://github.com/compound-finance/), [white paper](https://compound.finance/documents/Compound.Whitepaper.v04-83de48b6622ddd665234b41076d04c8b.pdf?vsn=d)) - Protocol for algorithmic money markets
  - [Dharma](https://www.dharma.io/) ([source code](https://github.com/dharmaprotocol) [white paper](https://dharmaprotocol.github.io/developer-docs/#/)) - Protocol for building lending products using tokenized debt
  - [Ethlend](https://ethlend.io) ([source code](https://github.com/ETHLend), [white paper](https://github.com/ETHLend/Documentation/blob/master/ETHLendWhitePaper.md)) - Marketplace for peer-to-peer lending
  - [Lendroid](https://www.lendroid.com) ([source code](https://github.com/lendroidproject), [white paper](https://lendroid.com/assets/whitepaper-margin-trading.pdf)) - Protocol for decentralized lending, margin trading, and short selling
  - [Marble](https://marble.org) ([source code](https://github.com/marbleprotocol)) - "Flash lending" protocol for borrowing "Ether and ERC20 tokens to take advantage of arbitrage opportunities on Ethereum"
  - [Ripio](https://ripiocredit.network/) ([source code](https://github.com/ripio/rcn-network), [white paper](https://ripiocredit.network/wp/RCN%20Whitepaper%20ENG.pdf)) - P2P global credit network protocol based on cosigned smart contracts

<a name="derivative-protocols" />

## Derivative Protocols/Prediction Markets

- Ethereum
  - [Augur](https://www.augur.net) ([source code](https://github.com/AugurProject/augur), [white paper](https://www.augur.net/whitepaper.pdf)) - Prediction market protocol to enable anyone to "create and speculate on derivatives at a low cost for the first time"
  - [bZx](https://b0x.network) ([source code](https://github.com/bZxNetwork), [white paper](https://b0x.network/pdfs/bZx_white_paper.pdf)) - 0x-integrated protocol for decentralized, peer-to-peer margin funding and trading
   - [CDx](https://cdxproject.com) ([source code](https://github.com/cdx-project), [white paper](https://cdxproject.com/assets/resources/cdx-whitepaper.pdf)) - Protocol for tokenized credit default swaps
   - [Daxia](https://www.daxia.us) ([source code](https://github.com/DecentralizedDerivatives), [white paper](https://github.com/DecentralizedDerivatives/DRCT_standard/blob/master/InDepthOverview.md)) - Tokenized derivatives protocol
  - [dYdX](https://dydx.exchange) ([source code](https://github.com/dydxprotocol/protocol_v1), [white paper](https://whitepaper.dydx.exchange/)) - Margin-trading and options protocols
  - [Gnosis](https://gnosis.io/) ([source code](https://github.com/gnosis), [white paper](https://gnosis.io/pdf/gnosis-whitepaper.pdf)) - Decentralized prediction market protocol
  - [Market](https://marketprotocol.io) ([source code](https://github.com/MARKETProtocol), [white paper](https://marketprotocol.io/assets/MARKET_Protocol-Whitepaper.pdf)) - Protocol for structuring peer-to-peer agreements that settle in the future based on the price of a reference asset
  - [UMA](https://umaproject.org) ([source code](https://github.com/umaprotocol), [white paper](https://umaproject.org/UMA-whitepaper.pdf)) - Protocol that allows any two counterparties to design and create their own financial contracts that are secured with economic incentives alone, making them self-enforcing and "universally accessible"
  - [Veil](https://veil.co) ([source code](https://github.com/veilco)) - Peer-to-peer prediction market and derivatives platform built on top of Augur, 0x, and Ethereum

<a name="bundling-protocols" />

## Bundling Protocols

- Ethereum
  - [Basket Protocol](https://www.coinalpha.com/projects) ([source code](https://github.com/CoinAlpha/basket-protocol), [wiki](https://github.com/CoinAlpha/basket-protocol/wiki)) - Protocol for creating tokens that contain a portfolio of other tokens
  - [BSKT](https://cryptofinlabs.github.io) ([source code](https://github.com/cryptofinlabs/bskt), [white paper](https://github.com/cryptofinlabs/bskt-whitepaper/blob/master/bskt-whitepaper-v1.0.0.pdf)) - Generic smart contract that creates decentralized token portfolios
  - [Set](https://www.setprotocol.com/) ([source code](https://github.com/SetProtocol/set-protocol-contracts), [white paper](https://www.setprotocol.com/pdf/set_protocol_whitepaper.pdf)) - Protocol for creating, issuing, redeeming, and rebalancing fungible, collateralized baskets of tokenized assets

<a name="fund-protocols" />

## Fund Protocols

- Ethereum
  - [Fund Protocol](https://www.coinalpha.com/projects) ([source code](https://github.com/CoinAlpha/fund-protocol), [wiki](https://github.com/CoinAlpha/fund-protocol/wiki)) - Protocol for fund administration on the Ethereum blockchain
  - [Melonport](https://melonport.com) ([source code](https://github.com/melonproject), [green paper](https://github.com/melonproject/paper/blob/master/melonprotocol.pdf)) - Protocol for digital asset management

<a name="tokenization-protocols" />

## Tokenization Protocols
- Ethereum
  - [ERC-1404](https://erc1404.org/) ([source code](https://github.com/simple-restricted-token/simple-restricted-token), [eip](https://github.com/ethereum/EIPs/issues/1404)) - An open standard for issuing tokens with transfer restrictions
  - [Harbor/R-Token](https://harbor.com) ([source code](https://github.com/harborhq), [white paper](https://harbor.com/rtokenwhitepaper.pdf)) - Compliant protocol for standardizing crypto-securities issuance and trading
  - [Polymath/ST-20](https://polymath.network) ([source code](https://github.com/PolymathNetwork), original white paper removed from website but is archived [here](https://whitepaper.io/document/57/polymath-whitepaper)) - Platform for tokenizing securities
  - [Abacus](https://abacusfi.com/) ([soure code](https://github.com/abacusfi), [white paper](https://github.com/abacusfi/whitepaper/blob/master/whitepaper.pdf)) - Protocol for permissioned tokens
- [Stellar](https://www.stellar.org/) ([source code](https://github.com/stellar/stellar-core), [docs](https://www.stellar.org/developers/guides/concepts/assets.html)) - Stellar has first-party support for issuing arbitrary tokens

<a name="kyc-aml-identity" />

## KYC/AML/Identity
- Ethereum
  - [Bloom](https://bloom.co) ([source code](https://github.com/hellobloom), [white paper](https://bloom.co/whitepaper.pdf)) - Protocol for identity & credit-scoring
  - [Project Hydro](https://projecthydro.org/) ([source code](https://github.com/HydroBlockchain), [white paper](https://github.com/HydroBlockchain/hydro-docs)) - Decentralized ecosystem using cutting-edge cryptography to secure user accounts, identities, and transactions
  - [SelfKey](https://selfkey.org) ([source code](https://github.com/SelfKeyFoundation/Identity-Wallet), [white paper](https://selfkey.org/selfkey-whitepaper)) - "Self-sovereign" identity management system that aims to integrate with various financial services
  - [Wyre](https://www.sendwyre.com) ([source code](https://github.com/sendwyre), [Medium post](https://blog.sendwyre.com/announcing-the-wyre-sdk-on-ramps-off-ramps-in-under-10-lines-of-code-f2b127eccb5d)) - Compliance SDK that mints ERC-721 tokens to the addresses of verified users


<a name="applications-tools" />

## Applications/Tools
- Ethereum
  - [AMP](https://amp.credit/) - DeFi Software Developer with [EasyCDP](https://easycdp.com/), [SilverWire](https://silverwire.io/), [MultiSupply](https://multi.supply/), and [StableWire](https://stablewire.com/)
  - [Bloqboard](https://bloqboard.com) - Lending platform for collateralized loans originated, settled, serviced, and managed on Ethereum and powered by Compound and Dharma
  - [Fetch](https://hellofetch.co) - Application that is both a decentralized exchange aggregator for price discovery and trading and a dashboard for discovering and managing decentralized loans and borrowings
  - [InstaDApp](https://instadapp.io) - "Decentralized bank" interface built on top of MakerDAO by developers of [MakerScan](https://makerscan.io)
  - [Multis](https://multis.co) ([white paper](https://multis.co/white-paper.html)) - Interface for multisig contracts positioned as "cryptobank for companies"
  - [Settle](https://settle.finance) - Web interface that combines chat with different crypto tools (including portfolio tracking and integration with DeFi protocols) and an "app store" for developers
  - [Zerion](https://zerion.io) ([source code](https://github.com/zeriontech)) - Interface to decentralized finance protocols positioned as "trustless banking"

<a name="analytics" />

## Analytics
- Ethereum
  - [0xTracker](https://0xtracker.com) - 0x protocol trade explorer and decentralised ERC-20 token price index
  - [CuriousGiraffe](https://www.curiousgiraffe.io) - Analytics for [AirSwap](https://www.curiousgiraffe.io/airswap/), [Augur](https://www.curiousgiraffe.io/augur/), [Compound](https://www.curiousgiraffe.io/compound/), and [KyberSwap](https://www.curiousgiraffe.io/kyberswap/)
  - [DEX Terminal](https://dexterminal.com) - Dashboard of decentralized finance activities, from exchange volume to lending/borrowing rates
  - [ETH in DeFi](https://mikemcdonald.github.io/eth-defi/) - Chart of the amount of ETH locked in DeFi products (Maker, Compound, Augur, dYdX, Uniswap)
  - [Loanscan](https://loanscan.io/) - Explorer for Ethereum loans
  - [MakerScan](https://makerscan.io) - Explorer for MakerDao
  - [MKR Tools](https://mkr.tools/) - Explorer for MakerDao
  - [Uniswap ETH Liquidity](https://mikemcdonald.github.io/uniswap/eth-token-liquidity) - Chart of Uniswap's ETH liquidity by token
  - [Predictions.Global](https://predictions.global/) - Dashboard with prediction markets from Augur
- [DeFI Pulse](https://defipulse.com/) - Dashboard with info about locked amount in USD
- [Stablecoin Index](https://stablecoinindex.com/) - Chart of prices biggest stablecoins
- [Stable Report](https://stable.report/) - Weekly reports about stablecoins and list of most stablecoins

<a name="misc" />

## Misc
- Ethereum
  - [8x Protocol](https://8xprotocol.com) ([source code](https://github.com/8xprotocol), [white paper](https://rawcdn.githack.com/8xprotocol/whitepaper/master/latest.pdf)) - Protocol for decentralized subscription payment
  - [AZTEC Protocol](https://www.aztecprotocol.com) ([source code](https://github.com/AztecProtocol/AZTEC), [white paper](https://github.com/AztecProtocol/AZTEC/blob/master/AZTEC.pdf)) - Privacy-enabling protocol for confidential transactions on the Ethereum network
  - [Centrifuge](https://www.centrifuge.io) ([source code](https://github.com/centrifuge), [white paper](https://centrifuge.io/centrifuge_os_white_paper.pdf)) - Platform for financial supply chain, including exchange of invoices, purchase orders, etc.
  - [Groundhog](https://groundhog.network) - "End-to-end" platform for decentralized recurring subscription payments

<a name="community" />

## Community
* [DeFi Reddit](https://www.reddit.com/r/defi/)
* [DeFi Telegram](https://t.me/de_fi)

<a name="contributions" />

## Contributions

Your contributions are always welcome!

If you want to contribute to this list (please do), send me a pull request or contact me [@edwin](https://twitter.com/edwin).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
