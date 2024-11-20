Для запуска приложения требуется выполнить следующие действия:
1) Скачать архив с GitHub https://github.com/Ger0n1m0/highload/
2) Распоковать архив в папку
3) Запустить Git bush в папке, в которую разархивируется проект 
4) Выполнить команду docker start
5) Выполнить команду docker compose up

В результате поднимется образ с приложением и базой данных

Приложение поднимется на http://localhost:8080

Для подключения к бд через PGAdmin или DBeaver необходимо указать:
db name: highload_db
host: localhost
port: 9432
user: highload_app
password: 89jxVAwABuNPtLIx1PVoBaX9h

Для корректной работы желательно иметь PostgreSQL не ниже версии 17.0
