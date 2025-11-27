# Аутентификация

## Получение токена

Для получения токена выполните запрос:

```
curl -X 'POST' \
  'https://zefixed.ru/raspyx/api/v1/users/login' \
  -H 'accept: application/json' \
  -H 'Content-Type: application/json' \
  -d '{
  "password": "YWNjZXNzdG9hcGk=",
  "username": "accesstoapi"
}'
```

В ответ вы получите JWT токен:

```
{
  "status": "OK",
  "response": {
    "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJhY2Nlc3NfbGV2ZWwiOjUwLCJleHAiOjE3NjQzNTcyNDgsInN1YiI6ImFjY2Vzc3RvYXBpIn0.pYalhMoYqrHzKEj7MadRE5XJT4arFExp2gzfazcVU10",
    "token_type": "bearer"
  }
}
```

## Использование токена

Добавьте полученный токен в заголовок Authorization:

```
GET https://zefixed.ru/raspyx/api/v1/groups
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...

Пример с curl:

curl -X GET "https://zefixed.ru/raspyx/api/v1/groups" \
  -H "Authorization: Bearer ваш_токен_здесь"
```