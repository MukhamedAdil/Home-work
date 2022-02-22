   TXT
 4. Создать внешний репозиторий c названием TXT    ===     создать внешний репозиторий на Гитхаб, скопировать ссылку (https://github.com/MukhamedAdil/TXT.git)
 5. Клонировать репозиторий TXT на локальный компьютер.   ===   cd D:      cd GIT     в терминале ввести команду и вставить ссылку: git clone https://github.com/MukhamedAdil/TXT.git
 6. Внутри локального TXT создать файл “new.txt”.   === cd TXT     touch new.txt
 7. Добавить файл под гит    ===     git add new.txt
 8. Закоммитить файл.   ===    git commit -m "TXT"
 9. Отправить файл на внешний GitHub репозиторий.    ===   git push
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.   
   

vim new.txt
    i 
surname:Mukhamet,
name:Adil,
age:30,
salary:1000.
esc :wq

git commit -am "change new.txt"


 11. Отправить изменения на внешний репозиторий.   ===    git push
 12. Создать файл preferences.txt    ===    touch preferences.txt
 13. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.

vim preferences.txt     i  

favorite movie:Troy,
favorite series:Brigada,
favorite food:manti,
favorite season:summer,
country:USA

esc :wq


 14. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT

vim skills.txt    i

hard skills:
http,
JSON,
XML,
API Postman,
Charles,
Fiddler,
Devtools,
VPN,
Mobile testing,
IOS,
Android,
Android studio,
ADB,
Gitbash,
Terminal,
SQL,
Postgres,
Redis,
Jmeter,
Scrum,
Python.

esc :wq



 15. Сделать коммит в одну строку.   ===   git add . ; git commit -m "2 files"
 16 Отправить сразу 2 файла на внешний репозиторий.    ===    git push
 16. На веб интерфейсе создать файл bug_report.txt.    ===    На гитхабе репозиторий TXT - Add file - create new file
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.   ===    commit new file
 18. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT

открыть bug_report.txt
написать:

Summary:test,
Project:test,
Component:test,
Version:test,
Severity:test,
Priority:test,
Status:test,
Author:test,
Assigned To:test,
Environment:test,
Steps to Reproduce:test,
Result:test,
Expected Result:test,
Attachment:test


 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.   ===    commit changes
 20. Синхронизировать внешний и локальный репозиторий TXT   ===   git pull