#### JSON

 1. Создать внешний репозиторий c названием JSON.
+ go to github.com and log in
+ click "new" to create new repositary
+ set repositary name to "JSON"
+ chose "Public" repositary and "Add a README file" at checkboxes
+ click "Create repositary"

 2. Клонировать репозиторий JSON на локальный компьютер. — `git clone https://github.com/del0nius/JSON.git`
 3. Внутри локального JSON создать файл “new.json”. — (`cd JSON`) `touch new.json`
 4. Добавить файл под гит. — `git add new.json` (и проверяем через `git status`)
 5. Закоммитить файл. — `git commit -m new.json`
 6. Отправить файл на внешний GitHub репозиторий. — `git push`
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
```
vim new.json (i)
{
   "FullName": "Daniil Pavlovich Gaponenko",
   "Age": 27,
   "Number of pets": 1,
   "Desired salary": "650$"
}
(esq) :wq
```
 8. Отправить изменения на внешний репозиторий. — `git add new.json ; git commit -m new.json ; git push`
 9. Создать файл preferences.json — `touch preferences.json`
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
```
vim preferences.json (i)
{
   "Favourite movie": "Dead poets society",
   "Favourite series": "The Sopranos",
   "Favourite food": "Noodles",
   "Favourite season": "Summer",
   "Country i'd like to visit": "Japan"
}
(esq) :wq
 ```
 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
 ```
cat > skills.json
{
"Skill set": [
	"1. Basic theory",
	"2. Client-server architecture.",
	"3. HTTP server request methods.",
	"4. HTTP server response codes.",
	"5. Structures of HTTP inputs and responses.",
	"6. What is JSON, XML. Their structure.",
	"7. API testing via Postman (JS, API autotests).",
	"8. Removing and reading logs from an external server.",
	"9. Sniffing http web traffic via Charles and Fiddler.",
	"10. Web Dev Tools (Google Chrome, FireFox).",
	"11. VPN. (How it works, why you need it, how to use it, tool options)",
	"12. Mobile testing.",
	"13. Feature iOS, Android, guidelines.",
	"14. Building iOS applications on XCode.",
	"15. Building Android applications on Android Studio.",
	"16. ADB (android device management).",
	"17. Setting up proxy and vpn on iOS and Android.",
	"18. Interception (sniffing) of traffic through Charles and Fiddler on iOS and Android.",
	"19. Command line (terminal) Linux (copy, create, view, move files on servers without a graphical interface)",
	"20. Basics of bash scripting, automation of routine tasks on the server.",
	"21. Access to remote servers.",
	"22. SQL basics (create, delete, drop, insert into, select, from, where, join).",
	"23. Postgres database (installation, configuration and use).",
	"24. Non-relational database Redis (installation, configuration and use).",
	"25. Load testing in Jmeter.",
	"26. Scrum development methodology.",
	"27. Python. (Learning the basics. Creating a client server application)"
	]
}
Enter (Ctrl+D)
```
 12. Отправить сразу 2 файла на внешний репозиторий. — `git add "preferences.json" "skills.json" ; git commit -m "add two files" ; git push`
 13. На веб интерфейсе создать файл bug_report.json.
+ Go to repository "JSON"
+ Click "Add file" - "Create new file"
+ Enter "bug_report.json" in the name_field
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
+ click "commit new file'
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
+ open file "bug_report.json" and click "edit this file"
```
{
	"Bug ID": 123,
	"Bug Name": "Add_to_cart_01",
	"Summary": "Unable to add a second item via the add_to_cart button",
	"Submit Date": "22.02.2022",
	"Reporter": "del0nius",
	"Operating System": "Windows 10",
	"Browser": "Chrome",
	"URL": "https://example.com/product/abc",
	"Description": "When my cart contains one item, I am unable to add a second item via the add_to_cart button on a product page",
	"Steps to reproduce": {
		"1": "Go to https://example.com/catalog",
		"2": "Add any item to the cart",
		"3": "Go to any product page",
		"4": "click on add_to_cart button"
	},
	"Expected result": "being able to add a second item to the cart",
	"Actual result": "NOT being able to add a second item to the cart",
	"Screenshot": "https://example.com/screenshot/bug01"
}
 ```
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе. 
 + click "commit changes"
 17. Синхронизировать внешний и локальный репозиторий JSON — `git pull`

#### XML

 1. Создать внешний репозиторий c названием XML. 
