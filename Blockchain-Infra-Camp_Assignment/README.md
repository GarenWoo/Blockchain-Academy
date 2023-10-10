# Project Name
ERC721Token(GarenCN)
## Project Introduction
I Deployed 3 Contracts(ERC20TokenGTT, ERC721Token, NFTMarket) on Sepolia. All three contracts had been verified. The addresses are shown as follows: 

ERC20TokenGTT address: 0xd0DA6eB5c080b749cEeA5f2A746C91bA634426F9
ERC721Token address: 0x7cD5bdB0C9FfA3A5eace3F0f94883eddEa94940A
NFTMarket address: 0x63405c39F309572f1C99CDB9f915a45ba8dFe9c2

<br>
This subgraph is used for monitoring token transfer and approval of ERC721Token contract. NFTMarket contract supports NFT transactions by using ERC20TokenGTT.

There were two EOAs that interacted with NFTMarket contract:

EOA1: 0x9314f15a04d9a69bCE94758e535e49c4e6c6770E
EOA2: 0x545383E5263D519B086C4e37964413e1bA17D756

## Project Preview Image
![Subgraph-screenshot1](https://github.com/BLOCKCHAIN-INFRA-CAMP/BLOCKCHAIN-INFRA-CAMP-2023/assets/126687110/7535f87b-b65c-4931-ac7d-704481591692)
![Subgrapgh-screenshot2](https://github.com/BLOCKCHAIN-INFRA-CAMP/BLOCKCHAIN-INFRA-CAMP-2023/assets/126687110/7a212320-ead1-447c-bbd1-6935f8424c8b)

## Project Slide
There were several transactions and events occurred in ERC721Token contract.
1. EOA1 had minted a new NFT (tokenId: 1). This NFT transferred from `address(0)` to EOA1. The `transfer` event occurred.
2. EOA1 had approved NFTMarket contract so that the latter is able to list NFTs of the approver). The `approve` event occurred.
3. NFTMarket contract listed the new NFT. The `transfer` event occurred. At the same time, NFTMarket contract approved EOA1 considering the practicability of delisting NFTs by the NFT original owner(not NFTMarket). So, the `approve` event occurred as well.
4. EOA2 as a buyer, bought the new NFT with 12,000 GTT (ERC20 token, which is supported in NFTMarket contract). The `transfer` event occurred.

In total, there were 5 events that occurred. This subgraph successfully captured all the events that were completely consistent with the result queried on Etherscan.

![Etherescan-Events](https://github.com/BLOCKCHAIN-INFRA-CAMP/BLOCKCHAIN-INFRA-CAMP-2023/assets/126687110/82432a21-5a7e-44c4-8de0-181286177a04)


## Team Information
Garen Woo

## Project Address
https://github.com/GarenWoo/Blockchain-Academy/tree/main/Blockchain-Infra-Camp_Assignment
