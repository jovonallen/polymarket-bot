# Polymarket Bot

## Project Overview
The Polymarket Bot is a trading bot designed to interact with the Polymarket platform, facilitating automated trades based on market conditions. It utilizes advanced algorithms to optimize trading strategies and enhance user experience.

## Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone https://github.com/jovonallen/polymarket-bot.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd polymarket-bot
   ```
3. **Install dependencies:**
   ```bash
   npm install
   ```
4. **Configure environment variables:**
   Create a `.env` file in the root directory and set the following variables:
   ```
   POLYMARKET_API_KEY=your_api_key
   ```

## Features
- Automated trading based on real-time market data.
- User-friendly configuration options.
- Detailed logging of trades and performance.
- Support for various trading strategies.

## Configuration Guide
Edit the `.env` file to customize your bot's settings. Key configuration options include:
- `POLYMARKET_API_KEY`: Your API key for Polymarket access.
- `TRADE_STRATEGY`: The trading strategy to employ (e.g., "arbitrage", "market making").

## Usage Examples
To start the bot, run the following command:
```bash
npm start
```
The bot will begin executing trades based on the configured strategy. Check the logs for real-time updates on trades executed.

For more detailed usage, refer to the documentation within the repository or the Wiki page.