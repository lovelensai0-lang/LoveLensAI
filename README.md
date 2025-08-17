![Banner](lovelens-banner.svg)

# LoveLens AI

![Logo](lovelens-logo.svg)

Welcome to **LoveLens AI** — your always-available AI companion unlocked by Web3.

## Features

- Empathetic, supportive conversations with a gentle, playful tone
- Slightly romantic flair without crossing boundaries
- Token-gated access using [Unlock Protocol](https://unlock-protocol.com/) on the Polygon Amoy testnet
- Free tier with limited messages; premium unlock for unlimited chat

## Mission

Our mission is to explore meaningful connections between humans and AI while leveraging blockchain technology to ensure fair, community-driven access. LoveLens AI demonstrates how Web3 can create sustainable, user-centric digital experiences.

## Get Started

- **Chat Now**: [Start chatting](chat.html)
- **Buy Access Pass**: Coming soon — you will mint a LoveLens Access Pass NFT on Polygon Amoy to unlock unlimited conversations. After creating a lock with Unlock Protocol, update `config.json` with your `lockAddress` and the Buy Access button will point to the correct checkout link.

## Setup Notes

This project is deployed via GitHub Pages. To make the premium gating real:

1. Use MetaMask to add Polygon Amoy (chain id `80002`) and get test MATIC.
2. Go to the [Unlock Protocol dashboard](https://app.unlock-protocol.com/) and create a new **Lock** (NFT contract) with your chosen parameters.
3. Copy the lock address and paste it into `config.json` under `"lockAddress"`.
4. Commit the change and wait for GitHub Pages to redeploy. The Buy Pass links will now point to the Unlock checkout.

## Contributing

We welcome contributions via pull requests. Feel free to improve the UI, add features, or explore other Web3 integrations.
