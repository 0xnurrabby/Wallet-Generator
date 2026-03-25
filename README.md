# EVM Wallet Batch Generator

A simple browser-based tool to generate multiple EVM wallets locally.

## Features
- Generate 1 to 1000 wallets in one click
- Separate bulk sections for:
  - all addresses
  - all private keys
  - all phrases
- Per-wallet copy buttons
- Bulk copy buttons
- Export as TXT, JSON, or CSV
- Derivation path base input
- Phrase length options: 12 / 15 / 18 / 21 / 24 words

## How to use
1. Open `index.html` in a modern browser.
2. Enter the wallet count.
3. Choose phrase length.
4. Optionally change the derivation path base.
5. Click `Generate wallets`.
6. Copy or export as needed.

## Important security note
This tool displays private keys and recovery phrases in plain text on-screen.
Use it only on a trusted device and handle exports carefully.

## Tech note
This app uses ethers in the browser to generate wallets from random entropy.
