# Areas Contract

## Overview

The Areas Contract is a Cadence smart contract designed for the Flow blockchain, showcasing key concepts like access control, resource management, and contract interaction. It serves as a valuable example for learning how to structure and interact with smart contracts in Cadence.

## Features

- **Structured Data Management**: Utilizes structures (`SomeStruct`) and resources (`SomeResource`) to efficiently handle data.
- **Access Control**: Demonstrates different levels of access control (`pub`, `pub(set)`, `access(contract)`, `access(self)`) for variables and functions.
- **Functionality Segmentation**: Organized into distinct areas to illustrate varying scopes and accessibility within the contract.

## Contract Areas

1. **AREA 1**: Inside the `structFunc` of `SomeStruct`. Shows full access within the context of the structure.
2. **AREA 2**: Within the `resourceFunc` of `SomeResource`. Highlights access limitations when interacting with a resource.
3. **AREA 3**: Inside the `questsAreFun` function of `SomeContract`. Demonstrates contract-level access and its restrictions.
4. **AREA 4**: In a script that imports `SomeContract`. Represents external, read-only access to the contract's public elements.

## Getting Started

To use this contract:

1. **Deploy the Contract**: Deploy it to the Flow blockchain.
2. **Interact with the Contract**: Use Flow's transaction and script functionalities to engage with the contract’s functions and access its variables based on their defined scopes.

## Usage Guidelines

- Familiarize yourself with Cadence’s access control rules for effective interaction.
- Adhere to the contract's access restrictions when reading or modifying variables or calling functions.
