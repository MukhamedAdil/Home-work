GitHub. HW_2
1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag_Reports
- SQL
- Charles
- Mobile testing
================
создать внешний репозиторий HW_2_GIT  
В Gitbash клонировать созданный репозиторий: git clone https://github.com/MukhamedAdil/HW_2_GIT.git
git branch Postman
git branch Jmeter
git branch CheckLists
git branch Bag_Reports
git branch SQL
git branch Charles
git branch Mobile testing

2. Запушить все ветки на внешний репозиторий   ===   git push --all
3. В ветке Bag_Reports сделать текстовый документ со структурой баг репорта 
==================  
 git checkout Bag_Reports 
 vim bug_report.txt     i

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

esc :wq

4. Запушить структуру багрепорта на внешний репозиторий   
======================  
git add . ; git commit -m "structure of bug_report"        git push -u origin Bag_Reports
   
5. Вмержить ветку Bag_Reports в Main   ===    git checkout main  ----------- git merge Bag_Reports
6. Запушить main на внешний репозиторий.   ===    git push
7. В ветке CheckLists набросать структуру чек листа.   

git branch CheckLists 

vim checklist.txt     i

number:test
check:test
priority:test
test_data:test
result:test
comments:test

esc :wq


8. Запушить структуру на внешний репозиторий  
 =================
 git add . ; git commit -m "structure of checklist"         git push -u origin CheckLists


9. На внешнем репозитории сделать Pull Request ветки CheckLists в main   
==================================================   
на Гитхабе на ветке "main" нажать кнопки: "Compare & pull request" ---   Create pull request   ---    Merge pull request   ---    confirm merge

10. Синхронизировать Внешнюю и Локальную ветки Main    ===   git branch main   ----    git pull