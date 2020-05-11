# Задача проекта

Разработать асинхронное веб приложение.
Backend - на основе модуля aiohttp. REST — API.


# Настройки проекта

### 1)Настройка базы
В проекте используется БД PostgreSQL.

1)Необходимо создать базу данных ,пользователя и пароль(Стандартные настройки лежат в файле database/settings_db.py)<br>
2)Перейдите в директорию database и выполните команду:
```
python create_table.py
```
### 2)Создайте виртуальное окружение
1) Установите завсисмости в виртуальное окружение используя команду
```
pip install -r requerements.txt
```
### 3)Настройка Frontend
1)Перейдите в директорию frontend<br>
2) Установка пакета производится при помощи команды:
```
npm install
```



# Запуск проекта 

 Перейдите в корневую директорию проекта и запустите файл 
 
 ```
python run.py
```


 В директории frontend запустите команду
```
npm start
```

 Перейдите по урлу http://localhost:3000
 
 Используйте кнопки для запуска получения значения и остановки таймера.
 
 Вся информация о работе таймера выводится в клиенте.
 

 

Данные о старте и остановке таймера сохраняются в бд. Также в корне проекта создается файл logs.log. 

# Как работать с WebSocket

### Настройка WebSocket(Ubuntu)
1)Для запуска необходимо скачать следующую программу
https://github.com/vi/websocat/releases <br>
2)Установить пакет в операционную систему. <br>
3)Для проверки работоспособности сокетов используйте<br>
```
websocat ws://0.0.0.0:8080/ws

```

4)Для закрытие вебсокета используйте команду 
 ```
close
```



