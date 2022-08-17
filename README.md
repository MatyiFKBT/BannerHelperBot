# BannerHelperBot

Telegram Bot that helps with banners in Ingress. Uses Bannergress for data.

## Running

### Railway (one-click deploy)

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/ANwuAj?referralCode=xNLBXG)

### Locally (using Docker compose)

Fill in Telegram your bot token you received from https://t.me/BotFather in the `docker-compose.yml` file, and run:

```sh
docker compose up -d
```

### Locally (using Python)
Install dependencies:
```sh
pip install -r requirements.txt
```
Set your Telegram bot token as an env variable and run 
```sh
python main.py
```