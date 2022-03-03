# What is GYDragon🚀
GYDragon is an art creator. We build up this website to show and sell the art works created by GYDragon.
Also we welcome any artist to share their art works in GYDragon. 

# About the Project🎈
This project consists in an open platform where each user can mint his own NFT and expose it on a marketplace by making an offer or buying NFT from others. It includes:

1. A smart contract which represents a collection of NFTs by following the ERC-721 standard
2. A smart contract which represents the NFT Marketplace and contains all the logic to make offers, fill offers...
3. Tests built with JavaScripts to ensure smart contracts are accomplishing the expected functionalities
4. A React.js front-end application as a user interface

# Project architecture🎞
<img width="601" alt="architecture" src="https://user-images.githubusercontent.com/100744176/156522936-11f1f5e9-1256-4150-884e-92d39869c150.png">
The user can access the application via web-browser, and he must have the Metamask wallet installed. This interface, built with React.js, relies on the web3.js library to communicate with the smart contracts through Metamask. This means that the data reflected on the front-end application is fetched from the Ethereum blockchain. Each action performed by the user (mint a NFT, offer NFT, buy NFT...) creates a transaction on Ethereum, which will require Metamask confirmation and pay a small fee, and this transaction will permanently modify the state of the NFTCollection and NFTMarketplace smart contracts. 

# NFT Marketplace features
![image](https://user-images.githubusercontent.com/100744176/156523611-4f12de13-a38f-4c17-8f7c-4da1f4f2d1e0.png)

The user can perform the following actions on this NFT Marketplace:

**Mint**

The user must input a name, description and upload a file (image) to mint his own NFT. Once minted, a representation of this NFT will be displayed in the marketplace and initially it will be owned by its creator. This is open for everyone, meaning everyone can participate in this NFT creation within this collection.

**Make Offer**

The user can offer his NFT by specifying its price (in Ether). If someone fulfills this offer, then the ownership is transferred to a new owner.

**Cancel Offer**

The user can cancel an offer he did in the past if in the end he does not want to sell his NFT or wants to adjust the price.

**Buy**

A user can buy those NFT which someone else offered. This will require paying the requested price (the Ether will be transferred to the smart contract to be claimed later on).

**Claim Funds**

If a user sold an NFT, he can claim his funds by clicking the button in the top-right.
