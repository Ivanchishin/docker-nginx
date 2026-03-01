# Инструкция по запуску
Скопировать проект на сервер Ubuntu из github

В папке проекта выполнить команду docker build -t netology-nginx .

И команду docker run -d -p 80:80 --name netology-nginx netology-nginx

Проверить работу сервера через команду curl http://localhost:80
