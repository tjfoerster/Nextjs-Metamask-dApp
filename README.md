## About

The project base is forked from [MetaMask/Nextjs-Starter](https://github.com/MetaMask/Nextjs-Starter)

This dApp is a prototype that is intended to illustrate the approach of blockchain technology in the area of classic ERP systems. It represents a business use case from human resource management.

Technologies used are:
- [MetaMask](https://metamask.io/) is a crypto wallet and gateway to dApps as a browser extension
- [Truffle Suite](https://trufflesuite.com/) for developing of smart contracts (for the Ethereum blockchain)
- [Solidity](https://docs.soliditylang.org/en/latest/) is the programming language for smart contracts (Ethereum)
- [NextJS](https://nextjs.org/) for the ui of the dApp

## Get started
1. Checkout this repository.
2. Switch in the project folder and run `npm install`
3. Run `truffle compile` to build production ready files for the blockchain.
4. Get [Ganache](https://trufflesuite.com/ganache/) for your system.
5. Host a local ethereum blockchain with Ganache for experimenting. (Use port 7545 or edit truffle-config.js!)
6. Deploy the smart contracts to blockchain with `truffle deploy`.
7. Run `npm dev` and open in your browser `http://localhost:3000`.
8. Get [MetaMask](https://metamask.io/) for your browser.
9. Connect MetaMask to your local blockchain.
10. Import accounts into Metamask from your local blockchain.
11. Have fun with the dApp!
