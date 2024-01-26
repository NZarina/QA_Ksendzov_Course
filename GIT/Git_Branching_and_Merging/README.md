GitHub. HW_2

Команды, использованные для данного репозитория:

1. На локальном репозитории сделать ветки для:
- Postman: git branch Postman
- Jmeter: git branch Jmeter
- CheckLists: git branch CheckLists
- Bug Reports: git branch Bug_Reports
- SQL: git branch SQL
- Charles: git branch Charles
- Mobile Testing: git branch Mobile_testing

2. Запушить все ветки на внешний репозиторий:
- git push --all

4. В ветке Bug Reports сделать текстовый документ со структурой баг репорта:
- git checkout Bug_Reports
- vim bug_report_structure.txt
- нажать i, ввести текст.
- нажать ESC :wq Enter

4. Запушить структуру багрепорта на внешний репозиторий:
- git add bug_report_structure.txt
- git commit -m 'Add_bug_report_structure'
- git push --set-upstream origin Bug_Reports

5. Вмержить ветку Bug Reports в Main:
- git checkout main
- git merge Bug_Reports

6. Запушить Main на внешний репозиторий:
- git push --set-upstream origin main

7. В ветке CheckLists набросать структуру чек-листа:
- git checkout CheckLists 
- vim checklist_structure.txt
- нажать i, ввести текст
- нажать ESC :wq Enter

8. Запушить структуру на внешний репозиторий:
- git add checklist_structure.txt
- git commit -m 'Add_checklist_structure'
- git push --set-upstream origin CheckLists

9. На внешнем репозитории сделать Pull Request ветки CheckLists в Main:
- Compare & pull request -> Create pull request -> Merge pull request -> Confirm merge

10. Синхронизировать внешнюю и локальную ветки Main:
- git checkout main
- git pull
