JSON

4. Создать внешний репозиторий c названием JSON. +
***
5. Клонировать репозиторий JSON на локальный компьютер. 

clone https://github.com/WINDNOISE0/JSON.git
***
6. Внутри локального JSON создать файл “new.json”. 

touch JSON/new.json
***
7. Добавить файл под гит. 

cd JSON 
 
git init 

git add .
***
8. Закоммитить файл. 

git commit -m "One"
***
9. Отправить файл на внешний GitHub репозиторий.

git remote add origin https://github.com/WINDNOISE0/JSON.git

git branch -M main

git push -u origin main    

10. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.

#cat >> new.json

```
{
        "name":"Yaroslav",
        "sername":"Yaroslavov",
        "patronymic":"Yaroslavich",
        "age":25,
        "count home pets": 1,
        "future expected salary":"1000$+"
}
```
***
11. Отправить изменения на внешний репозиторий. 

git push -u origin main
***
12. Создать файл preferences.json 

cat > preferences.json
***
13. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
# nano preferences.json
```
{
  "favorite movie":"fear and loathing in las vegas",
  "favorite TV-show":"none",
  "favorite food":"delicious",
  "favorite season":"summer",
  "country which I want visit":"Spain"
}
```
***
14. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

# nano sklls.json
```
{
  "will studys skills":["Bash terminal", "Git system of control version", "SQL", "Postman", "Jmeter", "AndroidStudio", "Charles", "DB Browser", "Fiddler"]
}
```
***
15. Отправить сразу 2 файла на внешний репозиторий. 

git push -u origin main
***
16. На веб интерфейсе создать файл bug_report.json. +
***
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. +
***
18. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON. 
```
{
  "number ID":1,
  "Title":"Link 'create new account' Global Menu isn't open when clicking",
  "Seveity":"critical",
  "Priority":"hight",
  "STR":{
    "1":"Open link",
    "2":"Tap to button 'create new account'"
  },
  "Expected Result":"Registration's window is opened",
  "Actual Result":"nothing happens, link isn't opened"
}
```
***
19. Сделать Commit changes (сохранить) изменения на веб интерфейсе.+
***
20. Синхронизировать внешний и локальный репозиторий JSON 

git pull
***
