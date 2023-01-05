## HW_GitHub_2
1. На локальном репозитории сделать ветки для: - Postman - Jmeter - CheckLists - Bag Reports - SQL - Charles - Mobile testing -

git branch Postman && git branch Jmeter && git branch CheckLists && git branch Bag_Reports && git branch SQL && git branch Charles && git branch Mobile_testing

2. Запушить все ветки на внешний репозиторий - 
    
git push -u origin Postman 

git push -u origin Bag_Reports

git push -u origin Charles

git push -u origin CheckLists

git push -u origin Jmeter

git push -u origin Mobile_testing

git push -u origin SQL

или

    git push -u origin --all

3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта -

git checkout Bag_reports

vim bug_report_structure.txt

    ID
    Environment
    Title
    Precondition
    Steps to reproduce
    Actual result
    Expected result
    Attachments
    Severity
    Priority
    Status
    Tester
4. Запушить структуру багрепорта на внешний репозиторий -

git add .

git commit –m “create and add text to bug_report_structure.txt”

git push

5. Вмержить ветку Bag Reports в Main - 

git checkout main

git merge Bag_reports

6. Запушить main на внешний репозиторий. - git push
7. В ветке CheckLists набросать структуру чек листа.

git checkout CheckLists

vim checklist_structure.txt

    N
    Title
    ER
    Status
8. Запушить структуру на внешний репозиторий –

git add . && git commit -m "create and add text to checklist.txt" && git push

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main - done
10. Синхронизировать Внешнюю и Локальную ветки Main -

git checkout main

git pull
