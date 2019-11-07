# Klaytn Threshold Wallet

![npm](https://badge.fury.io/js/%40kzen-networks%2Ftezos-thresh-wallet.svg)

Klaytn wallet and JS SDK powered by two-party ECDSA.

## Installation
```sh
yarn install @kzen-networks/tezos-thresh-wallet
```

## Usage
Server (acts as the co-signer in the two-party signing protocol):
```js

```
Client:
```js

```

## Demo
You can also use a demo using the command line.<br>
Server:
```sh
$ demo/server
```
Client:
```sh
Usage: client [options] [command]

Options:
  -h, --help                                                    output usage information

Commands:
  address
  balance <address>
  token_balance <address> <token_contract_address>
  token_listen <to> <token_contract_address>
  token_transfer <from> <to> <amount> <token_contract_address>
  transfer <from> <to> <klay_amount>

```

|![Transfer demo](https://raw.githubusercontent.com/KZen-networks/tezos-thresh-wallet/master/demo/tezos-tss-demo.gif "Tezos Threshold Wallet Demo")|
|:--:|

## Development
```js
yarn install
yarn run build
```
Built files will be located in the `dist` folder.

## License
MIT

## Credits
This work is a fork extending Klaytn's [caver-js](https://github.com/klaytn/caver-js)
