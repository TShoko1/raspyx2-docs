# Аутентификация

## Получение токена

```http
POST /api/v1/users/login
Content-Type: application/json

{
  "username": "your_username",
  "password": "your_password"
}