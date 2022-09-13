## GIT Homework 1  

Для выполнения задания у вас должен быть установлен для Windows - GitBash.  
Создан аккаунт в GitHub  

Все шаги сценария выполняйте в терминале GitBush, Terminal, в папке под гитом.  

Как отправить ДЗ на проверку.  
 1. Создайте текстоовый файл как в первом ДЗ по Terminal.  
 2. Сценарий перенесите в этот файл.  
 3. На против каждого действия - напишите команду в GitBash  

Файл со сценарием и ссылку на свой гит хаб отправляйте менторам на проверку.  

### JSON  
 4. Создать внешний репозиторий c названием JSON.  
 Training <https://github.com/IKarnika/Training.git>  
 5. Клонировать репозиторий JSON на локальный компьютер.  
 ```git clone https://github.com/IKarnika/Training.git```  
 6. Внутри локального JSON создать файл “new.json”.  
 ```cd Training, touch new.json```  
 7. Добавить файл под гит.  
 ```git add new.json```  
 8. Закоммитить файл.  
 ```git commit new.json -m "Person data"```  
 9. Отправить файл на внешний GitHub репозиторий.  
 ```git push```  
 10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.  
 ```vim new.json```  
  {
	"Name":"Cirilla Fiona Elen Riannon",
	"Age":"16",
	"Pet": "3",
	"Salary":"60 000"

}  

```Esc :wq Enter```  
  
 11. Отправить изменения на внешний репозиторий.  
 ```git commit new.json -m "Update person data"```  
 ```git push```  
 12. Создать файл  
  ```preferences.json```  
  ```vim preferences.json```  
 13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.  
  ```vim preferences.json```  
  {
	"Movie":"The 5th element",
	"TV Show":"Brassic",
	"Food":"KFC",
	"Season":"Spring",
	"Country":"Sweden"
 }  
 
 ```Esc :wq Enter```  
 
 14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON   
 
 ```vim skills.json```  
  
 {
	"Smart"
	"Speed"
	"Streight"
	"Agility"
}  
```Esc :wq Enter```  

 15. Отправить сразу 2 файла на внешний репозиторий.  
 ```git add .```  
 ```git commit .```  
 ```git push```   
 16. На веб интерфейсе создать файл bug_report.json. 
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
 19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 20. Синхронизировать внешний и локальный репозиторий JSON  
 ```git pull```  
 ```git push```


### XML https://github.com/IKarnika/XML.git  
21. Создать внешний репозиторий c названием XML. XML  
 22. Клонировать репозиторий XML на локальный компьютер.  
 ```git clone https://github.com/IKarnika/XML.git```  
 23. Внутри локального XML создать файл “new.xml”.  
 ```touch new.xml```  
 24. Добавить файл под гит.  
 ```git add new.xml```  
 25. Закоммитить файл.  
 ```git commit -m "Bio"```  
 26. Отправить файл на внешний GitHub репозиторий.  
 ```git push```
 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.   
 ```vim new.xml```  
 <xml? version="1.0" encoding="UTF-8">
        <name>Max Frai</name>
        <age>40</age>
        <pet>2</pet>
        <salary>65 000</salary>  
```Esc :wq Enter```  
 
 28. Отправить изменения на внешний репозиторий.  
 ```git add new.xml```  
 ```git commit -m "New update Bio"```  
 ```git push```  
 29. Создать файл preferences.xml  
 ```vim preferences.xml```  
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.   
 <xml? version="1.0" encoding="UTF-8">
		<movie>Deadpool</movie>
		<TVShow>Misfits</TVShow>
		<food>Borsch</food>
		<season>Summer</season>
		<counrty>Finland</country>  
```Esc :wq Enter```  
	
 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML  
 ```vim skills.xml```  
 <xml? version="1.0" encoding="UTF-8">
		<skill1>Agility</skill1>
		<skill2>Smart</skill2>
		<skill3>Speed</skill3>
		<skill4>Magic</skill4>
		<skill5>Mana</skill5>  
```Esc :wq Enter```  

 32. Сделать коммит в одну строку. git add . , git commit -m "New xml files"
 33. Отправить сразу 2 файла на внешний репозиторий. git push
 34. На веб интерфейсе создать файл bug_report.xml.
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 38. Синхронизировать внешний и локальный репозиторий XML git pull
 
 ### TXT https://github.com/IKarnika/TXT.git  
 1. Создать внешний репозиторий c названием TXT.  
 2. Клонировать репозиторий TXT на локальный компьютер.  
 ```git clone https://github.com/IKarnika/TXT.git```  
 3. Внутри локального TXT создать файл “new.txt”.  
 ```touch new.txt```  
 4. Добавить файл под гит.   
 ```git add new.txt```  
 5. Закоммитить файл.  
 ```git commit -m "Added new file"```  
 6. Отправить файл на внешний GitHub репозиторий.  
 ```git push```
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.  
 ```vim new.txt```  
 
 Name Alice
 Age unknown
 Pet not
 Salary endless

Esc :wq Enter
 
 8. Отправить изменения на внешний репозиторий. git commit -m "Update information", git push
 9. Создать файл preferences.txt vim preferences.txt
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
 
 Movie Avengers
TV show Supernatural
Food Cookies
Season Winter
Country Germany

Esc :wq Enter

 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
 
 vim skills.txt
 
 JS
 Git bash
 Postman
 SQL
 Theory
 Python
 
Esc :wq Enter
 
 12. Сделать коммит в одну строку. git add . , git commit -am "Added new files"
 13. Отправить сразу 2 файла на внешний репозиторий. git push
 14. На веб интерфейсе создать файл bug_report.txt.
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 18. Синхронизировать внешний и локальный репозиторий TXT git pull
