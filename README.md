# ROAD TO WEB3

Hey Guys ! So this repo is for me to kickoff my web3 developer journey ! I will be following [Alchemy University's road to web3](https://docs.alchemy.com/docs/welcome-to-the-road-to-web3) path, which is a 10 week (1 project / week) self paced web3 developer program to help new blockchain devs go from beginner to advanced.

Each folder in this repo represents a project from this series and I will explain what has been done in each one of these projects.

Although I'm an experience web2 dev, there are so much more things to learn in web3 and blockchain, the journey is long but super fun ! 

If you want to follow my journey be sure to follow me on [twitter](twitter.com/nonfungibleluc) where I am the most active !


# The 10 Projects

## Week 1: How to Develop an NFT Smart Contract (ERC721) with Alchemy

The things covered in this week's lesson is how to simply develop an NFT Smart contract with the help of Alchemy, OpenZeppelin, Remix and Ethereum Goerli More precisely what I learned was:

-   How to write and modify the smart contract using OpenZeppelin and Remix
-   Get free Goerli ETH using  **[https://goerlifaucet.com/](https://goerlifaucet.com/)**
-   Deploy it on the Ethereum Goerli testnet blockchain to save on gas fees
-   Host the NFT tokens metadata on IPFS using Filebase.
-   Mint an NFT and visualize it on OpenSea.

I really recommend you follow the full step by step tutorial by clicking on this [link](https://docs.alchemy.com/docs/how-to-develop-an-nft-smart-contract-erc721-with-alchemy)

## Week 2: Build a "Buy Me a Coffee" DeFi dapp

This projects get's a bit more hands on, where you have to configure your Visual Studio Code IDE, install Hardhat start developing and deploying contracts from your terminal instead of using Remix or some extra tools. I built a simple smart contract that can collect donations from others.

What I specifically did was:
-   Use the  **Hardhat**  development environment to build, test, and deploy our  smart contract.
-   Connect your MetaMask wallet to the  **Goerli**  test network using an  **Alchemy**  RPC endpoint.
-   Get free  **Goerli**  ETH from  **goerlifaucet.com.**
-   Use  **Ethers.js**  to interact with your deployed smart contract.
-   Build a frontend website for your decentralized application with  **Replit**.

> Note: in my folder you will find the full smart contract and JS code, the front end was pre written in a tool specified in the tutorial so if you want to test out the full functionality with the UI I recommend you follow the tutorial [here](https://docs.alchemy.com/docs/how-to-build-buy-me-a-coffee-defi-dapp)

## Week 3: Create NFTs with On-Chain Metadata - Hardhat and JavaScript

In this project (my favorite so far), I got to learn how to create an NFT with on chain metadata, since we deploy our smart contracts on the blockchain, they cannot communicate with the outside world. So if we need to update the metadata directly from our smart contract we need to store it on chain. Blockchain gaming is one of the use cases we explore in this project.

I built an NFT that can level up by calling a training function that updates the metadata (the level of the NFT) on chain.

What I specifically did was:
-   Stored NFTs metadata on-chain
-   Learned What is **Polygon** and why it's important to lower Gas fees (Okay I knew this one haha, but was interesting to know more in technical details).
-   Deployed the smart contract on **Polygon Mumbai** (Polygon test net)
-   Process and store on-chain **SVG images and JSON objects**
-   Modify the metadata based on interactions with the NFT ([on polygon scan](https://mumbai.polygonscan.com))

The full step by step tutorial by **Alchemy University** [here](https://docs.alchemy.com/docs/how-to-make-nfts-with-on-chain-metadata-hardhat-and-javascript)

## Week 4: Creat an NFT Galery

So this project for now is my least favorite but kind of important I think. It's more focused on the front-end rather than blockchain and solidity (It's a road to web3 course, so it's understandable). We created a Next.js app (Very similar to react, discovered it in this course).

I learned how to use the Alchemy NFT API to build an NFT gallery capable of fetching NFTs based on three things:
-   Wallet address
-   Collection address
-   Wallet address + collection address

Personal feedback:
-   Great to learn how to fetch NFTs and Collections
-   Some redundant code that could be refractored easily, you can check the api_key variable that is duplicated and fetching nfts function that is duplicated as well.

The full step by step tutorial by **Alchemy University** [here](https://docs.alchemy.com/docs/how-to-create-an-nft-gallery)


*Please note that if you find some differences in the code this is normal, each lesson has a challenge at the end and I try to implement every challenge. I will continue updating this read me as I go through each weeks project.*