+ go to github.com and log in
+ click "new" to create new repositary
+ set repositary name to "XML"
+ chose "Public" repositary and "Add a README file" at checkboxes
+ click "Create repositary"

 2. Клонировать репозиторий XML на локальный компьютер. — `git clone https://github.com/del0nius/XML.git`
 3. Внутри локального XML создать файл “new.xml”. — (`cd XML`) `touch new.xml`
 4. Добавить файл под гит. — `git add new.xml` (и проверяем через `git status`)
 5. Закоммитить файл. — `git commit -m new.xml`
 6. Отправить файл на внешний GitHub репозиторий. — `git push`
 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
```
vim new.xml (i)
<aboutme>
  <fullname>Daniil Pavlovich Gaponenko</fullname>
  <age>27</age>
  <numbberofpets>1</numbberofpets>
  <desiredsalary>650$</desiredsalary>
</aboutme>
(esq) :wq
```
 8. Отправить изменения на внешний репозиторий. — `git add new.xml ; git commit -m new.xml ; git push`
 9. Создать файл preferences.xml — `touch preferences.xml`
 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML. 
```
vim preferences.xml (i)
<preferences>
  <favmovie>Dead poets society</favmovie>
  <favseries>The Sopranos</favseries>
  <favfood>Noodles</favfood>
  <favseason>Summer</favseason>
  <countrytovisit>Japan</countrytovisit>
</preferences>
(esq) :wq
```
 11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
```
cat > skills.xml
<skills>
  <one>Basic theory</one>
  <two>Client-server architecture</two>
  <three>HTTP server request methods</three>
  <four>HTTP server response codes</four>
  <five>Structures of HTTP inputs and responses</five>
  <six>What is JSON, XML. Their structure</six>
  <seven>API testing via Postman (JS, API autotests)</seven>
  <eight>Removing and reading logs from an external server</eight>
  <nine>Sniffing http web traffic via Charles and Fiddler</nine>
  <ten>Web Dev Tools (Google Chrome, FireFox)</ten>
  <eleven>VPN(How it works, why you need it, how to use it, tool options)</eleven>
  <twelve>Mobile testing</twelve>
  <thirteen>Feature iOS, Android, guidelines</thirteen>
  <fourteen>Building iOS applications on XCode</fourteen>
  <fivteen>Building Android applications on Android Studio</fivteen>
  <sixteen>ADB (android device management)</sixteen>
  <seventeen>Setting up proxy and vpn on iOS and Android</seventeen>
  <eighteen>Interception (sniffing) of traffic through Charles and Fiddler on iOS and Android</eighteen>
  <nineteen>Command line (terminal) Linux (copy, create, view, move files on servers without a graphical interface)</nineteen>
  <twenty>Basics of bash scripting, automation of routine tasks on the server</twenty>
  <twentyone>Access to remote servers</twentyone>
  <twentytwo>SQL basics (create, delete, drop, insert into, select, from, where, join)</twentytwo>
  <twentythree>Postgres database (installation, configuration and use)</twentythree>
  <twentyfour>Non-relational database Redis (installation, configuration and use)</twentyfour>
  <twentyfive>Load testing in Jmeter</twentyfive>
  <twentysix>Scrum development methodology</twentysix>
  <twentyseven>Python(Learning the basics. Creating a client server application)</twentyseven>
</skills>
Enter (Ctrl+D)
 ```
 12. Сделать коммит в одну строку. — `git add . ; git commit -m "commit in one line"`
 13. Отправить сразу 2 файла на внешний репозиторий. — `git push`
 14. На веб интерфейсе создать файл bug_report.xml.
+ Go to repository "XML"
+ Click "Add file" - "Create new file"
+ Enter "bug_report.xml" in the name_field
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
+ click "commit new file'
 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML. 
+ open file "bug_report.xml" and click "edit this file"
```
<bugreport>
<bugid>123</bugid>
<bugname>Add_to_cart_01</bugname>
<summary>Unable to add a second item via the add_to_cart button</summary>
<submitdate>22.02.2022</submitdate>
<reporter>del0nius</reporter>
<OS>Windows 10</OS>
<browser>Chrome</browser>
<URL>https://example.com/product/abc</URL>
<Description>When my cart contains one item, I am unable to add a second item via the add_to_cart button on a product page</Description>
<StepsToReproduce>
	<one>Go to https://example.com/catalog</one>
	<two>Add any item to the cart</two>
	<three>Go to any product page</three>
	<four>click on add_to_cart button</four>
</StepsToReproduce>
<expresult>being able to add a second item to the cart</expresult>
<actualresult>NOT being able to add a second item to the cart</actualresult>
<screenshot>https://example.com/screenshot/bug01</screenshot>
</bugreport>
```
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 + click "commit changes"
 18. Синхронизировать внешний и локальный репозиторий XML — `git pull`

