﻿# max_volands


## Подготовка проекта

* В кансоли, перейдите к проекту и установите виртуальное окружение командой
    - Структура проекта
    ```python
        Work_dir
          |____max_volands
            |___about
            |___cart
            |___order
            |___auth
            |___store
            |___static
            |___templates
          |____my_venv
          |____.gitignore
          |____README.md

    ```
```html
    python -m venv (your_name_env)
```

* После установки активируйте виртуальное окружение
    - <b>в Windows</b>
    ```html
        venv\Scripts\activate
    ```
    - <b>в UNIX system</b>
    ```html
        source (your_name_env)/bin/activate
    ```
    
* Установите все зависимости для запуска проекта
```html
    pip install -r requirements.txt
```
* Что бы посмотреть какие зависимости установлены, поможет команда
```html
    pip freeze
```

* <b>Проект готов к запуску</b>
