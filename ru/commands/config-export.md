# config:export
Экспорт текущей конфигурации приложения.

**Использование:**
```
drupal config:export [options]
ce
```

## Доступные параметры
Команда | Детали
-------|-------------
--directory | Определяет каталог экспорта для сохранения конфигурации.
--tar | Если установлено, конфигурация будет экспортирована в архив.
--remove-uuid | Если установлено, конфигурация будет экспортирована без uuid ключа.
--remove-config-hash | Если установлено, конфигурация будет экспортирована без хеш ключа сайта по умолчанию.

## Примеры
* Опционально вы можете добавить путь для экспорта
```
drupal config:export  \
  --directory="path/to/export"
```
* Экспорт будет заархивирован и/или uuid и хеши конфигурации будут удалены.
```
drupal config:export  \
  --directory="path/to/export" \
  --tar \
  --remove-uuid \
  --remove-config-hash
```
