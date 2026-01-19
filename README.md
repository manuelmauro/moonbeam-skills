# Moonbeam Skills

A collection of skills that enhance AI agents with specialized capabilities for developing on the Moonbeam parachain. Each skill provides actionable instructions that enable agents to perform specific development tasks effectively.

## Installation

Install these skills using [skilo](https://github.com/manuelmauro/skilo):

```bash
skilo add --agent claude-code manuelmauro/moonbeam-skills
```

## What is Moonbeam?

Moonbeam is a smart contract parachain on Polkadot that combines Ethereum-compatibility with Substrate functionality, allowing developers to use familiar Ethereum tools while leveraging Polkadot's cross-chain capabilities.

## Available Skills

| Skill                                                     | Capability                                  |
| --------------------------------------------------------- | ------------------------------------------- |
| [Adding Pallets](./adding-pallets/SKILL.md)               | Create new FRAME pallets for the runtime    |
| [Adding Precompiles](./adding-precompiles/SKILL.md)       | Build EVM precompiled contracts             |
| [Benchmarking Pallets](./benchmarking-pallets/SKILL.md)   | Benchmark performance and calculate weights |
| [Debugging Moonbeam](./debugging-moonbeam/SKILL.md)       | Debug runtime and EVM issues                |
| [Developing RPCs](./developing-rpcs/SKILL.md)             | Develop and extend RPC endpoints            |
| [Developing Runtime](./developing-runtime/SKILL.md)       | Configure and modify the runtime            |
| [Developing XCM](./developing-xcm/SKILL.md)               | Implement cross-chain messaging             |
| [Implementing EIPs](./implementing-eips/SKILL.md)         | Add Ethereum Improvement Proposals support  |
| [Managing Staking](./managing-staking/SKILL.md)           | Work with the parachain staking system      |
| [Patching Dependencies](./patching-dependencies/SKILL.md) | Manage dependencies across repositories     |
| [Testing Moonbeam](./testing-moonbeam/SKILL.md)           | Write and run tests                         |
| [Writing Migrations](./writing-migrations/SKILL.md)       | Create runtime migrations                   |

## Technologies

- **Rust** - Core development using Substrate/FRAME
- **TypeScript** - Integration testing with Moonwall
- **Solidity** - EVM smart contracts
- **XCM** - Cross-consensus messaging

## Runtimes

Moonbeam maintains three runtime variants:

| Runtime   | Network  | Chain ID |
| --------- | -------- | -------- |
| Moonbase  | Testnet  | 1287     |
| Moonriver | Kusama   | 1285     |
| Moonbeam  | Polkadot | 1284     |

## Resources

- [Moonbeam Documentation](https://docs.moonbeam.network/)
- [Substrate Documentation](https://docs.substrate.io/)
- [Polkadot Wiki](https://wiki.polkadot.network/)
