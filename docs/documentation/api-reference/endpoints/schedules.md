# Расписание (Schedules)

Управление расписанием занятий.

## Эндпоинты

| Метод | Путь | Описание |
|-------|------|-----------|
| `POST` | `/api/v1/schedules` | Создание новой записи расписания |
| `GET` | `/api/v1/schedules/` | Получение списка расписаний |
| `GET` | `/api/v1/schedules/group/number/{number}` | Получение расписания по номеру группы |
| `GET` | `/api/v1/schedules/group/uuid/{uuid}` | Получение расписания по UUID группы |
| `GET` | `/api/v1/schedules/location/name/{name}` | Получение расписания по имени локации |
| `GET` | `/api/v1/schedules/location/uuid/{uuid}` | Получение расписания по UUID локации |
| `GET` | `/api/v1/schedules/room/number/{number}` | Получение расписания по номеру аудитории |
| `GET` | `/api/v1/schedules/room/uuid/{uuid}` | Получение расписания по UUID аудитории |
| `GET` | `/api/v1/schedules/subject/name/{name}` | Получение расписания по имени предмета |
| `GET` | `/api/v1/schedules/subject/uuid/{uuid}` | Получение расписания по UUID предмета |
| `GET` | `/api/v1/schedules/teacher/fn/{fn}` | Получение расписания по ФИО преподавателя |
| `GET` | `/api/v1/schedules/teacher/uuid/{uuid}` | Получение расписания по UUID преподавателя |
| `GET` | `/api/v1/schedules/uuid/{uuid}` | Получение расписания по UUID |
| `PUT` | `/api/v1/schedules/{uuid}` | Обновление расписания |
| `DELETE` | `/api/v1/schedules/{uuid}` | Удаление расписания |