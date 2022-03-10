==============
### TXT
==============
1. Создать внешний репозиторий c названием TXT.  
**`Зайти на сайт github.com, создать новый репозиторий TXT, нажать Code и скопировать ссылку на репозиторий`**

2. Клонировать репозиторий TXT на локальный компьютер.  
**`На локальном компьютере зайти в папку, где будет размещен репозиторий, запустить Gitbash и ввести команду git clone https://github.com/AlexKantrov/TXT.git`**

3. Внутри локального TXT создать файл “new.txt”.  
**`cd TXT/ (перейти в папку созданного репозитория на локальном компьютере) и ввести команду touch new.txt`**

4. Добавить файл под гит.  
**`git add new.txt или git add . (добавляет все существующие файлы)`**

5. Закоммитить файл.  
**`git commit -m "add new.txt"`**

6. Отправить файл на внешний GitHub репозиторий.  
**`git push`**

7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных,
 будущая желаемая зарплата). Всё написать в формате TXT.  
**`vim new.txt`**
```
    Name:Alexey
    age:39
    Pets:
     quantity:1
     Pet name:Bonya
    Expected salary:1200$
```
8. Отправить изменения на внешний репозиторий.  
**`git add new.txt => git commit -m "modified new.txt => git push`**

9. Создать файл preferences.txt  
**`touch preferences.txt`**

10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда,
 любимое время года, сторона которую хотели бы посетить) в формате TXT.  
**`vim preferences.txt`**
```
    favorite movie:fight club
    favorite serial:Breaking bad
    favorite food:meat
    favorite seasons:spring, summer, autumn
    country i would like to visit: Australia
```
11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT  
**`touch skills.txt => vim skills.txt или cat > skills.txt`**
```
    Theory
    Client-server
    HTTP
    selects
    Json, xml: structure
    API
    Postman
    Dev Tools
    VPN
    Mobile testing
    Charles
    Fiddler
    Python
    and more.
```
12. Сделать коммит в одну строку.  
**`git add . && git commit -m "add new txt file"`**
 
13. Отправить сразу 2 файла на внешний репозиторий.  
**`git push`**
 
14. На веб интерфейсе создать файл bug_report.txt.  
**`В репозитории TXT (сайт github.com) нажимаем на кнопку "add file" и нажимаем "create new file" с названием bug_report.txt`**

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
**`В появившемся окне нажимаем "commit new file"`**

16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.  
**`На вебинтерфейсе открыть файл путем редактирования и ввести текст`**

17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
**`Сохранить изменения (нажать на кнопку Commit changes на вебинтерфейсе)`**
 
18. Синхронизировать внешний и локальный репозиторий TXT  
**`git pull`**
