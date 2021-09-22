# AuctionDapp
This project includes development of a decentralized application which is used for auction.

This project is part of the Blockchain Specialization at Coursera. The test cases has been added in this project in continuation of the project done in Course 2 (which allows bidding of items by participants and its various functions such as register bidder, declare winner etc. over blockchain).

Pre-requisites to run:
1. Ethereum Virtual Machine having truffle and git installed in it

Run:
1. Open Ethereum Virtual Machine in VirtualBox
2. Clone this repository git clone https://github.com/AbhishekAebi/AuctionDapp/
3. Open terminal and run truffle develop
4. Open another terminal and run the following commands:
    truffle compile
    truffle migrate --reset
    truffle test
5. Done - You should witness passing of test cases related to the Smart Contract functions such as registering bidders, placing bids and revealing winners

This project uses the following technologies:
1. Solidity v0.4.17
2. Truffle IDE v4.0.4
