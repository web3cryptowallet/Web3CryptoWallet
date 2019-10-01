# Web3 Crypto Wallet

Web3CryptoWallet is modern mobile wallet with dApps platform

![Web3 Crypto Wallet screenshot-1](/screenshots/screenshot1.jpg)

See Web3CryptoWallet demo:

[Web3CryptoWallet video @vimeo.com](https://vimeo.com/363434871)

# Prerequirements

- Animation CPU Platform for iOS (request us web3future@gmail.com for Animation CPU Beta via TestFligt)
- node v8.9.1+

# Setup

## Setup Web3 Crypto Wallet source code

```
git clone git@github.com:web3cryptowallet/Web3CryptoWallet.git acpu-web3-project/Web3CryptoWallet
```

## Setup Animation CPU bootloader source code

```
git clone git clone git@github.com:web3cryptowallet/acpul-boot.git acpu-web3-project/acpul-boot
```

## Startup Animation CPU server locally

Clone repo
```
git clone git@github.com:web3cryptowallet/acpu-server.git 
cd acpu-server
npm install
```

Configure config/config.js
```
let BASE = '/Users/user/acpu-web3-project' # your web3 project absolute path 
```

Run
```
node acpu-server.js
```

## Startup Web3 Crypto Wallet on mobile

1. Run Animation CPU   
2. Connect to your server via Bootloader 1.0, Web3CryptoWallet app runs immediatelly.

## Donate

Contact us web3future@gmail.com

## Contribute

Contact us web3future@gmail.com

## License

MIT

