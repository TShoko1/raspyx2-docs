# Быстрый старт

Начните работу с API за 5 минут

## Предварительные требования

- Go 1.19+
- Доступ к API endpoint
- Valid API token

## Установка и настройка

1. **Получите токен доступа:**
```bash
curl -X POST https://api.raspyx2.auth/token \
  -H "Content-Type: application/json" \
  -d '{"username": "your_username", "password": "your_password"}'