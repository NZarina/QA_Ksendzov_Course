Командны, использованные для создания данного репозитория:

 1. Создать внешний репозиторий c названием JSON.  
Перейти на страницу на https://github.com, нажать на кнопку New repository (Новый репозиторий). На открывшейся странице ввести имя репозитория "JSON" в поле Repository name, нажать на кнопку Create repository.

 2. Клонировать репозиторий JSON на локальный компьютер.  
На локальном компьютере перейти в папку, в которой будет создан локальный репозиторий. Открыть терминал, ввести:  
git clone git@github.com:NZarina/JSON.git

 3. Внутри локального JSON создать файл “new.json”.  
cd JSON (переход в папку JSON)  
touch new.json

 4. Добавить файл под гит.  
git add .  

 5. Закоммитить файл.  
git commit -m 'Add new file'  

 6. Отправить файл на внешний GitHub репозиторий.  
git push

 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.  
```{
"name": "Zarina",
"age": 33,
"pets": "no",
"salary": "1 000 000"
}
```
 8. Отправить изменения на внешний репозиторий.  
git commit -am 'Add personal info'

 9. Создать файл preferences.json  
touch preferences.json

 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.  
```{
"movie": "Pride and Prejudice",
"series": "The Big Bang Theory",
"food": "steak",
"season": "summer",
"countrToVisit": "Greece"
}
```
 11. Создать файл sklls.json добавить информацию о навыках, которые будут изучены на курсе в формате JSON  
cat > skills.json  
```{
    "qaCourses": {
        "course1 ": "Manual QA Engineer. Udemy, online courses", 
        "course2": "Vadim Kzendzov's QA Course",
        "courseSyllabus":        		
		"documentation": "Test cases, checklists, bug reports",
		"tools": "Fiddler, Charles, Postman",
		"webApplications": "HTML, CSS, browser development tools",
		"mobileApplications": "Android, iOS tools",
		"bugTrackingSystem": "Jira, Azure DevOps, YouTrack"
		"programmingLanguage": "Python"
    },    
    "languages": {
        "russian": "native",
        "english": "C1"
    }
}
```
 12. Отправить сразу 2 файла на внешний репозиторий.  
git add . && git commit -m 'Add preferences and skills'

 13. На веб интерфейсе создать файл bug_report.json.  
git push

 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
https://github.com/NZarina/XML -> Add file -> Create new file

 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.  
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
 17. Синхронизировать внешний и локальный репозиторий JSON  
git fetch  
git pull
