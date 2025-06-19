
# 🇨🇳 Pinduoduo Telegram Bot

Готовый Telegram-бот для заказов с Pinduoduo. Работает на Fly.io.

## 📦 Содержимое

- `bot.py` — основной бот
- `requirements.txt` — зависимости
- `Dockerfile` — сборка контейнера
- `fly.toml` — конфигурация Fly.io

## 🚀 Деплой на Fly.io

1. Установи Fly CLI: https://fly.io/docs/hands-on/install-flyctl/
2. В терминале:

```bash
flyctl launch  # если fly.toml нет, иначе пропусти
flyctl secrets set BOT_TOKEN=твой_токен ADMIN_ID=твой_id
flyctl deploy
```

Бот будет доступен по адресу https://имя.fly.dev
