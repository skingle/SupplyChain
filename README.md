# SupplyChain

SupplyChain is a study project, create smart contract to track products using Ethereum Blockchain

## UML Diagrams

1. Activity Diagram

![Activity Diagram](uml/SupplyChainActivityDiagram.svg "Activity Diagram")

2. Sequence Diagram

![Sequence Diagram](uml/SequenceDiagram.svg "Sequence Diagram")

3. State Diagram

![State Diagram](uml/StateDiagram.svg "State Diagram")

4. Class Diagram

![Class Diagram](uml/ClassDiagram.svg "Class Diagram")

## Libraries

 `Roles` library is used to create different roles such as Farmers, Distributor, Retailer and Consumer.

## IPFS
 
 IPFS is not used.


## Contract Information

Transaction ID : `0xd175bb98f8a6cd2c19f6366e0d00bb628279df911e9a454dd6a3140a5118b100`

Contract address : `0xdb64987f512efe83c6930da31f7b9e4a2075b332` 

Network : `Renkeby`

## Execution and testing
`Truffle v5.0.27`

`truffle-hdwallet-provider v1.0.13`

`web3 v1.0.0-beta.55`

`node v10.15.1`

check truffle version using

`truffle`

check the version of truffle is same as given above if not install using 

`npm install -g truffle@latest`

In project folder execute following command which will install `truffle-hdwallet-provider` and `web3`

`npm install `

Deploy locally and test

`truffle develop`

`truffle(develop)> test`

Note : If asked for `.secret` file create a blank file of that name.




https://rinkeby.etherscan.io/address/0xdb64987f512efe83c6930da31f7b9e4a2075b332

## Local UI Installation

Change directory

`cd src/js`

Run local UI

`npm run dev`

