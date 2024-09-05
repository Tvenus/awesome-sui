# Pyth Network

## Tooling Category

- [ ] dApp Development
- [ ] Explorer
- [ ] IDE
- [ ] Indexer
- [x] Oracle
- [ ] SDK

## Homepage or Repo or Download Link

- [Homepage](https://www.pyth.network/) | [Documentation](https://docs.pyth.network/home) | [Sui Tutorial](https://docs.pyth.network/price-feeds/use-real-time-data/sui) | [Sui JS SDK](https://github.com/pyth-network/pyth-crosschain/tree/main/target_chains/sui/sdk/js)
- No Sui specific API Reference documentation

## Description

Pyth Network is an oracle protocol that connects the owners of market data to applications on multiple blockchains.

## Features
- [Pull-based oracles](https://docs.pyth.network/price-feeds/pull-updates#pull-oracles)
- Except Solana, price data is transmitted from Pythnet to Sui through Wormhole behind the scene
- Hermes is a service facilitating fetching updated price info and its signature for on-chain verification
    - [Hermes API](https://hermes.pyth.network/docs/)
    - [Hermes JS SDK](https://github.com/pyth-network/pyth-crosschain/tree/main/price_service/client/js)
- Price Feeds:
    - [Supported pairs on Sui](https://docs.pyth.network/price-feeds/sponsored-feeds#sui)
- [Benchmarks - Historical Price](https://docs.pyth.network/benchmarks)
- Randomness (Sui is not supported)