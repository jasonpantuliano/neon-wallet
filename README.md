[![CircleCI](https://circleci.com/gh/CityOfZion/neon-wallet.svg?style=svg)](https://circleci.com/gh/CityOfZion/neon-wallet)

# Neon Wallet

![wallet](/wallet.png)

The aim of this project is to port the current NEO web wallet to electron with a better UI.

## Installation

A standalone app will be available soon. For now, you will need to build the wallet manually.

### Required Tools and Dependencies

  - Node (This project uses the current LTS node version, which is `v6.11.0`)
  - `npm install -g webpack` Global Webpack 
  - `npm install -g jest` Unit testing framework

### Developing and Running

Execute these commands in the project's root directory:

  - `npm install` Installing node dependencies
  - `webpack` or `webpack --watch` for live reload.
  - `npm start` for running the project
  - `npm test` or `npm test-watch` for live testing.
