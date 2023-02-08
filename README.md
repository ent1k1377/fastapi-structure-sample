# Шаблон структуры FastAPI проекта
[youtube](https://www.youtube.com/watch?v=IpSRs6ZNA5k)

## Структура
- app
    - configuration
    - internal
    - pkg
- docker
- ...

## Описание структуры
- **app** - директория проекта
- **configuration** - Создание базовой конфигурации сервера, определение механизма регистрации путей и событий
- **internal** - Основной код FastAPI
- **pkg** - Хранение всех взаимодействий со стороними сервисами(postgresql, redis...)