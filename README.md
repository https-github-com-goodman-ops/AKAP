# AKAP

The AKA protocol is somewhat like LDAP for Ethereum. It allows you to
reference content and data, and also navigate structures in the context
of nodes and a directed acyclic graph.

The contract is deployed and is ready for use, see below for details.

Please have a read of the [white paper](WHITEPAPER.md).

## Truffle commands

Assuming you have [Truffle](https://www.trufflesuite.com/) installed
you can run the usual commands:

`truffle build`

`truffle test`

You might need to do:
 
 `npm install @openzeppelin/contracts`
 
 `npm install @openzeppelin/test-helpers`

## Official build

The "officially compiled" AKAP contract json files can be found under `build/contracts`.

This contract has been deployed to
[Goerli](https://goerli.etherscan.io/address/0xaaccaab0e85b1efcecdba88f4399fa6cab402349),
[Rinkeby](https://rinkeby.etherscan.io/address/0xaaccaab0e85b1efcecdba88f4399fa6cab402349),
[Kovan](https://kovan.etherscan.io/address/0xaaccaab0e85b1efcecdba88f4399fa6cab402349),
[Ropsten](https://ropsten.etherscan.io/address/0xaaccaab0e85b1efcecdba88f4399fa6cab402349) and of course
[Mainnet](https://etherscan.io/address/0xaaccaab0e85b1efcecdba88f4399fa6cab402349).

Contract address is: 0xaacCAAB0E85b1EfCEcdBA88F4399fa6CAb402349

Compiled using below versions:

```
Truffle v5.1.4 (core: 5.1.4)
Solidity v0.5.12 (solc-js)
Node v13.3.0
Web3.js v1.2.1
macOS Catalina v10.15.2
```

The solc optimizer was enabled with runs = 200.

## AKAP UI

There's a browser available on [akap.me/browser](https://akap.me/browser), and you can find the repo for this [here](https://github.com/cfelde/AKAP-browser).