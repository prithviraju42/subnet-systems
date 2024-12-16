# DeFi Empire: A Simple DeFi Kingdom Clone

## Project Overview
Welcome to the **DeFi Empire** project! In this tutorial, we explore the thrilling world of blockchain-based gaming by creating a simplified version of a **DeFi Kingdom** on the **Avalanche Network**. This immersive game allows players to collect, build, and battle using digital assets, earning rewards through various game activities.

With the power of **Avalanche EVM Subnets**, you can:
- Deploy smart contracts to a custom chain with low fees.
- Create a unique game environment using your own native currency.
- Architect interactive game features like battling, exploring, and trading.

This guide focuses on the fundamentals of **custom subnet development** on Avalanche, serving as a foundation for your decentralized finance (DeFi) gaming adventure.

---

## Key Features
1. **Custom EVM Subnet**: Set up and configure your custom subnet on Avalanche.
2. **Native Currency**: Define a unique in-game currency for transactions and rewards.
3. **Smart Contracts**: Deploy core game contracts for battling, exploring, and trading.
4. **User Integration**: Connect to wallets like Metamask for seamless asset management.
5. **Scalability**: Build additional game features like leaderboards, achievements, and difficulty levels.

---

## Steps to Build Your DeFi Empire

### 1. Set Up the EVM Subnet
- Use the **Avalanche CLI** and official documentation to create your custom subnet.
- Define a native token for in-game use.

### 2. Connect to Metamask
- Add your subnet to Metamask by following the guide.
- Ensure your subnet is the selected network in Metamask.

### 3. Deploy Smart Contracts
- Use **Remix IDE** and Solidity to deploy foundational contracts, such as:
  - **ERC20 Token Contract**: For creating your custom token.
  - **Vault Contract**: For managing player deposits and rewards.

### 4. Test Your Application
- Deploy tokens, liquidity pools, and other game elements.
- Use Remix to interact with your contracts and simulate game activities.

### 5. Expand Your Game World
- Add features like:
  - **Leaderboards**
  - **Achievements**
  - **Dynamic rewards**
- Integrate with Avalanche Wallet for a complete user experience.

---

## Tools Used
- **Unix-based System (MacOS/Linux)**
- **Solidity**
- **Remix IDE**
- **Metamask**
- **Web Browser**

---

## Smart Contracts
### ERC20 Token Contract
```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.17;

contract ERC20 {
    uint public totalSupply;
    mapping(address => uint) public balanceOf;
    mapping(address => mapping(address => uint)) public allowance;
    string public name = "DeFi Empire Token";
    string public symbol = "DEF";
    uint8 public decimals = 18;

    event Transfer(address indexed from, address indexed to, uint value);
    event Approval(address indexed owner, address indexed spender, uint value);

    // Token logic omitted for brevity.
}
```

### Vault Contract
```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.17;

interface IERC20 {
    // Interface methods omitted for brevity.
}

contract Vault {
    // Vault logic omitted for brevity.
}
```

---

## Submission Requirements

### 1. **GitHub Repository**
- Host your project on a public GitHub repository.
- Include a `README.md` file that explains your project’s purpose and functionality.
- Example: [GitHub URL](https://github.com/your-repo)

### 2. **Video Walkthrough**
- Record a video walkthrough using tools like **Loom**.
- Provide a code walkthrough and demo of your application.
- Example: [Loom URL](https://loom.com/your-video)

### 3. **Transaction/Application ID**
- Include a transaction or application ID as proof of deployment.
- Example: `5Cr2ddy5Lpuz...`

---

## Assessment Criteria
Your project will be evaluated on:
1. **Functionality**: Does it meet the requirements?
2. **Explanation**: Is the code walkthrough clear and complete?
3. **Completeness**: Have all steps been implemented effectively?

You will receive feedback within 72 hours of submission.

---

## Next Steps
- [Set Up Your EVM Subnet](https://docs.avax.network)
- [Learn Solidity](https://soliditylang.org/)
- [Deploy Your First Contract](https://remix.ethereum.org)

Let’s build your **DeFi Empire** together! 🚀

