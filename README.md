# XML
 ### __1. Создать внешний репозиторий с названием XML.__ 
 - *Открыть* [GitHub](https://github.com/new "Создание нового репозитория")  
 - *В поле __Repository name__ ввести __XML__*.
 - *В чекбоксе __Public__ выбрать*:
    - [x] __Public__
    - [ ] Private
 -  *Выбрать __Add a README file__.*
 -  *Нажать __Create repository__*.
  ### __2. Клонировать репозиторий XML на локальный компьютер.__ 
 - *В репозитории __XML__ нажать на  __Code__ затем в разделе __HTPPS__ скопировать ссылку.*
 - *В __Gitbash__ написать команду и вставить ссылку (для Windows, вставить Shift+Insert)*
 - *`git clone https://github.com/Marlen7A/XML.git`*
### __3. Внутри локального XML создать файл "new.xml".__ 
- *`touch new.xml`*
- *`git status` файл __new.xml__ отображается красным, изменения в файле не отслеживаются*.
### __4. Добавить файл под гит.__ 
- *`git add new.xml`*
### __5. Закомитить файл.__ 
- *`git commit -m "add new.xml"`*
### __6. Отправить файл на внешний GitHub репозиторий.__ 
- *`git push`*
### __7. Отредактировать содержание файла "new.xml"-написать информацию о себе (ФИО,возраст, количество домашних животных, будущая желаемая зарплата). Все написать в формате XML.__ 
- *`vim new.xml`*
- *Insert*
 ```
<?xml version="1.0"?>
<person>
  <fullname>Marlen Abliakimov</fullname>
  <age>34</age>
  <pets>
  <dog>1</dog>
  </pets>
  <desiredSalary>5000$</desiredSalary>
</person>
 ```
 - *Нажать __ESC__ ввести `:X`  __Enter__*
 ### __8. Отправить изменения на внешний репозиторий.__
- *`git commit -am "new information added"`*
- *`git push`*
### __9. Создать файл preferences.xml.__
- *`touch preferences.xml`*
### __10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате XML.__
- *`vim preferences.xml`*
- *Insert*
 ```
<?xml version="1.0"?>
<preferences>
  <favoriteMovie>The Terminal</favoriteMovie>
  <favoriteSeries>Suits</favoriteSeries>
  <favoriteFood>pasta</favoriteFood>
  <favoriteSeason>summer</favoriteSeason>
  <countryIWouldLikeToVisit>Japan</countryIWouldLikeToVisit>
</preferences>
```
 - *Нажать __ESC__ ввести `:X`  __Enter__*
### __11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML.__
- *`cat > skills.xml`*
```
<skills>
<skill>SoftwareTestingTheory</skill>
<skill>LinuxTerminal</skill>
<skill>GitBash</skill>
<skill>GitHun</skill>
<skill>DevTools</skill>
<skill>SQL</skill>
<skill>Postman</skill>
<skill>Jmeter</skill>
<skill>Fiddler</skill>
<skill>Python</skill>
</skills>
```
- *__Enter__*
- *__CTRL+C__*
### __12. Отправить сразу 2 файла на внешний репозиторий.__
- *`git add . && git commit -m "add preferences.xml and skills.xml" && git push`*
- 
### __13. На веб интерфейсе создать файл bug_report.xml.__
- *В репозитории __XML__ нажать __Add file__ и выбрать __Create new file.__*
-  *В поле __Name your file__ ввести __bug_report.xml.__*
### __14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.__
-  *Нажать  __Commit changes__*
-  *Подтвердить  __Commit changes__*
### __15. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.__
- *Открыть файл __bug_report.xml__ нажать на кнопку __Edid this file__ *
 ```
{
    "ID": "123",
    "Severity": "Critical",
    "Priority": "High",
    "Status": "New",
    "Title": "Нажатие кнопки 'Контакты' на главной странице не перенаправляет на страницу Контакты",
    "Project": "Интернет-магазин 'Колесо'",
    "STR": [
             "1. Зайти на главную страницу сайта (ссылка_сайта)",
             "2. Нажать кнопку Контакты"
    ],
    "Enviroment": {
                "OS": "Windows 10 x64 build 19045.2965",
                "Browser": "Google Chrome v113.0.5672.93 x64 bit"
    },
    "Component": "Кнопка Контакты",
    "Actual result": "Нажатие кнопки Контакты НЕ перенаправляет на страницу Контакты",
    "Expected result": "Нажатие кнопки Контакты перенаправляет на страницу Контакты",
    "Attachments": "ссылка_на_картинку_или_видео_с_багом"
    "Author": "Марлен Аблякимов",
}
```



### __16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.__
-  *Нажать  __Commit changes.__*
### __17. Синхронизировать внешний и локальный репозиторий XML.__
- *`git pull`*
