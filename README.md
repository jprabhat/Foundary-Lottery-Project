# Solidity Lottery Project

This project is a decentralized lottery system built with Solidity, leveraging the Foundry development framework. The lottery allows users to participate by sending a specified amount of cryptocurrency, with a verifiably random winner selected to receive the prize pool. This project is deployed and tested on the Sepolia test network.

## Features

- **Lottery Entry Mechanism**: Participants can enter the lottery by sending the required entry fee to the contract.
- **Random Winner Selection**: We use Chainlink’s VRF (Verifiable Random Function) for transparent, verifiable randomness in selecting a winner, ensuring fairness and security.
- **Automatic Payouts**: After a winner is selected, the prize pool is automatically transferred to the winner’s wallet.
- **Secure and Auditable**: The contract includes security measures to prevent reentrancy and unauthorized access, and ensures transparency through on-chain randomness.

## Project Structure

- **Smart Contract**: Written in Solidity, defining entry, prize distribution, and randomness functions.
- **Testing**: Unit tests are implemented using Foundry to ensure reliability of all key functions.
- **Deployment**: Deployed and tested on the Sepolia test network for smooth operation in real-world scenarios.

## Requirements

- **Foundry**: Used for development and testing of the smart contract.
- **Chainlink VRF**: Ensures randomness for fair selection.
- **Sepolia Test Network**: Deployed for testing purposes.

## Installation and Setup

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd Foundary-Lottery


Foundry consists of:

-   **Forge**: Ethereum testing framework (like Truffle, Hardhat and DappTools).
-   **Cast**: Swiss army knife for interacting with EVM smart contracts, sending transactions and getting chain data.
-   **Anvil**: Local Ethereum node, akin to Ganache, Hardhat Network.
-   **Chisel**: Fast, utilitarian, and verbose solidity REPL.

## Documentation

// Layout of the contract file:
// version
// imports
// errors
// interfaces, libraries, contract

// Inside Contract:
// Type declarations
// State variables
// Events
// Modifiers
// Functions

// Layout of Functions:
// constructor
// receive function (if exists)
// fallback function (if exists)
// external
// public
// internal
// private

// view & pure functions

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
### Contributions
THis project is open for Frontend and backend Contributions: Lets make WEB3 more user interactive ....!!!