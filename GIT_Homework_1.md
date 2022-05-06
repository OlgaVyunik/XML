### GIT Homework 1  
Для выполнения задания должен быть установлен для Windows - GitBash.
Создан аккаунт в GitHub
Все шаги сценария выполняются в терминале GitBush, Terminal, в папке под гитом или на сайте github.com в своем аккаунте.
#### Сценарий   
 |Шаги|JSON|XML|TXT|
 |:--|:--|:--|:--|
 |1. Создать внешний репозиторий c названием... |github.com/new  <br/> -> Repository name JSON (Add readme.md)<br/> ->  Create repository|github.com/new  <br/> -> Repository name XML (Add readme.md)<br/> ->  Create repository|github.com/new  <br/> -> Repository name TXT (Add readme.md)<br/> ->  Create repository|
 |2. Клонировать репозиторий на локальный компьютер|git clone [link](https://github.com/OlgaVyunik/JSON.git) |git clone [link](https://github.com/OlgaVyunik/XML.git)|git clone [link](https://github.com/OlgaVyunik/TXT.git)|
 |3. Внутри локальной директории создать файл | cd JSON <br/>  touch new.json |cd XML <br/>  touch new.xml|cd TXT <br/>  touch new.txt|
 |4. Добавить файл под гит | git add new.json |git add new.xml|git add new.txt|
 |5. Закоммитить файл |git commit -m "new"|git commit -m "new"|git commit -m "new"|
 |6. Отправить файл на внешний GitHub репозиторий |git push|git push|git push|
 |7. Отредактировать содержание файла - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в соответствующем формате| start new.json -> edit -> save|start new.xml -> edit -> save|start new.txt -> edit -> save|
 |8. Отправить изменения на внешний репозиторий |git commit -am "update" <br/>  git push |git commit -am "update" <br/>  git push| git commit -am "update" <br/>  git push|
 |9. Создать файл | touch preferences.json |touch preferences.xml|touch preferences.txt|
 |10. В файл добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) | start preferences.json -> edit -> save |start preferences.xml -> edit -> save |start preferences.txt -> edit -> save |
 |11. Создать файл добавить информацию о скиллах которые будут изучены на курсе | touch skills.json  <br/>   start skills.json -> edit -> save |touch skills.xml  <br/>   start skills.xml -> edit -> save |touch skills.txt  <br/>   start skills.txt -> edit -> save |
 |12. Отправить сразу 2 файла на внешний репозиторий. | git add . <br/>   git commit -m "new" <br/> git push|git add .  <br/>  git commit -m "new" <br/> git push|git add .  <br/>  git commit -m "new" <br/> git push|
 |13. На веб интерфейсе создать файл | "Add file" -> bug_report.json|"Add file" -> bug_report.xml|"Add file" -> bug_report.txt|
 |14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.|"Commit new file"|"Commit new file"|"Commit new file"|
 |15. На веб интерфейсе модифицировать файл, добавить баг репорт в соответствующем формате |"Edit this file"|"Edit this file"|"Edit this file"|
 |16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.|"Commit changes"|"Commit changes"|"Commit changes"|
 |17. Синхронизировать внешний и локальный репозиторий |git pull|git pull|git pull|
