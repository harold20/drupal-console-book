# database:log:clear
Удалить события из таблицы DBLog, фильтры доступны

**Использование:**
```
drupal database:log:clear [arguments] [options]
dblc
```

## Доступные параметры
Команда | Детали
-------|-------------
--type | Отфильтровать события по указанному типу
--severity | Отфильтровать события по указанному уровню важности
--user-id | Отфильтровать события по указанному идентификатору пользователя

## Доступные аргументы
Аргумент | Детали
---------|-------------
event-id | DBLog ID события

## Примеры
* Отчистить лог базы данных из таблицы DBLog
```
drupal database:log:clear \
  <database>
```
* Отчистить лог базы данных из таблицы DBLog, используя фильтры
```
drupal database:log:clear \
  <database> \
  --type=TYPE \
  --severity=SEVERITY
```
