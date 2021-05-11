# bch-ipfs-service

[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](http://standardjs.com) [![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)

This repository is forked from the [ipfs-service-provider](https://github.com/Permissionless-Software-Foundation/ipfs-service-provider) boilerplate. The purpose of this app is to provide access to the BCH network through both REST API over HTTP, and JSON RPC over IPFS. This service allows flexible, uncensorable web-based wallets by provided the 'back end' service needed by a wallet to access the BCH blockchain.

There are two main directories in this repository:

- [`service`](./service) is the fork of ipfs-service-provider, which provides access to the BCH blockchain using JSON RPC over IPFS as well as a conventional REST API.
- [`consumer`](./consumer) simulates a consumer of the above services. It provides end-to-end testing by accessing each endpoint provided by the service using both REST API over HTTP, and JSON RPC over IPFS.

## License

MIT
