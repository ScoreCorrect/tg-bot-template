# Telegram Bot

Simple Python Telegram bot template using `python-telegram-bot`.

## Setup

```bash
python3 -m venv venv
source venv/bin/activate      # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

## Configuration

```bash
cp .env.example .env
```

Edit `.env` and set your bot token (get one from [@BotFather](https://t.me/BotFather)):

```
BOT_TOKEN=your_telegram_bot_token_here
```

## Run

```bash
source venv/bin/activate
python bot.py
```

## Commands

| Command | Description |
|---------|-------------|
| `/start` | Greet the user |
| `/help` | Show help message |
| _(any text)_ | Echo the message back |

## Project Structure

```
tg-bot-demo/
├── bot.py            # Main bot logic
├── requirements.txt  # Dependencies
├── .env              # Secrets (not committed)
├── .env.example      # Secret template
└── .gitignore
```
