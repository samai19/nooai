Noo Ai Solana Agent Kit

A powerful toolkit for interacting with the Solana blockchain, providing easy-to-use functions for token operations, trading, and more. Now integrated with LangChain for enhanced functionality.

Features:

Token Operations:
Transfer SOL and SPL tokens
Check token balances
Stake SOL
Deploy new tokens
Request faucet funds (for testing)
Burn and close token accounts (both single and batch)
Trading:
Integrated Jupiter Exchange support
Token swaps with customizable slippage
Direct routing options
Buy and sell tokens with Raydium liquidity
Yield Farming:
Lend idle assets to earn interest with Lulo
LangChain Integration:
Utilize LangChain tools for enhanced blockchain interactions
Access a suite of tools for balance checks, transfers, token deployments, and more
Performance Tracking:
Fetch current transactions per second (TPS) on the Solana network
Token Data:
Get token data by ticker
Get token data by address
Advanced Features: (These might require additional configuration)
Launch Pump & Fun tokens with customizable options
Create Meteora DLMM pools with various configurations
Installation:

Bash

pip install nooai-agentipy
Quick Start:

Install the library:

Bash

pip install nooai-agentipy
Import necessary modules:

Python

from nooai_agentipy import SolanaAgentKit, create_solana_tools

# Initialize with private key and optional RPC URL (endpoint to interact with the blockchain)
agent = SolanaAgentKit(
    "your-wallet-private-key-as-base58",
    "https://api.mainnet-beta.solana.com",
    "your-openai-api-key"  # May be required for some features
)

# Create LangChain tool (optional for additional functionalities)
tools = create_solana_tools(agent)
Replace "your-wallet-private-key-as-base58" with your actual Solana wallet's private key (keep it secure!).

The RPC URL is optional and defaults to the Solana mainnet beta endpoint. You can change it to a different network if needed.

The your-openai-api-key might be required for specific features that utilize OpenAI integration.

Usage Examples:

The document provides various examples for functionalities like fetching token prices, swapping tokens, lending assets, staking SOL, requesting faucet funds, and more. These examples demonstrate how to use the library's functions with your private key and other parameters.

API Reference:

The document outlines the core functions offered by the library, including descriptions and parameters for each function. You can refer to this section for detailed information on how to use specific functionalities.

Dependencies:

The document lists the Solana and Metaplex libraries required for nooai-agentipy to function.

Contributing and License:

Information on contributing to the project's development and the license under which it's distributed is also provided.

Security Reminder:

The document emphasizes the importance of using the library in a secure environment and never sharing your private key.

I hope this breakdown with the requested name change is helpful! Feel free to ask if you have any further questions about specific functionalities of nooai-agentipy.
