# Auto Filter Bot V2

A Telegram bot built with Python and Pyrogram that searches indexed channels for files matching a user's query and returns matching results through the bot.

## Features
- Search files across connected Telegram channels
- Supports document, video, and music searches
- Group-based channel linking and unlinking
- MongoDB-backed configuration/storage
- Admin/auth-user controls

## Setup
```bash
pip install -r requirements.txt
python3 main.py
```

Configure the required Telegram and MongoDB environment values in `config.py` before starting the bot.

## Stack
Python · Pyrogram · MongoDB · TgCrypto

## License
MIT
