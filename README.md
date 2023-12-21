

CICD - Симбирцев Андрей




Задание 1
Что нужно сделать:

Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
Установите на машину с jenkins golang.
Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.
Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

Решение1 


![alt text](https://github.com/simbirtsevav/zabbix8.03/blob/main/img/1.png)

![alt text](https://github.com/simbirtsevav/zabbix8.03/blob/main/img/2.png)

![alt text](https://github.com/simbirtsevav/zabbix8.03/blob/main/img/3.png)

Задание 2
Что нужно сделать:

Создайте новый проект pipeline.
Перепишите сборку из задания 1 на declarative в виде кода.
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.


Решение 2

![alt text](https://github.com/simbirtsevav/zabbix8.03/blob/main/img/4.png)
![alt text](https://github.com/simbirtsevav/zabbix8.03/blob/main/img/5.png)

Задание 3
Что нужно сделать:

Установите на машину Nexus.
Создайте raw-hosted репозиторий.
Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
Загрузите файл в репозиторий с помощью jenkins.
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки


Решение 4
![alt text](https://github.com/simbirtsevav/zabbix8.03/blob/main/img/6.png)
![alt text](https://github.com/simbirtsevav/zabbix8.03/blob/main/img/7.png)
![alt text](https://github.com/simbirtsevav/zabbix8.03/blob/main/img/8.png)