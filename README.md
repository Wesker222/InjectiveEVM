# InjectiveEVM

Automated registration and faucet claiming for the **Injective EVM Testnet**.

## Overview

This project provides a Python automation script using Puppeteer (Pyppeteer) to streamline the process of registering on the Injective EVM Testnet and claiming testnet tokens from the official faucet.

Injective’s EVM Testnet offers a native Ethereum Virtual Machine environment on a blazing-fast Layer 1 blockchain, enabling developers to deploy Solidity smart contracts and users to explore decentralized finance applications with zero friction.

## Features

- Automated navigation to the Injective MultiVM Testnet portal
- RPC configuration (if applicable)
- Automated faucet token claiming on the Injective Testnet faucet site
- Basic ecosystem exploration navigation
- Headless or headed browser automation with Pyppeteer

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Pyppeteer (`pip install pyppeteer`)
- A valid Injective testnet wallet address (for faucet claiming)

### Installation

Clone the repository:

```bash
git clone https://github.com/Wesker222/InjectiveEVM.git
cd InjectiveEVM
```

Install dependencies:

```bash
pip install -r requirements.txt
```

*(If `requirements.txt` is not provided, install Pyppeteer directly)*

```bash
pip install pyppeteer
```

### Usage

Edit the script to set your testnet wallet address:

```python
wallet_address = 'your_test_wallet_address_here'
```

Run the automation script:

```bash
python automate_injective_testnet.py
```

The script will:

1. Open the Injective MultiVM Testnet portal
2. Attempt to add RPC configuration (if required)
3. Navigate to the faucet page and claim testnet tokens
4. Navigate back to the ecosystem portal for exploration

## About Injective EVM Testnet

Injective’s EVM Testnet is a high-performance, fully native Ethereum Virtual Machine environment embedded into Injective’s Layer 1 blockchain. It supports seamless deployment of Solidity smart contracts and interoperates with Injective’s advanced modules and MultiVM architecture.

- **MultiVM Architecture:** Enables interoperability between EVM and WASM smart contracts.
- **Frictionless Onboarding:** No browser extensions or seed phrases required to start.
- **Fast and Secure:** Designed for high throughput and low latency onchain finance applications.

Learn more and explore the testnet here: [https://multivm.injective.com/](https://multivm.injective.com/)

Request testnet funds here: [https://testnet.faucet.injective.network/](https://testnet.faucet.injective.network/)

## Contributing

Contributions are welcome! Please open issues or pull requests for bug fixes, improvements, or new features.

## License

This project is open source under the MIT License.

