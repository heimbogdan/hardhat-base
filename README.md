# hardhat-base

If you want to make your own hardhat project from zero, follow the tutorial [here](https://hardhat.org/tutorial).

## Pre-prerequisites

* [NodeJs 18.12.1](https://nodejs.org/download/release/v18.12.1/) or [newer](https://nodejs.org/en/)

## Project structure

* `./contracts`
* `./test`
* `./hardhat.config.js`
* `./package.json`
* `./README.md`

## Usage

```shell

# Compile
npx hardhat compile

# Test
npx hardhat test

#Run a script on a specific network
npx hardhat run scripts/deploy.js --network <network-name>
# !!! Running it without the --network parameter would cause
# the code to run against an embedded instance of Hardhat Network

```
