# Discord OTP Bot

A simple Discord bot that generates random 6-digit OTP (One-Time Password) codes.

## Features
- Generates secure 6-digit OTP codes
- 5-minute expiration time for each code
- Clean embed display with expiration countdown

## Setup
1. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

2. Create a Discord bot and get your bot token:
   - Go to [Discord Developer Portal](https://discord.com/developers/applications)
   - Create a new application
   - Go to the Bot section and create a bot
   - Copy your bot token

3. Replace `'YOUR_BOT_TOKEN'` in `bot.py` with your actual bot token

4. Run the bot:
   ```
   python bot.py
   ```

## Usage
Use the following command in any channel where the bot has access:
- `!otp` - Generates a new OTP code

The bot will respond with an embed containing:
- The 6-digit OTP code
- Expiration time countdown
- Visual indicators for better readability