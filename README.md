# [Webpack] project template

В проекте используется менеджер пакетов ```yarn```. 


## Установка:

    1. git clone https://github.com/klv-codehub/webpack-template

    2. cd webpack-template

    3. yarn
    
## Документация

Для работы со стартовым шаблоном используются yarn (npm) скрипты.

```yarn start```

Запускает проект в отслеживаемом режиме "разработка". В данном режиме не производится конкатенация/минификация файлов. Работа осуществляется с помощью плагина ```webpack-dev-server```, изменения сохраняются в памяти (не пытайтесь найти папку dist).

---

```yarn build```

Сборка проекта в сжатом виде (однократная). Отслеживание не производится. Результирующие файлы сохраняются в папке dist.


```yarn serv```

Запуск сервера ```node-static``` для тестирования собранного проекта.
