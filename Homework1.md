# Terminal Homework #1

1) Посмотреть локацию пользователя 
`pwd`

2) Создать папку
`mkdir folder`

3) Зайти в папку `сd folder`

4) Создать 3 папки : `mkdir folder1 folder2 folder3`

5) Зайти в любую папку : `cd folder1`

6) Создать 5 файлов (3 txt, 2 json) : `touch name1.txt name2.txt name3.txt file1.json file2.json`

7) Создать 3 папки : `mkdir data1 data2 data3`

8. Вывести список содержимого папки : `ls -la`


9) Открыть любой txt файл : `cat name1.txt touch name1.txt`

10) Написать туда что-нибудь, любой текст. 

`cat >> name1.txt
Hello world!`


11) Сохранить и выйти. : `ctrl + c`

12) Выйти из папки на уровень выше : `cd ..`

13) Переместить любые 2 файла, которые вы создали, в любую другую папку:


`mv folder1/name1.txt folder2/name1.txt`

`mv folder1/name2.txt folder2/name2.txt`

11) Cохранить и выйти. : `ctrl + c`

12) Выйти из папки на уровень выше : `cd ..`

13) переместить любые 2 файла, которые вы создали, в любую другую папку.:

`mv folder1/name1.txt folder2/name1.txt`

`mv folder1/name2.txt folder2/name2.txt`


15) скопировать любые 2 файла, которые вы создали, в любую другую папку. :

`cp folder1/file1.json folder3/file1.json`

`cp folder1/file2.json folder3/file2.json`

17) Найти файл по имени: `find . -name file2.json `

18) Просмотреть содержимое в реальном времени (команда grep) : 
[Команда grep предназначена для поиска строк, соответствующих заданному шаблону.]
`grep Teddy name3.txt`

19) Вывести несколько первых строк из текстового файла : `head -5 name3.txt` (Выводит нам 5 первых строк на экран)

20) Вывести несколько последних строк из текстового файла `tail -5 name3.txt` (выводит нам 5 последних строк на экран)

21) Просмотреть содержимое длинного файла (команда less) :
`less name3.txt`
Для выхода используем wq

22) вывести дату и время : `date`

*
1) Отправить https запрос на сервер http://162.55.220.72:5006/terminal-hw-request : 

`cURL "http://162.55.220.72:5005/get_method?name=Vladimir&age=20"`

2) Написать скрипт, который автоматически выполнит 3,4,5,6,7,8,13 пункты:

[script](https://github.com/pyatkov-vladimir/Terminal/blob/main/HW1_Terminal_script.sh)

Запустить скрипт 

`#!/bin/bash`
