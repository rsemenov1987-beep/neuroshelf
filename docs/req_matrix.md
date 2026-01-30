| User story | Описание|  API Endpoint |  Таблица БД | Приоритет |
|---------|----------|----------|---------|----------|
| US-001 |Регистрация| POST /auth/register|users| High|
| US-002 |Просмотр профиля| GET /users/me |users| High|
| US-003 |Просмотр навков, совместимых с версией|GET /skill-packs?compatible=true|skill_packs + compatibility| High|
| US-004 |Просмотр подробной информации о навыке| GET /skill_packs/{skill_id} |skill_packs| High|
| US-005 |Синхронизация| POST /sync/start| sync_sessions | High|
| US-102 |Добавление навыка на полку| POST /admin/skill-packs	| skill_packs | High|