#### TXT
 1. Создать внешний репозиторий c названием TXT.
- go to github.com and log in
- click "new" to create new repositary
- set repositary name to "TXT"
- chose "Public" repositary and "Add a README file" at checkboxes
- click "Create repositary"

 2. Клонировать репозиторий TXT на локальный компьютер. — `git clone https://github.com/del0nius/TXT.git`
 3. Внутри локального TXT создать файл “new.txt”. — (`cd TXT`) `touch new.txt`
 4. Добавить файл под гит. — `git add new.txt` (и проверяем через `git status`)
 5. Закоммитить файл. — `git commit -m new.txt`
 6. Отправить файл на внешний GitHub репозиторий. — `git push`
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
```
vim new.txt (i)
   FullName: Daniil Pavlovich Gaponenko
   Age: 27
   Number of pets: 1
   Desired salary: 650$
(esq) :wq
```
 8. Отправить изменения на внешний репозиторий. — `git add new.txt ; git commit -m new.txt ; git push`
 9. Создать файл preferences.txt — `touch preferences.txt`
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
```
vim preferences.txt (i)
   Favourite movie: Dead poets society
   Favourite series: The Sopranos
   Favourite food: Noodles
   Favourite season: Summer
   Country i'd like to visit: Japan
(esq) :wq
```
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
```
cat > skills.txt
Skill set:
1. Basic theory.
2. Client-server architecture.
3. HTTP server request methods.
4. HTTP server response codes.
5. Structures of HTTP inputs and responses.
6. What is JSON, XML. Their structure.
7. API testing via Postman (JS, API autotests).
8. Removing and reading logs from an external server.
9. Sniffing http web traffic via Charles and Fiddler.
10. Web Dev Tools (Google Chrome, FireFox).
11. VPN. (How it works, why you need it, how to use it, tool options)
12. Mobile testing.
13. Feature iOS, Android, guidelines.
14. Building iOS applications on XCode.
15. Building Android applications on Android Studio.
16. ADB (android device management).
17. Setting up proxy and vpn on iOS and Android.
18. Interception (sniffing) of traffic through Charles and Fiddler on iOS and Android.
19. Command line (terminal) Linux (copy, create, view, move files on servers without a graphical interface)
20. Basics of bash scripting, automation of routine tasks on the server.
21. Access to remote servers.
22. SQL basics (create, delete, drop, insert into, select, from, where, join).
23. Postgres database (installation, configuration and use).
24. Non-relational database Redis (installation, configuration and use).
25. Load testing in Jmeter.
26. Scrum development methodology.
27. Python. (Learning the basics. Creating a client server application).
Enter (Ctrl+D)
 ```
 12. Сделать коммит в одну строку. — `git add . ; git commit -m "commit in one line"`
 13. Отправить сразу 2 файла на внешний репозиторий. — `git push`
 14. На веб интерфейсе создать файл bug_report.txt 
- Go to repository "TXT"
- Click "Add file" - "Create new file"
- Enter "bug_report.txt" in the name_field
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 - click "commit new file'
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
- open file "bug_report.txt" and click "edit this file"
```
Bug ID: 123
Bug Name: Add_to_cart_01
Summary: Unable to add a second item via the add_to_cart button.
Submit Date: 22.02.2022
Reporter: del0nius
Operating System: Windows 10
Browser: Chrome
URL: https://example.com/product/abc
Description: When my cart contains one item, I am unable to add a second item via the add_to_cart button on a product page.
Steps to reproduce: 
	1. Go to https://example.com/catalog.
	2. Add any item to the cart.
	3. Go to any product page.
	4. click on add_to_cart button.
Expected result: being able to add a second item to the cart.
Actual result: NOT being able to add a second item to the cart.
Screenshot: https://example.com/screenshot/bug01
 ```
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе/
 - click "commit changes"
 18. Синхронизировать внешний и локальный репозиторий TXT — `git pull`
