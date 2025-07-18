# Домашнее задание к занятию "`Кластеризация и балансировка нагрузки`" - `Лычагин Н.В.`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1

1) Запустите два simple python сервера на своей виртуальной машине на разных портах
2) Установите и настройте HAProxy, воспользуйтесь материалами к лекции по ссылке
3) Настройте балансировку Round-robin на 4 уровне.
4) На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy.


![alt text](https://github.com/Nikich828/10_2hw/blob/master/1.jpeg)
![alt text](https://github.com/Nikich828/10_2hw/blob/master/2.jpeg)
![alt text](https://github.com/Nikich828/10_2hw/blob/master/3.jpeg)
![alt text](https://github.com/Nikich828/10_2hw/blob/master/4.jpeg)
![alt text](https://github.com/Nikich828/10_2hw/blob/master/5.jpeg)
![alt text](https://github.com/Nikich828/10_2hw/blob/master/6.jpeg)
![alt text](https://github.com/Nikich828/10_2hw/blob/master/7.jpeg)
![alt text](https://github.com/Nikich828/10_2hw/blob/master/8.jpeg)
![alt text](https://github.com/Nikich828/10_2hw/blob/master/9.jpeg)

### Задание 2


1) Запустите три simple python сервера на своей виртуальной машине на разных портах
2) Настройте балансировку Weighted Round Robin на 7 уровне, чтобы первый сервер имел вес 2, второй - 3, а третий - 4
3) HAproxy должен балансировать только тот http-трафик, который адресован домену example.local
4) На проверку направьте конфигурационный файл haproxy, скриншоты, где видно перенаправление запросов на разные серверы при обращении к HAProxy c использованием домена example.local и без него.


![alt text](https://github.com/Nikich828/10_2hw/blob/master/10.jpeg)
![alt text](https://github.com/Nikich828/10_2hw/blob/master/11.jpeg)
![alt text](https://github.com/Nikich828/10_2hw/blob/master/12.jpeg)
![alt text](https://github.com/Nikich828/10_2hw/blob/master/13.jpeg)
![alt text](https://github.com/Nikich828/10_2hw/blob/master/14.jpeg)
![alt text](https://github.com/Nikich828/10_2hw/blob/master/15.jpeg)
