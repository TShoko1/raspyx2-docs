
# Быстрый старт

Начните работу с API за 5 минут.

## 1. Получение токена доступа


curl -X POST "https://zefixed.ru/raspyx/api/v1/users/login" \
  -H "Content-Type: application/json" \
  -d '{"username": "demo", "password": "demo"}'