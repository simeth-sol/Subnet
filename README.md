# Metacrafter Custom Evm Subnet 

This project creates a blockchain-based vault system using Solidity, where users can deposit and withdraw ERC20 tokens. The smart contract manages user balances and tracks the total supply of tokens within the vault, ensuring accurate record-keeping and proportional share distribution.

## Description

The ERC20 contract facilitates the transfer, minting, and burning of a standard token within an Avalanche custom EVM subnet, while the Vault contract enables users to deposit and withdraw these tokens, minting "shares" that represent their claims to the vault's total assets based on the ratio of total tokens to total shares. Check [Here](https://docs.avax.network/) to learn how to build a subnet.

## Getting Started 

### Installing 

  - Clone this repository or
  - Copy the file to remix IDE

### Executing program

  - Connect to injected provider on remix IDE
  - Deploy your subnet
  - I've already deployed the contract on my subnet, use the following parameters to comfirm.
  ```
    Network RPC URL: http://127.0.0.1:9650/ext/bc/simonSubnet/rpc
    Funded address: 0x8db97C7cEcE249c2b98bDC0226Cc4C2A57BF52FC with 1000000 (10^18)
    Network Name: simonSubnet
    Chain ID: 228866
    Token Symbol: SIMSUBNET
  ```

## Authors

Okwa Simon Ogbu
[@OgbuOkwa](https://x.com/OgbuOkwa)

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

                                  

                                        

                          

