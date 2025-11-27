# Аутентификация

## Получение токена

Для получения токена выполните запрос:

```http
POST https://zefixed.ru/raspyx/api/v1/users/login
Content-Type: application/json

{
  "username": "ваш_логин",
  "password": "ваш_пароль"
}

В ответ вы получите JWT токен:
{
  "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...",
  "expires_at": "2024-01-15T12:00:00Z"
}


## Использование токена

Добавьте полученный токен в заголовок Authorization:

GET https://zefixed.ru/raspyx/api/v1/groups
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...


Пример с curl:

curl -X GET "https://zefixed.ru/raspyx/api/v1/groups" \
  -H "Authorization: Bearer ваш_токен_здесь"