# Crypto Seed Phrase Checker

This project is a seed phrase checker for Bitcoin and Ethereum networks. The script generates random seed phrases, checks if they have balances or transactions, and logs the results. It supports both Bitcoin (BTC) and Ethereum (ETH), sending notifications via Telegram for found wallets with balance or transactions.

## Features

- **BTC Seed Phrase Check**: Uses `bitcoinlib` to derive Bitcoin addresses and check their balances and transaction history.
- **ETH Seed Phrase Check**: Uses `web3.py` to check Ethereum wallets for balances and transactions.
- **Telegram Notifications**: Sends alerts to a Telegram bot when a wallet with a balance is found.
- **Customizable Generation**: Supports generating 12-word seed phrases from a set of BIP39 words.
- **Logging**: Results are logged to different text files based on the balance of the wallet.

## Installation

### Prerequisites

1. Python 3.x
2. [Infura](https://infura.io/) account (for Ethereum network access)
3. Telegram bot (for notifications)

### Python Dependencies

Install the required Python packages:

```bash
pip install requests web3 eth_account colorama bitcoinlib
