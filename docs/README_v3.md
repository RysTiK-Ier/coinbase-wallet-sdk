# Coinbase Wallet SDK v3.x.x
## [Playground]  (https://coinbase.github.io/coinbase-wallet-sdk/)
**[Developer docs]**(https://docs.cloud.coinbase.com/wallet-sdk/docs)

The **Coinbase Wallet SDK** (formerly **WalletLink**) enables developers to connect their dApps to **Coinbase Wallet** on both **mobile web** (iOS and Android) and **desktop** platforms.

- **Mobile**: Users can connect to your mobile web dApp via a deep link to the dApp browser in the **Coinbase Wallet mobile app**.  
- **Desktop**: Users can connect to your desktop app using a **QR code** scanned in the Coinbase Wallet mobile app, or by using the **Coinbase Wallet Chrome Extension**.

The Wallet SDK is **open-source**, with **minimal dependencies** to maximize security and reduce code bloat. Simply drop a few lines of code into your dApp, and the SDK handles the rest.

---

## Getting Started

This repository uses a **Yarn workspace**. To get started, run:

```bash
yarn install


# To start the development server run the following command. This starts a nextjs app on port 3001. Any changes in the SDK become available through the app.
yarn dev

# To interact with the SDK directly:
yarn workspace @coinbase/wallet-sdk "<command>"

# To lint all files
yarn lint

# To typecheck all files
yarn typecheck
```

## Installing and Upgrading

> The installation package for **Coinbase Wallet SDK** (formerly WalletLink) is now named `@coinbase/wallet-sdk`.

- This [readme](/packages/wallet-sdk/README.md) contains brief instructions to get up and running.
- Visit our [public developer docs](https://docs.cloud.coinbase.com/wallet-sdk/docs) for more detail, including samples for integrating Coinbase Wallet using libraries like [web3-react](https://github.com/Uniswap/web3-react), [web3modal](https://github.com/Web3Modal/web3modal), [Web3-Onboard](https://docs.blocknative.com/onboard), and [wagmi](https://wagmi.sh/).

## Libraries using Coinbase Wallet SDK

- [blocknative/onboard](https://github.com/blocknative/onboard)
- [wagmi](https://github.com/tmm/wagmi)
- [web3-react](https://github.com/NoahZinsmeister/web3-react)
- [web3modal](https://github.com/Web3Modal/web3modal)
