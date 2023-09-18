# TelegramChatBot

# Telegram AI Bot 
This particular Telegram bot has been designed to utilize the advanced technology of OpenAI in order to provide thoughtful and informative responses to all user messages. Its primary goal is to assist users in any way possible, while maintaining a helpful, fair, and safe experience for all who use it. It is important to note that this bot's abilities are powered by the latest AI technology, yet it is programmed to communicate with users in a natural and human-like manner, ensuring that all interactions feel organic and seamless.

## Overview

This AI-assistant utilizes the Python Telegram Bot API wrapper in combination with either the OpenAI API or Anthropic's G4F library to provide users with helpful, fair, and safe responses. Upon receiving the `/start` command, the bot will greet the user with a welcoming message. It is designed to effectively handle text messages from users by generating responses utilizing advanced language models such as GPT-3.5. The bot is also capable of asynchronously generating GPT-3.5 responses through the use of a thread pool executor. To ensure the security of the user's information, the bot is configured to load API keys and tokens from environment variables.

## Setup
1. Sign up for an [OpenAI](https://openai.com/) API key.

2. Save the API keys in a `.env` file:

```
OPENAI_KEY=sk-...
TG_BOT_TOKEN=123456:ABC...
```
3. Install requirements:

```
pip install python-telegram-bot python-dotenv openai g4f
```
4. Run `python telegram_bot.py` to start the bot.

5. Message your bot and interact!

## Customizing

- Switch between using OpenAI and GPT-3.5 by commenting/uncommenting code and API keys.
- Modify the `echo()` handler to call different AI models.
- Add new command handlers for additional bot features.

## Resources

- [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)
- [OpenAI API](https://openai.com/api/)
- [GPT-3.5 API](https://www.anthropic.com/)
