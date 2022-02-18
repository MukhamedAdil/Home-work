1) Посмотреть где я    ===     pwd
1) Создать папку     ===    mkdir foldername
1) Зайти в папку     ===    cd foldername
1) Создать 3 папки    ===   mkdir qwerty asdfg zxcv
1) Зайти в любоую папку   ===   cd qwerty
1) Создать 5 файлов (3 txt, 2 json)    ===    touch file1.txt file2.txt file3.txt file4.json file5.json
1) Создать 3 папки   ===    mkdir papka1 papka2 papka3

\8. Вывести список содержимого папки   ===   ls -la

\9) + Открыть любой txt файл   ===   vim file1.txt

\10) + написать туда что-нибудь, любой текст.   ===   i tekst

\11) + сохранить и выйти.   ===   esc:wq

\12) Выйти из папки на уровень выше   ===   cd ..

\13) переместить любые 2 файла, которые вы создали, в любую другую папку.   ===  mv qwerty/file4.json qwerty/file5.json zxcv

\14) скопировать любые 2 файла, которые вы создали, в любую другую папку.   ===   cp zxcv/file4.json zxcv/file5.json asdfg

\15) Найти файл по имени   ===   find -name "file1.txt"

\16) просмотреть содержимое в реальном времени (команда grep) изучите как она работает     ===    tail -f q1.txt

\17) вывести несколько первых строк из текстового файла    ===    head -3 q1.txt

\18) вывести несколько последних строк из текстового файла    ===    tail -3 q1.txt

\19) просмотреть содержимое длинного файла (команда less) изучите как она работает   ===    cat q1.txt | less

\20) вывести дату и время   ===   date


\===========================================


1. отправить http запрос на сервер:

http://162.55.220.72:5005/terminal-hw-request   ===     curl http://162.55.220.72:5005/terminal-hw-request

`						        `ответ: {"Intro":"Hello!! This is your the first response from server","Tasks":{"Task\_1":"Send the next URL in terminal: http://162.55.220.72:5005/get\_method?name=(set\_your\_String)&age=(set\_your\_number)","result":["Your\_String","Your\_number"]}}

1-1 (подзадание из пункта 1):

"Task\_1":"Send the next URL in terminal:

http://162.55.220.72:5005/get\_method?name=(set\_your\_String)&age=(set\_your\_number)","result":["Your\_String","Your\_number"]       ===       curl "http://162.55.220.72:5005/get\_method?name=Adil&age=30"



1. Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13:


#!/bin/bash

cd d:/foldername

mkdir qwerty asdfg zxcv

cd qwerty

touch file1.txt file2.txt file3.txt file4.json file5.json

mkdir papka1 papka2 papka3

ls -la

mv file1.txt file2.txt d:/foldername
