   XML
21. Создать внешний репозиторий c названием XML.     ===     создать внешний репозиторий на Гитхаб, скопировать ссылку (https://github.com/MukhamedAdil/XML.git)
22. Клонировать репозиторий XML на локальный компьютер.   ===   cd D:     cd GIT   в терминале ввести команду и вставить ссылку: git clone https://github.com/MukhamedAdil/XML.git
23 Внутри локального XML создать файл “new.xml”.   === cd XML     touch new.xml
24 Добавить файл под гит    ===     git add new.xml
25. Закоммитить файл.   ===    git commit -m "xml"
26. Отправить файл на внешний GitHub репозиторий.    ===   git push
27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.   
   

vim new.xml
    i 
<?xml version="1.0" encoding="UTF-8"?>
	<inform>
		<surname>Mukhamet</surname>
		<name>Adil</name>
		<age>30</age>
		<salary>1000</salary>
	</inform>
esc :wq

git commit -am "change xml"


28. Отправить изменения на внешний репозиторий.   ===    git push
29. Создать файл preferences.json    ===    touch preferences.json
30. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

vim preferences.xml     i  

<?xml version="1.0" encoding="UTF-8"?>
        <preferences>
                <favorite_movie>Troy</favorite_movie>
                <favorite_series>Brigada</favorite_series>
                <favorite_food>manti</favorite_food>
                <favorite_season>summer</favorite_season>
                <country>USA</country>
        </preferences>


esc :wq


31. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML

vim skills.xml    i

<?xml version="1.0" encoding="UTF-8"?>
	<hard_skills>

		<skill_1>http</skill_1>
		<skill_2>JSON</skill_2>
		<skill_3>XML</skill_3>
		<skill_4>API_Postman</skill_4>
		<skill_5>Charles</skill_5>
		<skill_6>Fiddler</skill_6>
		<skill_7>Devtools</skill_7>
		<skill_8>VPN</skill_8>
		<skill_9>Mobile_testing</skill_9>
		<skill_10>IOS</skill_10>
		<skill_11>Android</skill_11>
		<skill_12>Android_studio</skill_12>
		<skill_13>SQL</skill_13>
		<skill_14>Redis</skill_14>
		<skill_15>GItbash</skill_15>

	</hard_skills>

esc :wq


32. Сделать коммит в одну строку   ===   git add . ; git commit -m "2 files"
33. Отправить сразу 2 файла на внешний репозиторий.    ===    git push
34. На веб интерфейсе создать файл bug_report.xml.    ===    На гитхабе репозиторий XML - Add file - create new file - ввести название bug_report.xml
35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.   ===    commit new file
36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.

открыть bug_report.xml
написать:

<?xml version="1.0" encoding="UTF-8">
  <bug_report>
        <summary>test</summary>
        <project>test</project>
        <component>test</component>
        <version>test</version>
        <severity>test</severity>
        <priority>test</priority>
        <status>test</status>
        <author>test</author>
        <assigned_To>test</assigned_To>
        <environment>test</environment>
        <steps_to_Reproduce>test</steps_to_Reproduce>
        <result>test</result>
        <expected_Result>test</expected_Result>
        <attachment>test</attachment>
  </bug_report>



37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.   ===    commit changes
38. Синхронизировать внешний и локальный репозиторий XML    ===     git pull