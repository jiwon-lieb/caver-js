# Getting Started

## Prerequisites

The following packages are required to use the caver-js library.

* [Node.js](https://nodejs.org/en/download)
* [npm](https://www.npmjs.com/get-npm)
* [Solidity](https://solidity.readthedocs.io/en/develop/installing-solidity.html)
* [nvm](https://github.com/nvm-sh/nvm)

**NOTE**: Use the below versions for node.js

* lts/erbium [12.21.0](https://nodejs.org/dist/latest-v12.x/)
* lts/fermium [14.16.0](https://nodejs.org/dist/latest-v14.x/)

You are probably using a different version of node.js. You can use the Node Version Manager [NVM](https://github.com/nvm-sh/nvm) to change to the version supported by caver-js.

Testing in caver-js is implemented using the mocha testing framework. If you want to run unit tests in caver-js, install mocha:

* [mocha](https://mochajs.org/#installation)

## Install caver-js

Install caver-js using npm:

```javascript
npm install caver-js
```

**Note**: package.json file should exist in the same install path. If it does not exist, generate package.json via `npm init`.

To install a specific version of caver-js, use the following command:

```
npm install caver-js@X.X.X
```
