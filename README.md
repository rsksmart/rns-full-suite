<img src="/logo.png" alt="logo" height="200" />

# RIF Name Service Full Suite

This solution includes a migrations file that deploys the full suite of RNS in your local environment.

It also registers a name (`alice.rsk`) during the migration so you can start managing it from the beggining.

Find the whole architecture and documentation in our [RSK Developers Portal](https://developers.rsk.co/rif/rns/libs/smart-contracts)

## Prerequisites

- [Truffle](https://www.trufflesuite.com/) (^5.0.30)

## Setup

```
npm install
```

Then, go to `migrations/2_rns_full_suite.js` and replace `DEV_ADDRESS` with your address.

Note: if you will use this suite in a browser, we strongly recommend to use [Nifty](https://chrome.google.com/webstore/detail/nifty-wallet/jbdaocneiiinmjbjlgalhcelgbejmnid?hl=en) or [Metamask](https://metamask.io/) wallets. Both work as Google Chrome extensions.

```
truffle develop
```

Once the Truffle Console is running

```
truffle(development)> migrate
```

These instructions assume you are running the Truffle local blockchain with the default settings. If you are using another blockchain such as Ganache, just change the port in the `truffle-config.js` file.
