<h1 align="center">eXtensible Markup Language</h1>

 1. Создать внешний репозиторий c названием XML - `Github Аккаунт в вебе` > _вкладка_ `Repositories` > _кнопка_ `New`
 2. Клонировать репозиторий XML на локальный компьютер - `git clone https://github.com/XXXXX/XML.git`
 3. Внутри локального XML создать файл “new.xml”. touch new.xml - `touch new.xml`
 4. Добавить файл под гит - `git add new.xml`
 5. Закоммитить файл - `git commit -m 'add new.xml'`
 6. Отправить файл на внешний GitHub репозиторий - `git push`
 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML - `vim new.xml`
```XML
<?xml version="1.0" encoding="UTF-8"?>
<rdntest category="QA">
	<firstname>Dmitry</firstname>
	<lastname>Romanushkov</lastname>
	<age>27</age>
	<numberOfPets>1</numberOfPets>
	<futureDesiredSalary>2000</futureDesiredSalary>
</rdntest>
```
 8. Отправить изменения на внешний репозиторий - `git commit -am 'update new.xml'` > `git push`
 9. Создать файл preferences.xml - `vim preferences.xml`
 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
```XML
<?xml version="1.0" encoding="UTF-8"?>
<rdntest>
	<favoriteFilm>The Lord Of The Rings</favoriteFilm>
	<favoriteSerial>GameOfThrones</favoriteSerial>
	<favoriteFood>Pizza</favoriteFood>
	<favoriteSeason>Winter</favoriteSeason>
	<countryIWouldLikeToVisit>USA</countryIWouldLikeToVisit>
</rdntest>
```
 11. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML - `vim skills.xml`
```XML
<?xml version="1.0" encoding="UTF-8"?>
<rdntest>
	<skill>Software testing theory</skill>
	<skill>Test-design techniques</skill>
	<skill>Working with test documentation</skill>
	<skill>Client-server architecture</skill>
	<skill>JSON and XML structure</skill>
	<skill>API testing via Postman</skill>
	<skill>Devtools practice</skill>
	<skill>Git and GitBash practice</skill>
	<skill>Payload testing via Jmeter</skill>
	<skill>Mobile testing</skill>
	<skill>SQL basics</skill>
	<skill>Python basics</skill>	
</rdntest>

```
 12. Отправить сразу 2 файла на внешний репозиторий - `git add .` > `git commit -m 'added 2 new files'` > `git push`
 13. На веб интерфейсе создать файл bug_report.xml - `Github Аккаунт в вебе` > `Add file` > `Create new file`
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 15. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
```XML
<?xml version="1.0" encoding="UTF-8"?>
<rdntest>
  <id>1</id>
  <severity>minor</severity>
  <priority>low</priority>
  <environment>
    <value>Windows 10 home, Chrome 112</value>
    <value>iPhone XR, IOS 16.5/<value>
  </enviroment>
  <title>The text hasn't been translated to EN on the 'About us' page</title>
  <stepsToReproduce>
    <step1>Navigate to site.com</step1>
    <step2>Click menu item 'About us</step2>
    <step3>Select EN language</step3>
  </stepsToReproduce>
  <actualResult>The text has been translated to EN</actualResult>
  <expectedResult>The text hasn't been translated to EN</expectedResult>
  <attachments xlink:type="simple" xlink:href="https://urltothevideo.com">link</attachments>
  <author>Poor tester</author>
</rdntest>
```
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 17. Синхронизировать внешний и локальный репозиторий XML - `git pull` - _сгрузить все изменения с удаленного репозитория в локальный._
