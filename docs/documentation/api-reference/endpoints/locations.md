# Локации (Locations)

Управление местоположениями (корпусами).

## Эндпоинты

| Метод | Путь | Описание |
|-------|------|-----------|
| `POST` | `/api/v1/locations` | Создание новой локации |
| `GET` | `/api/v1/locations/` | Получение списка локаций |
| `GET` | `/api/v1/locations/name/{name}` | Получение локации по имени |
| `GET` | `/api/v1/locations/uuid/{uuid}` | Получение локации по UUID |
| `PUT` | `/api/v1/locations/{uuid}` | Обновление локации |
| `DELETE` | `/api/v1/locations/{uuid}` | Удаление локации |