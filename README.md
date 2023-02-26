# ROAD TO WEB3

Hey Guys ! So this repo is for me to kickoff my web3 developer journey ! I will be following [Alchemy University's road to web3](https://docs.alchemy.com/docs/welcome-to-the-road-to-web3) path, which is a 10 week (1 project / week) self paced web3 developer program to help new blockchain devs go from beginner to advanced.

Each folder in this repo represents a project from this series and I will explain what has been done in each one of these projects.

Although I'm an experience web2 dev, there are so much more things to learn in web3 and blockchain, the journey is long but super fun ! 

If you want to follow my journey be sure to follow me on [twitter](twitter.com/nonfungibleluc) where I am the most active !


# The 10 Projects

## Week 1: How to Develop an NFT Smart Contract (ERC721) with Alchemy (9/10)

The things covered in this week's lesson is how to simply develop an NFT Smart contract with the help of Alchemy, OpenZeppelin, Remix and Ethereum Goerli More precisely what I learned was:

-   How to write and modify the smart contract using OpenZeppelin and Remix
-   Get free Goerli ETH using  **[https://goerlifaucet.com/](https://goerlifaucet.com/)**
-   Deploy it on the Ethereum Goerli testnet blockchain to save on gas fees
-   Host the NFT tokens metadata on IPFS using Filebase.
-   Mint an NFT and visualize it on OpenSea.

I really recommend you follow the full step by step tutorial by clicking on this [link](https://docs.alchemy.com/docs/how-to-develop-an-nft-smart-contract-erc721-with-alchemy)

## Week 2: Build a "Buy Me a Coffee" DeFi dapp (8/10)

This projects get's a bit more hands on, where you have to configure your Visual Studio Code IDE, install Hardhat start developing and deploying contracts from your terminal instead of using Remix or some extra tools. I built a simple smart contract that can collect donations from others.

What I specifically did was:
-   Use the  **Hardhat**  development environment to build, test, and deploy our  smart contract.
-   Connect your MetaMask wallet to the  **Goerli**  test network using an  **Alchemy**  RPC endpoint.
-   Get free  **Goerli**  ETH from  **goerlifaucet.com.**
-   Use  **Ethers.js**  to interact with your deployed smart contract.
-   Build a frontend website for your decentralized application with  **Replit**.

> Note: in my folder you will find the full smart contract and JS code, the front end was pre written in a tool specified in the tutorial so if you want to test out the full functionality with the UI I recommend you follow the tutorial [here](https://docs.alchemy.com/docs/how-to-build-buy-me-a-coffee-defi-dapp)

## Week 3: Create NFTs with On-Chain Metadata - Hardhat and JavaScript (7/10)

In this project (my favorite so far), I got to learn how to create an NFT with on chain metadata, since we deploy our smart contracts on the blockchain, they cannot communicate with the outside world. So if we need to update the metadata directly from our smart contract we need to store it on chain. Blockchain gaming is one of the use cases we explore in this project.

I built an NFT that can level up by calling a training function that updates the metadata (the level of the NFT) on chain.

What I specifically did was:
-   Stored NFTs metadata on-chain
-   Learned What is **Polygon** and why it's important to lower Gas fees (Okay I knew this one haha, but was interesting to know more in technical details).
-   Deployed the smart contract on **Polygon Mumbai** (Polygon test net)
-   Process and store on-chain **SVG images and JSON objects**
-   Modify the metadata based on interactions with the NFT ([on polygon scan](https://mumbai.polygonscan.com))

The full step by step tutorial by **Alchemy University** [here](https://docs.alchemy.com/docs/how-to-make-nfts-with-on-chain-metadata-hardhat-and-javascript)

## Week 4: Create an NFT Galery (6/10)

So this project for now is my least favorite but kind of important I think. It's more focused on the front-end rather than blockchain and solidity (It's a road to web3 course, so it's understandable). We created a Next.js app (Very similar to react, discovered it in this course).

I learned how to use the Alchemy NFT API to build an NFT gallery capable of fetching NFTs based on three things:
-   Wallet address
-   Collection address
-   Wallet address + collection address

Personal feedback:
-   Great to learn how to fetch NFTs and Collections
-   Some redundant code that could be refractored easily, you can check the api_key variable that is duplicated and fetching nfts function that is duplicated as well.

The full step by step tutorial by **Alchemy University** [here](https://docs.alchemy.com/docs/how-to-create-an-nft-gallery)


## Week 5: Connect APIs to your Smart Contracts using Chainlink (5/10)

This is one of the most important projects to follow. Unfortunately it is one of the least well managed projects by Aclhemy, the written documentation has no code examples, the video is long, sloppy without super clean code that can be easily refractored and written in a better way. Also everything is outdated and not updated so I would give this course a 5/10.

So what we did was learn to connect our smart contracts to outside of the blockchain data, like price feeds or APIs or Random number generators and we built a dynamic NFT that changes it's images based on a price feed. (you can check the full repo [here](https://github.com/zeuslawyer/chainlink-dynamic-nft-alchemy))

The Documentation is [here](https://docs.alchemy.com/docs/connect-apis-to-your-smart-contracts-using-chainlink)
I suggest you watch the [video](https://www.youtube.com/watch?v=hNdXSMKLDi4) It is better than the documentation in this case 

Personal feedback:
-   Very important topic, poor execution
-   Uses a lot of if/else statements instead of requires and asserts..
-   Step back in the quality of code I saw in the first 4 weeks

## Week 6: How to Build a Staking Dapp (9/10)

Okay this week's tutorial was one to remember ! it had it all Solidity, Javascript but most importantly it was a great way to understand how staking apps work, how to manage withdrawl times and claiming deadlines. I learned how to use a new tool as well ! Scaffold ETH which was great ! Really happy with this one to be honest. The only reason I didn't give it a 10/10 was the setup part isn't very well expplained, had some errors that I resolved by myself, was a bit frustrating to be honest 

You can find the full step by step tutorial [here](https://docs.alchemy.com/docs/how-to-build-a-staking-dapp) 

Personal feedback:
-   Extremely Important Topic
-   Easy to understand
-   Project Setup needs a bit more explaining

## Week 7: How to Build an NFT Marketplace from Scratch (9/10)

Wow ! This one was long, but honestly I think until now it has been the most enjoyable tutorial to follow to be honest. It had it all, a good solidity development part with new function other than the typical ERC721 implementation we had in the last tutorials and Big setup part and also a big JS / React front part.

Personal feedback:
-   We covered a lot of ground, Pinata, Solidity, Js and React
-   I think it is the first complete tutorial on how to create a market place
-   It was Challenging but very satisfying, well written and understandable.

You can find the full step by step tutorial [here](https://docs.alchemy.com/docs/how-to-build-an-nft-marketplace-from-scratch) 

*Please note that if you find some differences in the code this is normal, each lesson has a challenge at the end and I try to implement every challenge. I will continue updating this read me as I go through each weeks project.*