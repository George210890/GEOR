# Домашнее задание к занятию **Что такое DevOps. СI/СD - Логинов Даниил**

### Задание 1

1. Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
2. Установите на машину с jenkins golang.
3. Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.
4. Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..

### Ответ 1 

![Скрин 1](https://github.com/GEOR/cicd-8.02.hw/blob/main/img/J1s1.jpg)
![Скрин 2](https://github.com/GEOR/cicd-8.02.hw/blob/main/img/J1s2.jpg)
![Скрин 3](https://github.com/GEOR/cicd-8.02.hw/blob/main/img/J1s3.jpg)
![Скрин 4](https://github.com/GEOR/cicd-8.02.hw/blob/main/img/J1s4.jpg)
![Скрин 5](https://github.com/GEOR/cicd-8.02.hw/blob/main/img/J1s5.jpg)
![Скрин 6](https://github.com/GEOR/cicd-8.02.hw/blob/main/img/J1s6.jpg)

-------

### Задание 2


1. Создайте новый проект pipeline.
2. Перепишите сборку из задания 1 на declarative в виде кода.

### Ответ 2 

![Скрин 1](https://github.com/GEOR/cicd-8.02.hw/blob/main/img/J2s1.jpg)
![Скрин 2](https://github.com/GEOR/cicd-8.02.hw/blob/main/img/J2s2.jpg)
![Скрин 3](https://github.com/GEOR/cicd-8.02.hw/blob/main/img/J2s3.jpg)
![Скрин 4](https://github.com/GEOR/cicd-8.02.hw/blob/main/img/J2s4.jpg)

------

### Задание 3 и Задание 4

1. Установите на машину Nexus.
2. Создайте raw-hosted репозиторий.
3. Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
4. Загрузите файл в репозиторий с помощью jenkins.
5*. Придумайте способ версионировать приложение, чтобы каждый следующий запуск сборки присваивал имени файла новую версию. Таким образом, в репозитории Nexus будет храниться история релизов.


### Ответе 3 и 4 

![Скрин 1](https://github.com/GEOR/cicd-8.02.hw/blob/main/img/J3s1.jpg)
![Скрин 2](https://github.com/GEOR/cicd-8.02.hw/blob/main/img/J3s2.jpg)
![Скрин 3](https://github.com/GEOR/cicd-8.02.hw/blob/main/img/J3s3.jpg)
![Скрин 4](https://github.com/GEOR/cicd-8.02.hw/blob/main/img/J3s4.jpg)
![Скрин 5](https://github.com/GEOR/cicd-8.02.hw/blob/main/img/J4s1.jpg)
![Скрин 6](https://github.com/GEOR/cicd-8.02.hw/blob/main/img/J4s2.jpg)
![Скрин 7](https://github.com/GEOR/cicd-8.02.hw/blob/main/img/J4s3.jpg)
