# Raffle Contract

This repository contains a Raffle contract that uses Chainlink VRF to pick a random winner. The contract is written in Solidity and uses Foundry for development and testing.

## Prerequisites

- [Foundry](https://github.com/foundry-rs/foundry) - A blazing fast, portable and modular toolkit for Ethereum application development written in Rust.

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/mumernisar/lottery.git
   cd raffle-contract
   ```

2. Install dependencies:
   ```sh
   make install
   ```

## Usage

### Makefile Commands

- **Deploy**: Deploy the contract.

  ```sh
  make deploy ARGS="--network sepolia"
  ```

- **Fund Subscription**: Fund the Chainlink subscription.

  ```sh
  make fundSubscription ARGS="--network sepolia"
  ```

- **Clean**: Clean the repository.

  ```sh
  make clean
  ```

- **Remove Modules**: Remove git submodules.

  ```sh
  make remove
  ```

- **Update Dependencies**: Update project dependencies.

  ```sh
  make update
  ```

- **Build**: Build the project.

  ```sh
  make build
  ```

- **Test**: Run tests.

  ```sh
  make test
  ```

- **Snapshot**: Create a snapshot.

  ```sh
  make snapshot
  ```

- **Format**: Format the code.

  ```sh
  make format
  ```

- **Anvil**: Run Anvil, a local Ethereum node.
  ```sh
  make anvil
  ```

## Deployment

To deploy the contract, use the `deploy` command with the appropriate network arguments. For example:

```sh
make deploy ARGS="--network sepolia"
```

## Testing

To run the tests, use the `test` command:

```sh
make test
```

## License

This project is licensed under the MIT License.
