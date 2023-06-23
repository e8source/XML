# XML
Work with GIT, gitbash

 1. Создать внешний репозиторий c названием XML.
 2. Клонировать репозиторий XML на локальный компьютер. 
 
        git clone git@github.com:e8source/XML.git
 3. Внутри локального XML создать файл “bio.xml”. 
 
        touch bio.xml
 4. Добавить файл под гит. 
 
        git add bio.xml
 5. Закоммитить файл. 
 
        git commit -m "add bio.xml"
 6. Отправить файл на внешний GitHub репозиторий. 
 
        git push
 7. Отредактировать содержание файла “bio.xml” - написать информацию о себе в формате XML (ФИО, возраст, локация, роль).
        
        nano bio.xml
 8. Отправить изменения на внешний репозиторий. 

        git add bio.xml
        git commit -m "edit bio.xml"
        git push
 9. Создать файл preferences.xml 
 
        touch preferences.xml
 10. В файл preferences.xml добавит информацию о своих предпочтениях в формате XML (музыка, игра, фильм, сериал).
 
	       nano preferences.xml
 11. Создать файл skills.xml добавить информацию о скиллах в формате XML.
 
        touch skills.xml  
        nano skills.xml 
 12. Сделать коммит в одну строку. 
 
        git add . && git commit -m "add preferences.xml and skills.xml"
 13. Отправить сразу 2 файла на внешний репозиторий. 
 
        git push
 14. На веб интерфейсе создать файл bug_report.xml.
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 18. Синхронизировать внешний и локальный репозиторий XML. 
 
         git pull
