# Пульт охраны банка

Это внутренний репозиторий для сотрудников банка. Если вы попали сюда случайно, то у вас не полуяиться запустить его,
т.к. вы не имеете доступа к БД, но вы можете использовать код верстки или посмотреть как реализованы запросы к БД.

Пульт охраны - это сайт, который можно подключать к удаленной базе данных с визитами и карточками пропуска сотрудника 
банка.

## Окружение
Тип операционной системы - Windows, Lunix, Mac. Браузер для запуска - любой.

### Установка скрипта
Python3 должен быть уже установлен. 
Затем используйте `pip` (или `pip3`, есть конфликт с Python2) для установки зависимостей:
```
pip install -r requirements.txt
```

## Цели проекта
Автоматизировать систему учета посещений банковского хранилища с целью недопущения внутрибанковских краж.