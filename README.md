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

    Create a .env file from the .env.example:

    bash

cp .env.example .env

Add your Etherscan API key to the .env file:

ETHERSCAN_API_KEY=your_api_key_here

Install the required packages:

bash

    pip install -r requirements.txt

Usage

Run the script:

bash

python gas_price_estimator.py

The current gas price will be displayed every minute.
