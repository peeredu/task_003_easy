# Задание 3. Уровень Easy. Basic network's tools.

Добрый день, коллеги. Сегодня мы продолжаем решать задачи в нашем peer to peer канале Peer Education! Данное задание создано для ребят начинающего уровня.

Правила: первое сообщение в канале.

 <image src="images/servers.jpeg" alt="pascal_triangle" width=600px>

#### Задание

IP-адрес — это уникальный адрес, который идентифицирует устройство в Интернете или локальной сети. IP означает «Интернет-протокол», который представляет собой набор правил, регулирующих формат данных, отправляемых через Интернет или локальную сеть.

> По сути, IP-адреса — это идентификатор, который позволяет передавать информацию между устройствами в сети: они содержат информацию о местоположении и делают устройства доступными для связи. Интернету нужен способ различать разные компьютеры, маршрутизаторы и веб-сайты. IP-адреса предоставляют возможность сделать это и составляют важную часть работы Интернета.

[Подробнее про ip-адреса](https://www.kaspersky.ru/resource-center/definitions/what-is-an-ip-address)

###### Задача 1. Необходимо реализовать программу ip_check.c для валидации ip-адресов. Программа должна принимать на вход ip-адрес, например 127.0.0.1, проверять, может ли существовать такой ip-адрес и выходить результат проверки на экран: VALID - для существующих, INVALID - для несуществующих. Ответ не должен заканчиваться переносом строки или пробелом.

> Проверка ввода не нужна, на вход гарантировано подается строка состоящая из целых чисел и точек.

В одном из значений сеть — это группа устройств под одним управлением, способных коммуницировать между собой. Также сеть означает диапазон IP-адресов — выделенный или полученный от регистратора — для конкретной физической сети. Например, выбранный приватный диапазон 10.0.0.0/8 или полученный от регистратора диапазон внешних адресов 192.0.2.0/24.

Чтобы сети между собой не пересекались, для удобства и разделения доступа, сеть делится на сегменты.

Подсеть, помимо меньшего физического сегмента большой сети, также означает диапазон адресов меньшего размера, созданный путем деления более крупной сети на равные непересекающиеся части. Размер подсети определяется маской подсети.

[Еще немного про адреса и подсети](https://selectel.ru/blog/subnet-mask/)

[И еще немного](https://www.cloud4y.ru/blog/what-is-a-subnet-mask/)

###### Задача 2. Необходимо реализовать программу mask_check.c для определения вхождения ip-адресов в одну подсеть. Маска подсети /24. На вход поочередно подаются два ip-адреса, необходимо определить находятся ли они в одной подсети и вывести на экран ответ: YES - в случае нахождения адресов в одной подсети и NO в обратном случае. Ответ не должен заканчиваться переносом строки или пробелом.

> Проверка ввода не нужна, на вход гарантировано подаются 2 строки состоящие из целых чисел и точек.

###### Задача 3. Бонус. Необходимо соединить два предыдущих задания в одну программу, и добавить проверку на некорректный ввод. При запуске программы нужно выбрать один из пунктов меню: 1 - валидация ip-адреса, 2 - определение вхождения в подсеть. Далее в соответствии с текстами предыдущих заданий. Сборка проекта должна осуществляться с использованием Makefile, стадия сборки ip_tools. Бинарник должен располагаться в папке bin и называться ip_tools. В случае любой ошибки выводить на экран "Puck you, Verter!".

> Внимание. Эта задача повышенного уровня сложности, близкого к основным заданиям. 

#### Материалы которые могут вам помочь лучше узнать компьютерные сети:
- Книга Олифер Виктор, Олифер Наталья Компьютерные сети
- [Авторский бесплатный курс Андрея Созыкина](https://www.asozykin.ru/courses/networks_online)

Дедлайн на эти задания: **Среда 23:59 06.03.2024.**

Увидимся в пятницу!
