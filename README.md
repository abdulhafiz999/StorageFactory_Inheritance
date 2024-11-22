# StorageFactory Inheritance Project

## Overview
This project demonstrates advanced Solidity concepts such as the **Factory Pattern**, **inheritance**, and **conflict resolution**. Using Remix IDE and MetaMask, the contracts were compiled, deployed, and tested on the **Arbitrum Sepolia Testnet**. The focus of this project was on creating efficient contract structures and resolving inheritance conflicts.

## Features
- **Factory Pattern**: A `StorageFactory` contract to deploy and manage multiple instances of `SimpleStorage`.
- **Inheritance**: An `AdvancedStorage` contract that extends `SimpleStorage` with additional functionality.
- **Conflict Resolution**: Used `override` and `super` keywords to resolve conflicts in contracts inheriting from multiple parents.

## Challenges and Solutions
### **Challenge 1: Setting up MetaMask for Arbitrum Sepolia**
- **Issue**: Configuring the Arbitrum Sepolia Testnet on MetaMask was initially confusing.
- **Solution**: Followed detailed instructions from Module 4.1 to add the network and acquire test ETH via the Chainlink faucet.

### **Challenge 2: Resolving Inheritance Conflicts**
- **Issue**: Understanding how to handle conflicts when inheriting from multiple parent contracts.
- **Solution**: Used the `override` keyword and referred to Module 4.3 examples to explicitly resolve conflicts and call parent implementations with `super`.

### **Challenge 3: Factory Pattern Implementation**
- **Issue**: Managing multiple contract instances and ensuring they interacted correctly.
- **Solution**: Tested the `StorageFactory` contract extensively using Remix’s debugger and ensured all deployed contracts were stored in an array.

## Deployment
- **Tools Used**: Remix IDE, MetaMask, and the Arbitrum Sepolia Testnet.
- **Steps**:
  1. Compiled the contracts using the Solidity Compiler.
  2. Deployed `StorageFactory` and `AdvancedStorage` contracts.
  3. Verified and interacted with the deployed contracts on the Arbitrum Sepolia Testnet.

## Insights
This project provided valuable hands-on experience with:
- Organizing contracts using imports.
- Implementing and managing the Factory Pattern.
- Extending functionality with inheritance.
- Resolving conflicts in complex inheritance hierarchies.

 
