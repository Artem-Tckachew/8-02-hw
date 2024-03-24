# "Что такое DevOps. СI/СD" - Ткачев Артём
---
## Задание 1
Что нужно сделать:

1. Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.

2. Установите на машину с jenkins golang.

3. Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.

4. Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..

Ответ:
![alt text](https://github.com/Artem-Tckachew/8-02-hw/blob/main/1.png)
![alt text](https://github.com/Artem-Tckachew/8-02-hw/blob/main/2.png)
![alt text](https://github.com/Artem-Tckachew/8-02-hw/blob/main/3.png)

---
## Задание 2
1.Создайте новый проект pipeline.
2. Перепишите сборку из задания 1 на declarative в виде кода.
Ответ:
![alt text](https://github.com/Artem-Tckachew/8-02-hw/blob/main/4.png)
![alt text](https://github.com/Artem-Tckachew/8-02-hw/blob/main/5.png)
---
## Задание 3
1.Установите на машину Nexus.
2.Создайте raw-hosted репозиторий.
3.Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
4.Загрузите файл в репозиторий с помощью jenkins.
Ответ:
![alt text](https://github.com/Artem-Tckachew/8-02-hw/blob/main/6.png)
![alt text](https://github.com/Artem-Tckachew/8-02-hw/blob/main/7.png)
![alt text](https://github.com/Artem-Tckachew/8-02-hw/blob/main/8.png)
![alt text](https://github.com/Artem-Tckachew/8-02-hw/blob/main/9.png)