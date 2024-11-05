# Домашнее задание к занятию "`Git`" - `Ощепков Дмитрий`


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

`Переходим в репозиторий с шаблоном решения и активируем функцию fork. Что позволяет использовать чужой репозиторий в своих целях, не затрагивая оригинал.`

1. `Git clone https://github.com/OshchepkovDP/netology_test_repository-8.01-hw`
2. `git config --global user.name "OshchepkovDP"`
3. `git config --global user.email kajitsydmitry@gmail.com`
4. `git status`
5. `sudo nano README.md` `заполняем шаблон
6. `git status`
7. `git diff`
8. `git diff --staged`
9. `git add README.md`
10. `git diff`
11. `git diff --staged`
12. `git commit -m 'First commit'`
13. `git push origin master` `### что приводит нас к ошибке, так как ветки master не существует`
14. `git branch` `получаем вывод, что мы находимся в ветке main
15. `git push origin main` `### коммит добавлен`

```
Поле для вставки кода...
....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Добавление изменений в репозиторий задание 1](https://private-user-images.githubusercontent.com/186410638/382998753-902fc76c-bf4b-4215-bf28-d8c425da1e41.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzA3Nzg1ODAsIm5iZiI6MTczMDc3ODI4MCwicGF0aCI6Ii8xODY0MTA2MzgvMzgyOTk4NzUzLTkwMmZjNzZjLWJmNGItNDIxNS1iZjI4LWQ4YzQyNWRhMWU0MS5qcGc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTA1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEwNVQwMzQ0NDBaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0zMzc3OGM1Yzc5MWNkMjFjN2U1ZjVkNzU1MTEyZjJhMTc1OTQzZTkyZmJjYWNlNGJiOTk0ZjhlNDQ0MzAzZTY3JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.U_6ItqMmGCY3-lAMUPvpR80swRdTqYU4UzxeZ3gG0eQ)`


---

### Задание 2

`Создаём файл для установки правил игнорирования определённых файлов и кталогов при выполнении команд git add и git status`

1. `sudo nano .gitignore`
2. `git status`
3. `git add .gitignore`
4. `прописываем правила внутри файла`
5. `git commit -m 'Added .gitignore rules'`
6. `git push origin`

```
Поле для вставки кода...
....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![создание gitignore задание 2](https://private-user-images.githubusercontent.com/186410638/382995767-f7c3eb4c-5943-416f-bb48-adebcefa356e.jpg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzA3Nzc1NzQsIm5iZiI6MTczMDc3NzI3NCwicGF0aCI6Ii8xODY0MTA2MzgvMzgyOTk1NzY3LWY3YzNlYjRjLTU5NDMtNDE2Zi1iYjQ4LWFkZWJjZWZhMzU2ZS5qcGc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTA1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEwNVQwMzI3NTRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT01ODI2ZmYyMjFkZDA0M2RkODQ0YmExOTIyMDIzMWJhMTVkMDVmMTM0MmRmODc5MmM4NWMwMGM2MTRhNjIwZDI5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.OnkSMosqyk_0DcA4_qa7oMLUJeoUcKHVySaptXoeIX4)`


---

### Задание 3

`Создаём новую ветку с последующим слиянием с основной` `https://github.com/OshchepkovDP/netology_test_repository-8.01-hw/network`

1. `git checkout -b dev`
2. `sudo nano test.sh`
3. `git add test.sh`
4. `git commit -m 'Added test.sh file'`
5. `git push origin dev`
6. `git checkout main`
7. `sudo nano main.sh`
8. `git add main.sh`
9. `git commit -m 'Added main.sh file'`
10. `git push origin main`
11. `git merge dev`
12. `git commit -m 'Merged dev branch into main'`
13. `git push origin main`

```
Поле для вставки кода...
....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`

### Задание 4

`Приведите ответ в свободной форме........`

1. `Заполните здесь этапы выполнения, если требуется ....`
2. `Заполните здесь этапы выполнения, если требуется ....`
3. `Заполните здесь этапы выполнения, если требуется ....`
4. `Заполните здесь этапы выполнения, если требуется ....`
5. `Заполните здесь этапы выполнения, если требуется ....`
6. 

```
Поле для вставки кода...
....
....
....
....
```

`При необходимости прикрепитe сюда скриншоты
![Название скриншота](ссылка на скриншот)`
