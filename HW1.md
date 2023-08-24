Первое ДЗ 
Linux terminal (GitBash) commands

1) Посмотреть где я
 ```
 pwd
 ```
 ***
2) Создать папку
```
mkdir folder1
```
 ***
3) Зайти в папку
```
cd folder1
```
 ***
4) Создать 3 папки
```
mkdir folder2 folder3 folder4
```
 ***
5) Зайти в любоую папку
```
cd folder2
```
 ***
6) Создать 5 файлов (3 txt, 2 json)
```
touch file1.txt file2.txt file3.txt file4.json file5.json
```
 ***
7) Создать 3 папки
```
mkdir folder5 folder6 folder7
```
 ***
8) Вывести список содержимого папки
```
ls -la
```
 ***
9) Открыть любой txt файл
10) Написать туда что-нибудь, любой текст.
11) Сохранить и выйти.
```
nano file1.txt
hello bash!
ctrl+X
Y
Enter
```
 ***
12) Выйти из папки на уровень выше
```
cd ..
```
 ***
13) переместить любые 2 файла, которые вы создали, в любую другую папку.
```
mv file1.txt file2.txt folder5
```
 ***
14) скопировать любые 2 файла, которые вы создали, в любую другую папку.
```
cp file3.txt file4.json folder6
```
 ***
15) Найти файл по имени
```
find folder1 -name file1.txt
```
 ***
16) просмотреть содержимое в реальном времени (команда grep) изучите как она работает.
```
cat file3.txt | grep hello
```
 ***
17) вывести несколько первых строк из текстового файла
```
head file3.txt -n 2
```
 ***
18) вывести несколько последних строк из текстового файла
```
tail file3.txt -n 2
```
 ***
19) просмотреть содержимое длинного файла (команда less) изучите как она работает.
```
less file3.txt
```
 ***
20) вывести дату и время
```
date
```
 ***
=========
Задание *
1) Отправить http запрос на сервер.
http://162.55.220.72:5005/terminal-hw-request
```
curl http://162.55.220.72:5005/terminal-hw-request
```
 ***
2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13
```
#!/bin/bash
cd folder7
mkdir folder8 folder9 folder10
touch file6.txt file7.txt file8.txt file9.json file10.json
mkdir folder11 folder12 folder13
ls -la
```
 ***
