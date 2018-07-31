Bitcore
=======

This is the official Bitcore infastructure for the QUAR network. It will allow for the development of lightweight architecture such as copay, web wallets and will play a vital role in the production of QUAR pay.

[![NPM Package](https://img.shields.io/npm/v/bitcore.svg?style=flat-square)](https://www.npmjs.org/package/bitcore)
[![Build Status](https://img.shields.io/travis/bitpay/bitcore.svg?branch=master&style=flat-square)](https://travis-ci.org/bitpay/bitcore)

Infrastructure to build Bitcoin and blockchain-based applications for the next generation of financial technology.


Before you begin you'll need to have Node.js v4 or v0.12 installed. There are several options for installation. One method is to use [nvm](https://github.com/creationix/nvm) to easily switch between different versions, or download directly from [Node.js](https://nodejs.org/).
```bash
npm install -g bitcore-QUAR
```
Spin up a full node and join the network:
```bash
npm install -g bitcore-QUAR
bitcored
```
You can then view the Insight block explorer at the default location: `http://localhost:3001/insight`, and your configuration file will be found in your home directory at `~/.bitcore`.
Create a transaction:
```js
var bitcore = require('bitcore-dash');
var transaction = new bitcore.Transaction();
var transaction.from(unspent).to(address, amount);
transaction.sign(privateKey);

Based on Bitpays origional bitcore infastructure white can be found at https://github.com/bitpay/bitcore
Copyright 2013-2017 BitPay, Inc. Bitcore is a trademark maintained by BitPay, Inc.
