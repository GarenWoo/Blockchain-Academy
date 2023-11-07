# Project Name
Frictionless Cross-chain Swap
## Project Introduction
目前的web3世界的开放性有目共睹，但web3世界仍需要更多的基础设施降低用户的使用难度，以便让更多人轻松参与，以此扩大web3的市场规模。

Circle 公司的稳定币产品 USDC ，它在区块链网络的流通量十分巨大，实现现实世界与区块链网络的货币锚定，该公司新近推出的CCTP（Cross-chain Transfer Protocol）实现链上资产 burn and mint 的跨链方式，并借助 USDC 作为中间媒介，实现资产的跨链转移，有望实现 USDC 和原生代币更大的流通性。

我们借助CCTP，开发一款新的产品：Frictionless Cross-chain Swap，该产品将基于CCTP的跨链机制，实现更多可能性：

1. 多链资产聚合：集成各链资产的在线显示与动态更新，可供用户实时监控资产数据。
   
2. 无缝跨链传输：用户点击“Cross-chain Swap”按钮，即可使用原链的原生代币或 USDC 兑换为目标链上的 USDC。全程仅需与 Metamask 钱包交互，不间断地实现资产的跨链兑换。
   
3. 更友好的用户体验：

     a. 跨链接收者无需担心因原生代币余额不足而导致的接收失败的问题，始终保持跨链可用性。
   
     b. 做到与传统互联网转账的操作类似，账户信息与交易回执均在页面中提供。
   
4. 多样的网络支持：
   
     a. Mainnet: Ethereum Mainnet / Avalanche C-Chain/ Optimism Mainnet / Arbitrum One / Base
   
     b. Testnet: Ethereum Goerli / Avalanche Fuji / Optimism Goerli / Arbitrum Goerli / Base Goerli
   
5. 更安全的私钥管理：原生CCTP需要索取发送者与接收者的私钥明文，本产品通过钱包获取账户wallet对象，该对象由 Metamask 钱包掌握，不直接管理私钥，更安全。


The openness of the current web3 world is evident to all. However, the web3 world still needs more infrastructure to reduce the difficulty of use for users so that more people can easily participate, thereby expanding the market scale of web3.

Circle's stablecoin product, USDC, has a huge circulation in the blockchain network, realizing currency anchoring between the real world and the blockchain network. The company's newly launched CCTP (Cross-chain Transfer Protocol), realizes cross-chain transfer of assets through the <u>burn & mint</u>. Moreover, USDC is an intermediary to realize cross-chain transfer, which is expected to achieve greater liquidity of USDC and even native tokens on the chains.

With the help of CCTP, we developed a new product: Frictionless Cross-chain Swap. This product is based on the mechanism of CCTP to achieve more possibilities:

1. Multi-chain assets aggregation: Integrate the online display and dynamical updates of assets in each chain, allowing users to monitor up-to-date data of their assets.

2. Uninterrupt cross-chain transfer: Users can use the native token or USDC on the source chain to exchange for USDC on the target chain by clicking the "Cross-chain Swap" button. The entire process only requires interaction with the Metamask wallet to exchange assets without interruption.

3. More friendly user experience:

      a. Cross-chain recipients do not need to worry about reception failure due to insufficient native token balance, and cross-chain availability is always maintained.
   
      b. The operation is similar to the traditional Internet transfer, and the account information and transaction receipt are provided on the page.
   
4. Diverse network support:

      a. Mainnet: Ethereum Mainnet / Avalanche C-Chain/ Optimism Mainnet / Arbitrum One / Base
   
      b. Testnet: Ethereum Goerli / Avalanche Fuji / Optimism Goerli / Arbitrum Goerli / Base Goerli
   
5. Higher security of private key management: The original script that calls the CCTP smart contract, needs to obtain the private key of the sender and receiver, which is written in the env file. Instead of controlling the private key directly, this product obtains the wallet object which is totally controlled by the Metamask itself. This product effectively prevents the leakage of private keys。
   
## Project Preview Image
The preview image is an informal front page in the procedure of development, which does not represent the final version of it. The new pages are in the process.

![image](https://github.com/GarenWoo/Blockchain-Academy/assets/126687110/2d4c8b1f-ce8d-42de-9e57-5e312e3c6266)

## Project Slide
To do...

## Team Information
Garen Woo(core code), Joe(front-end design & docking), Yuyuista, Loicism, hitefork and Lanqing Zhong.
## Project Address
https://github.com/GarenWoo/Blockchain-Academy/tree/main/Circle-Hackathon-HK-2023
