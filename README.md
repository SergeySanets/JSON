1). Создать внешний репозиторий c названием JSON.
2). Клонировать репозиторий JSON на локальный компьютер.
 git clone https://github.com/SergeySanets/JSON.git

3). Внутри локального JSON создать файл “new.json”.
  touch new.json

4). Добавить файл под гит.
 git add new.json

5). Закоммитить файл.
 git commit -a -m "commit1"

6). Отправить файл на внешний GitHub репозиторий.
 git push

7). Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
$ cat > new.json

{
"first_name":"Sergey",
"last name":"Sanets",
"age":"28",
"pets":"2",
"salary":"500$"
}

8). Отправить изменения на внешний репозиторий.
 git commit -a -m "commit2"
 git push

9). Создать файл preferences.json
touch preferences.json

10). В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.

 cat > preferences.json

{
"favourite_film":"1+1",
"favourite_serial":"none",
"favourite_food":"potato",
"favourite_season":"winter"
}

11). Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON

touch skills.json
cat > skills.json

{
"skill_1":"API",
"skill_2":"API",
"skill_3":"API"
}

12). Отправить сразу 2 файла на внешний репозиторий.

git add preferences.json skills.json
git commit -a -m "commit1"
git push

13). На веб интерфейсе создать файл bug_report.json.

...

14). Сделать Commit changes (сохранить) изменения на веб интерфейсе.

...

15). На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.

{
"name":"fix_main_window",
"type":"bug",
"priority":"medium",
"environment":"windows_11",
"desciption":"none",
"attachment":"none"
}

16). Сделать Commit changes (сохранить) изменения на веб интерфейсе.

...

17). Синхронизировать внешний и локальный репозиторий JSON

git pull
