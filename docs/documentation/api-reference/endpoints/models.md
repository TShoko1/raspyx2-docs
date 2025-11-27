
**`docs/documentation/api-reference/models.md`**
```markdown
# Модели данных

## DTO (Data Transfer Objects)

### Запросы (Request)
- `dto.CreateGroupRequest` - Создание группы
- `dto.CreateLocationRequest` - Создание локации  
- `dto.CreateRoomRequest` - Создание аудитории
- `dto.CreateSubjectRequest` - Создание предмета
- `dto.CreateSubjectTypeRequest` - Создание типа предмета
- `dto.CreateTeacherRequest` - Создание преподавателя
- `dto.LoginUserRequest` - Аутентификация пользователя
- `dto.RegisterUserRequest` - Регистрация пользователя
- `dto.ScheduleRequest` - Создание расписания
- `dto.UpdateGroupRequest` - Обновление группы
- `dto.UpdateLocationRequest` - Обновление локации
- `dto.UpdateRoomRequest` - Обновление аудитории
- `dto.UpdateSubjectRequest` - Обновление предмета
- `dto.UpdateSubjectTypeRequest` - Обновление типа предмета
- `dto.UpdateTeacherRequest` - Обновление преподавателя
- `dto.UpdateUserRequest` - Обновление пользователя

### Ответы (Response)
- `dto.CreateGroupResponse` - Ответ создания группы
- `dto.CreateLocationResponse` - Ответ создания локации
- `dto.GetGroupsResponse` - Ответ получения групп
- `dto.GetLocationsResponse` - Ответ получения локаций
- `dto.GetRoomsResponse` - Ответ получения аудиторий
- `dto.GetSubjectTypesResponse` - Ответ получения типов предметов
- `dto.GetSubjectsResponse` - Ответ получения предметов
- `dto.GetTeachersResponse` - Ответ получения преподавателей
- `dto.GetUsersResponse` - Ответ получения пользователей

### Другие модели
- `dto.Day` - День недели
- `dto.Pair` - Пара (занятие)
- `dto.TeacherDTO` - DTO преподавателя
- `dto.Week` - Тип недели (числитель/знаменатель/обе)

## Основные модели (Models)
- `models.Group` - Группа
- `models.Location` - Локация
- `models.Room` - Аудитория
- `models.Subject` - Предмет
- `models.SubjectType` - Тип предмета
- `models.Teacher` - Преподаватель
- `models.User` - Пользователь

## Общие ответы
- `v1.ResponseError` - Ответ с ошибкой
- `v1.ResponseOK` - Успешный ответ