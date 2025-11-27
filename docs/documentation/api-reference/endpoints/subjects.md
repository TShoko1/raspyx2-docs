
**`docs/documentation/api-reference/endpoints/subjects.md`**
```markdown
# Предметы (Subjects)

Управление учебными предметами.

## Эндпоинты

| Метод | Путь | Описание |
|-------|------|-----------|
| `POST` | `/api/v1/subjects` | Создание нового предмета |
| `GET` | `/api/v1/subjects/` | Получение списка предметов |
| `GET` | `/api/v1/subjects/name/{name}` | Получение предмета по имени |
| `GET` | `/api/v1/subjects/uuid/{uuid}` | Получение предмета по UUID |
| `PUT` | `/api/v1/subjects/{uuid}` | Обновление предмета |
| `DELETE` | `/api/v1/subjects/{uuid}` | Удаление предмета |