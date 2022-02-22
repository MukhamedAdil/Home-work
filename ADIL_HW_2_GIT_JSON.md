   JSON
1.Создать внешний репозиторий c названием JSON.     ===     создать внешний репозиторий на Гитхаб, скопировать ссылку (https://github.com/MukhamedAdil/JSON.git)
2. Клонировать репозиторий JSON на локальный компьютер.   ===   cd D:     mkdir GIT     cd GIT     в терминале ввести команду и вставить ссылку: git clone https://github.com/MukhamedAdil/JSON.git
3. Внутри локального JSON создать файл “new.json”.   ===  cd JSON     touch new.json
4. Добавить файл под гит    ===     git add new.json
5. Закоммитить файл.   ===    git commit -m "inform"
6. Отправить файл на внешний GitHub репозиторий.    ===   git push
7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.  vim new.json
    i 
{
	"surname":"Mukhamet",
	"name":"Adil",
	"age": 30,
	"salary": 1000
}
esc :wq

git commit -am "change new.json"
8. Отправить изменения на внешний репозиторий.   ===    git push
9. Создать файл preferences.json    ===    touch preferences.json
10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
vim preferences.json     i  

{
	"favorite movie":"Troy",
	"favorite series":"Brigada",
	"favorite food":"manti",
	"favorite season":"summer",
	"country":"USA"
}

esc :wq


11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

vim skills.json    i

{
        "hard skills":

        [

        "http",
        "JSON",
        "XML",
        "API Postman",
        "Charles",
        "Fiddler",
        "Devtools",
        "VPN",
        "Mobile testing",
        "IOS",
        "Android",
        "Android studio",
        "ADB",
        "Gitbash",
        "Terminal",
        "SQL",
        "Postgres",
        "Redis",
        "Jmeter",
        "Scrum",
        "Python"

        ]

}

esc :wq



12. Отправить сразу 2 файла на внешний репозиторий.    ===    git add .  ---- git commit -m "2 files"  ----- git push
13. На веб интерфейсе создать файл bug_report.json.    ===    На гитхабе репозиторий JSON - Add file - create new file
14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.   ===    commit new file
15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON. 

открыть bug_report.json
написать:

{
  
"Summary":"test",
"Project":"test",
"Component":"test",
"Version":"test",
"Severity":"test",
"Priority":"test",
"Status":"test",
"Author":"test",
"Assigned To":"test",
"Environment":"test",
"Steps to Reproduce":"test",
"Result":"test",
"Expected Result":"test",
"Attachment":"test"

}

16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.   ===    commit changes
17. Синхронизировать внешний и локальный репозиторий JSON   ===   git fetch   ---   git pull
