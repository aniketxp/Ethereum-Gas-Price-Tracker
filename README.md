# Ethereum-Gas-Price-Tracker
A robust Python script for real-time monitoring of Ethereum gas prices using the Etherscan API.

# Gas Price Estimator

A simple Python script that fetches the current gas price on the Ethereum network using the Etherscan API.

## Features
- Securely fetches gas prices using environment variables.
- Monitors gas prices every 60 seconds.
- Error handling for network requests.

## Getting Started

### Prerequisites
- Python 3.x
- An Etherscan API key (sign up at [Etherscan](https://etherscan.io/)).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/gas-price-estimator.git
   cd gas-price-estimator

2. Create a .env file from the .env.example:
cp .env.example .env


3. Add your Etherscan API key to the .env file:
ETHERSCAN_API_KEY=your_api_key_here


4. Install the required packages:
   pip install -r requirements.txt

Usage
Run the script:

python gas_price_estimator.py
