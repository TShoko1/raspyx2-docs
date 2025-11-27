
**`docs/documentation/api-reference/endpoints/rooms.md`**
```markdown
# Аудитории (Rooms)

Управление учебными аудиториями.

## Эндпоинты

| Метод | Путь | Описание |
|-------|------|-----------|
| `POST` | `/api/v1/rooms` | Создание новой аудитории |
| `GET` | `/api/v1/rooms/` | Получение списка аудиторий |
| `GET` | `/api/v1/rooms/number/{number}` | Получение аудитории по номеру |
| `GET` | `/api/v1/rooms/uuid/{uuid}` | Получение аудитории по UUID |
| `PUT` | `/api/v1/rooms/{uuid}` | Обновление аудитории |
| `DELETE` | `/api/v1/rooms/{uuid}` | Удаление аудитории |

## Примеры запросов

### Создание аудитории
```http
POST /api/v1/rooms
Content-Type: application/json

{
  "number": "101",
  "location_uuid": "123e4567-e89b-12d3-a456-426614174000",
  "capacity": 30
}