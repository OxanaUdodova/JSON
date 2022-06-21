# JSON
1. Создать внешний репозиторий c названием JSON.
Создала репозиторий https://github.com/OxanaUdodova/JSON

2. Клонировать репозиторий JSON на локальный компьютер.
git clone https://github.com/OxanaUdodova/JSON.git

3. Внутри локального JSON создать файл “new.json”.
cd JSON > touch new.json

4. Добавить файл под гит.
git add new.json

5. Закоммитить файл.
git commit -m "add new.json"
git config --global user.name "OxanaUdodova"

6. Отправить файл на внешний GitHub репозиторий.
git push

7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
nano new.json
{"name": "Udodova Oxana Sergeevna",
"age": 35,
"pet": 1,
"salary": 50000}
Сtrl+o (Сохранить изменения) >> Сtrl+x (Выйти)

8. Отправить изменения на внешний репозиторий.
git add new.json >>  git commit -m "modify new.json" >>  git push

9. Создать файл preferences.json
touch preferences.json

10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
nano preferences.json 
{
	"preferences": {
		"favor_film": "Harry Potter",
		"favor_serial": "none",
		"favor_food": "none",
		"favor_season": "spring",
		"country": "Italy"
	}
}

Сtrl+o (Сохранить изменения) >> Сtrl+x (Выйти)

11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
nano sklls.json 

{
    "skills": 
    [
        "Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC",
        "Что такое клиент-серверная архитектура",
        "HTTP Методы запросов на сервер",
        "Коды ответов HTTP сервера".... и т.д.  ]
}

Сtrl+o (Сохранить изменения) >> Сtrl+x (Выйти)

12. Отправить сразу 2 файла на внешний репозиторий.
git add . >>  git commit -m "add 2 file" >> git push

13. На веб интерфейсе создать файл bug_report.json.
Add file >> Create new file

14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit changes

15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
{
    "bug_report": {
      "Bug_id": 2,
      "Title": "Add widget” button is not working on device",
      "Severity": "high",
      "Priority": "low",
      "Environment": "Honor 8x JSN-L21 Android 10.0.0260",
      "Precondition": "Clear the app from running",
      "Step_To_Reproduce": "1)Open app; 2)Click “Add Widget” button",
      "Actual_Result": "Nothing happens, button is not working, widget is not created on any page",
      "Expected_Result": "Widget creation window appears/widget created"
    }
  }


16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit changes

17. Синхронизировать внешний и локальный репозиторий JSON
git pull
