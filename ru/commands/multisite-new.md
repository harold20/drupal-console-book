# multisite:new
Настраивает файлы для мультисайт установки.

**Использование:**
```
drupal multisite:new [arguments] [options]
mun
sn
```

## Доступные параметры
Команда | Детали
-------|-------------
--copy-default | Копирует текущий сайт из установки по умолчанию.

## Доступные аргументы
Аргумент | Детали
---------|-------------
directory | Имя каталога, который будет создан в 'sites'.
uri | URI сайта, который будет добавлен в sites.php.

## Примеры
* Устанавливает файлы для мультисайт установки, указывая путь и uri
```
drupal multisite:new  vendor/newsite http://mysite.example.com
```
