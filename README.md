1. Создать внешний репозиторий c названием JSON

    а) Зайти в главное меню GitHub
    
    b) Нажать Create a new repository
    
    c) Ввести в Repository name "JSON"
    
    d) Выбрать Public
    
    e) Выбрать Add a readme file
    
    f) Нажать Create repository.
    
2. Клонировать репозиторий JSON на локальный компьютер
 
    $ mkdir JSON0
    
    $ cd JSON0
    
    $ git clone https://github.com/AliyaKahiya/JSON.git
    
3. Внутри локального JSON создать файл “new.json”

    $ cd JSON
    
    $ touch new.json
    
4. Добавить файл под гит

    $ git add new.json
    
5. Закоммитить файл

    $ git commit -m "Add new json file"
    
6. Отправить файл на внешний GitHub репозиторий.

    $ git push
    
7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.

    $ vim new.json
    
    i
    
    {
    
	   "name" : "Kahiya_Aliya_Timergalievna",
     
	   "age" : 29,
     
	   "pets" : 0,
     
	   "salary" : 80000
     
    }
    
    Esq
    
    :wq
8. Отправить изменения на внешний репозиторий.

    $ git add new.json && git commit -m "Add information about name age pets salary" && git push
    
9. Создать файл preferences.json

    $ touch preferences.json
    
10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

    $ vim preferences.json
    
    {
    
	   "favourite_film" : "not",
     
	   "favourite_TV_series" : "no",
     
	   "favourite_food" : "salad",
     
	   "favourite_seazon" : "summer",
     
	   "country" : "Australia"
     
    }
    
    Esq
    
    :wq
    
11.  Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

    $ vim skills.json
    
    {
    
	   "skill_1" : "Terminal",
     
	   "skill_2" : "GitBash",
     
	   "skill_3" : "GitHub",
     
	   "skill_4" : "Postman",
     
	   "skill_5" : "API"
     
    }
    
    Esq
    
    :wq
    
12. Отправить сразу 2 файла на внешний репозиторий.
 
    $ git add preferences.json skills.json && git commit -m "Add new preferences json and skills json files" && git push
    
13. На веб интерфейсе создать файл bug_report.json.

     a) Нажать add file
     
     b) Нажать create new file
     
     c) В бутон name your file написать bug_report.json
     
     d) Нажать Commit new file
     
14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

     a) Нажать на наименование необходимого файла
     
     b) Нажать Edit this file
     
     c) Внести изменения в поле Edit file
     
     d) Написать комментарий в нижнем бутоне 
     
     e) Нажать Commit changes
     
15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.

     a) Нажать на bug_report.json
     
     b) Нажать Edit this file 
     
     c) Ввести в поле Edit file 
     
       {
       
 		      "Summary" : "...",
          
  		    "Description" : "...", 
          
  		    "Actual_result" : "...",
          
  		    "Expected_result" : "...", 
          
  		    "Attachments" : "...", 
          
  		    "Priority" : "...", 
          
  		    "Severity" : "...",
          
  		    "Status" : "..."
          
	 }
   
     d) Нажать Commit changes
     
16. Сделать Commit changes (сохранить) изменения на веб интерфейсе
 
     a) Нажать на наименование необходимого файла
     
     b) Нажать Edit this file
     
     c) Внести изменения в поле Edit file
     
     d) Написать комментарий в нижнем бутоне 
     
     e) Нажать Commit changes
     
17. Синхронизировать внешний и локальный репозиторий JSON
 
     $ git pull
