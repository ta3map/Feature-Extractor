# Feature-Extractor
Pinpoint objects manually

Теперь запустим нашу программу feature extractor. С ней работать очень легко, мы просто выделяем объект который нас интересует. Вот здесь например это лицо этой обезьяны.
![GitHub Logo](/screenshots/screen1.png)
Мы отмечаем фичи. Во-первых, мы отмечаем что это обезьяна. Во вторых, мы отмечаем что это лицо. Мы не отмечаем что это ребенок, потому что это взрослая обезьяна. 
![GitHub Logo](/screenshots/screen2.png)
Дальше мы просто добавляем объект, нажимаем "Add Object". Вот он появился в нашей таблице с результатами. Здесь соответственно, с фичами отметилось что это обезьяна (monkey), то что это лицо (face), то что это взрослая обезьяна (adult). Также здесь отмечена площадь которую занимает это выделение (Area) и общая площадь всей картинки (Image area). Эти колонки всегда присутствуют.
![GitHub Logo](/screenshots/screen3.png)
Скажем, я захотел отметить еще других обезьян и один раз ошибся - и отметил что это 
"не обезьяна", или отметил не то что надо, или плохо выделил например. Проще говоря, добавил 
объект по ошибке. Если что, я могу выделить объект который меня не устраивает и удалить его (Delete object). Переключаюсь между объектами (знаки + - ) , вот это удалил.
![GitHub Logo](/screenshots/screen4.png)
После того как я переключился, посмотрел все картинки которые мне нужно, отметил все объекты которые мне нужны - я могу сохранить результаты (Save Results). 
![GitHub Logo](/screenshots/screen5.png)
И далее я например могу во-первых посмотреть где моя таблица находится (Show table in Folder), если я например забыл. Я могу например сделать новую таблицу (New Table) назвать и её как-нибудь. Тогда у нас автоматически все (предыдущие) результаты очищаются, мы начинаем с самого начала.
![GitHub Logo](/screenshots/screen6.png)

![GitHub Logo](/screenshots/screen7.png)
![GitHub Logo](/screenshots/screen8.png)
![GitHub Logo](/screenshots/screen9.png)
Теперь перейдем к другим настройкам. Вот здесь отмечены папки в которых находятся все наши картинки. Например в данном случае мы используем картинки из готового примера.
Все возможные фичи, которые здесь - то что это обезьяна, то что это лицо, то что это взрослый или ребенок отмеченных таблице фич (features). Все возможные категории, которые в название картинки указаны, и автоматически здесь выбираются, перечисленных таблицы категории (categories).
![GitHub Logo](/screenshots/screen10.png)

![GitHub Logo](/screenshots/screen11.png)
