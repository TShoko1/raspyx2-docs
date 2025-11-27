# Группы (Groups)

Управление учебными группами.

## Эндпоинты

| Метод | Путь | Описание |
|-------|------|-----------|
| `POST` | `/api/v1/groups` | Создание новой группы |
| `GET` | `/api/v1/groups/` | Получение списка групп |
| `GET` | `/api/v1/groups/number/{number}` | Получение группы по номеру |
| `GET` | `/api/v1/groups/uuid/{uuid}` | Получение группы по UUID |
| `PUT` | `/api/v1/groups/{uuid}` | Обновление группы |
| `DELETE` | `/api/v1/groups/{uuid}` | Удаление группы |

## Примеры запросов

### Создание группы
```http
POST /api/v1/groups
Content-Type: application/json

{
  "number": "ПМ-2101",
  "faculty": "ФПМИ"
}