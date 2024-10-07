

# Crypto Seed Phrase Checker


## Overview

The **Crypto Seed Phrase Checker** is a powerful tool designed to check the validity and status of Bitcoin (BTC) and Ethereum (ETH) seed phrases. It generates random seed phrases, derives their associated wallet addresses, and checks for any balances or transactions. Additionally, it sends notifications via Telegram for any wallets found with balances or transaction history.

## Features

- **BTC Seed Phrase Check**: Utilizes the `bitcoinlib` library to derive Bitcoin addresses and evaluate their balances and transaction history.
- **ETH Seed Phrase Check**: Employs `web3.py` to check Ethereum wallets for balances and transaction details.
- **Real-Time Telegram Notifications**: Sends alerts through a Telegram bot whenever a wallet with a balance is detected.
- **Customizable Seed Phrase Generation**: Supports the generation of 12-word seed phrases using a predefined set of BIP39 words.
- **Detailed Logging**: Results are logged into different text files based on the wallet balance.

## Installation

### Prerequisites

To get started, ensure you have the following:

1. **Python 3.x**: Install the latest version from [Python's official website](https://www.python.org/downloads/).
2. **Infura Account**: Sign up at [Infura](https://infura.io/) to access the Ethereum network.
3. **Telegram Bot**: Create a Telegram bot to send notifications (you can use [BotFather](https://t.me/botfather) to create one).

### Python Dependencies

Install the necessary Python packages using pip:

```bash
pip install requests web3 eth_account colorama bitcoinlib
```
## OWNER

This version includes your Telegram handle for users who might want to collaborate on blockchain projects. Let me know if you need any further modifications!
**contact me**: [telegram](https://t.me/nouredinekn)
