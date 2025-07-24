## Foundry

**Foundry is a blazing fast, portable and modular toolkit for Ethereum application development written in Rust.**

Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

https://book.getfoundry.sh/

## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```

##### fuji
✅  [Success] Hash: 0x490b4ffb747430768280844bb5b59319cdc26c9d2940bf49be64b2d15b3d6cb9
Contract Address: 0xE9c3E140aed1c57394FF684d596CBb2Ff5c8f2be                                                    
Block: 43866597
Paid: 0.00000000001653285 ETH (330657 gas * 0.00000005 gwei)

✅ Sequence #1 on fuji | Total Paid: 0.00000000001653285 ETH (330657 gas * avg 0.00000005 gwei)                 