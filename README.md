# Profi_hack_clever
Задача с образовательного форума "Я-профессионал" по классификации вопросов викторины вконтакте "Клевер"

Описание задачи: Вы наверняка слышали об онлайн-викторине "Клевер", разработанной командой ВКонтакте вместе с "Творческой лабораторией Ивана Урганта". С 14 марта по 31 декабря 2018 года в специальном мобильном приложении участникам нужно было выбрать правильный ответ на заданный вопрос из трёх предложенных вариантов. Игроки, правильно ответившие на все 12-15 вопросов игрового сеанса, поровну делили разыгрываемый призовой фонд.  

Вопросы для игры были подготовлены профессиональными авторами и отобраны редакторами викторины. Но у пользователей Клевера тоже была возможность предлагать свои вопросы и варианты ответов на них.  

Вы получите доступ к набору из примерно 40 000 вопросов. Определите, какие примерно 10% из этих вопросов подготовлены экспертами? Ваши решения будут оцениваться по метрике ROC-AUC. 

В файле data.csv будет доступен список всех вопросов игры, а в train.csv информация для части вопросов о том, подготовлен ли он профессиональными авторами или предложен участниками игры.  Решением является файл, содержащий в первом столбце идентификаторы вопросов, а во втором - вероятность принадлежности к классу.

Сохраняйте порядок идентификаторов вопросов, указанный в файле test.csv.
