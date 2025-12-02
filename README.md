# Ethereum Gas Calculator

<div align="center">
  ⛽
</div>

A simple, single-file HTML calculator for estimating Ethereum transaction costs in real-time.

## Features

- Calculate gas costs in ETH and USD
- Three gas price tiers: Low, Average, Fast
- Flexible input formats: `21000`, `21,000`, or `21k`
- Real-time prices from Etherscan API
- Works locally in your browser

## Usage

1. Open `gas_cost.html` in your browser
2. Enter your Etherscan API key (get one free at [etherscan.io](https://etherscan.io/apis))
3. Enter the gas amount for your transaction
4. Click Calculate

## Common Gas Amounts

- Simple ETH transfer: `21000`
- ERC-20 token transfer: `65000`
- Uniswap swap: `150000`
- NFT mint: `100000` - `300000`

## Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Etherscan API key (free)
- Internet connection for API calls