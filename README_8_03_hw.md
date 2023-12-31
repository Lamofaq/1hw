# Домашнее задание к занятию "Что такое DevOps. СI/СD" - Yana Ulanovskaya

### Задание 1

Задание 1
Что нужно сделать:

Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.
Установите на машину с jenkins golang.
Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.
Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

Скриншоты для первого задания:
![screenshots process 1-15](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/1.PNG)
![screenshots process 1-15](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/2.PNG)
![screenshots process 1-15](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/3.PNG)
![screenshots process 1-15](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/4.PNG)
![screenshots process 1-15](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/5.PNG)
![screenshots process 1-15](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/6.PNG)
![screenshots process 1-15](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/7.PNG)
![screenshots process 1-15](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/8.PNG)
![screenshots process 1-15](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/9.PNG)
![screenshots process 1-15](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/10.PNG)
![screenshots process 1-15](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/11.PNG)
![screenshots process 1-15](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/12.PNG)
![screenshots process 1-15](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/13.PNG)
![screenshots process 1-15](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/14.PNG)
![screenshots process 1-15](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/15.PNG)

![screenshots result 16-20](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/16.PNG)
![screenshots result 16-20](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/17.PNG)
![screenshots result 16-20](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/18.PNG)
![screenshots result 16-20](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/19.PNG)
![screenshots result 16-20](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/20.PNG)

---

### Задание 2

Что нужно сделать:

Создайте новый проект pipeline.
Перепишите сборку из задания 1 на declarative в виде кода.
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.



Скриншоты для второго задания: 

![screenshots result 2.1 - 2.4](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/2.1.PNG)
![screenshots result 2.1 - 2.4](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/2.2.PNG)
![screenshots result 2.1 - 2.4](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/2.3.PNG)
![screenshots result 2.1 - 2.4](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/2.4.PNG)

При выполнении второго задания был добавлен код в pipeline. При выполнении кода возникает ошибка при проверке наличия языка go. Скриншот из терминала машины показывает, что данный пакет установлен. 
---

### Задание 3

Что нужно сделать:

Установите на машину Nexus.
Создайте raw-hosted репозиторий.
Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.
Загрузите файл в репозиторий с помощью jenkins.
В качестве ответа пришлите скриншоты с настройками проекта и результатами выполнения сборки.

Скриншоты для третьего задания: 

![screenshots result 3.1 -3.4](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/3.1.PNG)
![screenshots result 3.1 -3.4](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/3.2.PNG)
![screenshots result 3.1 -3.4](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/3.3.PNG)
![screenshots result 3.1 -3.4](https://github.com/Lamofaq/YANA_U-gitlab-hw/blob/main/img/3.4.PNG)

При выполнении третьего задания возникли вопросы по изменению pipeline. Правильно ли выглядит команда. Также возникает ошибка при попытке выполнения sh 'go test .'

....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`

---
## Дополнительные задания (со звездочкой*)

Эти задания дополнительные (не обязательные к выполнению) и никак не повлияют на получение вами зачета по этому домашнему заданию. Вы можете их выполнить, если хотите глубже и/или шире разобраться в материале.

### Задание 5

`Приведите ответ в свободной форме........`

1. `Заполните здесь этапы выполнения, если требуется ....`
2. `Заполните здесь этапы выполнения, если требуется ....`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`
