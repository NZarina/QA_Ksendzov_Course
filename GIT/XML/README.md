Командны, использованные для создания данного репозитория:

XML
 1. Создать внешний репозиторий c названием XML.  
Перейти на страницу на https://github.com, нажать на кнопку New repository (Новый репозиторий). На открывшейся странице ввести имя репозитория "XML" в поле Repository name, нажать на кнопку Create repository.

 2. Клонировать репозиторий XML на локальный компьютер.  
На локальном компьютере перейти в папку, в которой будет создан локальный репозиторий. Открыть терминал, ввести:  
git@github.com:NZarina/XML.git

 3. Внутри локального XML создать файл “new.xml”.  
cd XML (переход в папку XML)  
touch new.xml

 4. Добавить файл под гит.  
git add .

 5. Закоммитить файл.  
git commit -m 'Add new file'

 6. Отправить файл на внешний GitHub репозиторий.  
git push

 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.  
cat > new.txt  
```<?xml version="1.0"?>  

<Info>  
	<name>  
		<first>Zarina</first>  
		<last>Niyazova</last>  
	</name>  
	<age>33</age>  
	<pets>no</pets>  
	<desiredSalary>1 000 000</desiredSalary>  
</Info>
```

 8. Отправить изменения на внешний репозиторий.  
git commit -am 'Add personal info'

 9. Создать файл preferences.xml  
touch preferences.xml

 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.  
```<?xml version="1.0"?>

<Info>
	<film>Favourite film: Pride and Prejudice.</film>
	<TVSeries>Favourite TV series: The Big Bang Theory.</TVSeries>
	<food>Favourite food: Plov</food>
	<season>Favourite season: Summer.</season>
	<food>Countries I want to visit: "Austria, Greece, Indonesia.</food>
	<countries>Desired salary: a lot of money.</countries>
</Info>
```

 11. Создать файл sklls.xml добавить информацию о навыках, которые будут изучены на курсе в формате XML  
cat > skills.xml  
```<?xml version="1.0"?>

<Info>
	<QACourses>
		<Course1>Manual QA Engineer. Udemy, online courses.</Course1>
		<Course2>Vadim Kzendzov's QA Course.</Course2>
	</QACourses>
	<Syllabus>
		<teory></teory>
		<documentation>Test cases, checklists, bug reports</documentation>
		<tools>Fiddler, Charles, Postman</tools>
		<webApplications>HTML, CSS, browser development tools</webApplications>
		<mobileApplications>Android, iOS tools</mobileApplications
		<bugTrackingSystem>Jira, Azure DevOps, YouTrack</bugTrackingSystem>
		<programmingLanguage>Python</programmingLanguage>		
	</Syllabus>
	<languages>Russian (native), English (C1).</languages>
</Info> 
```

 12. Сделать коммит в одну строку.  
git add . && git commit -m 'Add preferences and skills'

 13. Отправить сразу  файла на внешний репозиторий.  
git push

 14. На веб интерфейсе создать файл bug_report.xml.  
https://github.com/NZarina/XML -> Add file -> Create new file

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.  
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  

 18. Синхронизировать внешний и локальный репозиторий XML  
git fetch  
git pull
