# Binance Smart Chain Binary

:warning:BSC fullnode and Relayers has mostly stabilized, but we are still making some breaking changes.

[Binance Smart Chain](https://www.binance.org/en/smartChain)(BSC) brings the interoperability and programmability of the Ethereum Virtual Machine (EVM) to Binance Chain. While Binance DEX will remain as the major liquidity pool, BSC envisions a rich dApp ecosystem running on it and having tokens flow between two chains, with relatively lower transaction fees and faster confirmation time.

[Rialto Network](https://explorer.binance.org/smart-testnet):rocket: is the first try to run in parallel with a new[ Binance Chain Testnet](https://explorer.binance.org/testnet) (Chain-id: Binance-Chain-Kongo) providing the concrete inter-communication capability. To join the previous testnet, please go to this [page](https://github.com/binance-chain/node-binary)

### Install prebuilt bc fullnode and cli

To learn how to run a fullnode and use command line interface: 

- [Full Node](https://docs.binance.org/fullnode.html)
- [Cli](https://docs.binance.org/api-reference/cli.html)

The new version of Binance Chain binaries have the following new features:

* :bank:[Staking commands](http://docs.binance.org/guides/concepts/bc-staking.html) 
* :rotating_light:[Slashing commands](http://docs.binance.org/guides/concepts/bc-slashing.html)

### Install bsc fullnode

We host prebuilt binaries over at our [repositories](https://github.com/binance-chain/smart-chain-binary/tree/pre-release/bsc/fullnode).

or you can build from source code:

```bash
git clone -b v1.9.13-alpha.0 https://github.com/binance-chain/bsc
# Enter the folder bsc was cloned into
cd bsc
# Comile and install bsc
make geth
```

To learn about how to use bsc-relayer, read the guide [here](http://docs.binance.org/smart-chain/developer/fullnode.html)

You also  need to have [genesis.json](https://github.com/binance-chain/smart-chain-binary/blob/pre-release/bsc/fullnode/config/genesis.json) and [config.toml](https://github.com/binance-chain/smart-chain-binary/blob/pre-release/bsc/fullnode/config/config.toml)

### Install bsc-relayer :package:

We host prebuilt binaries over at our [repositories](https://github.com/binance-chain/smart-chain-binary/tree/pre-release/bsc/relayer).

or you can build from source code:

```bash
git clone -b v1.0.0-alpha.0 https://github.com/binance-chain/bsc-relayer
# Enter the folder bsc was cloned into
cd bsc-relayer
# Comile and install bsc
make build
```

To learn about how to use bsc-relayer, read the guide [here](http://docs.binance.org/smart-chain/developer/bsc-relayer.html)


## Resrouces

- [Dos Site](https://docs.binance.org/) :ledger:
- [White Paper](https://github.com/binance-chain/whitepaper/blob/master/WHITEPAPER.mdl)
