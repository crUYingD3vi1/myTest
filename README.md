Последовательность проектирования продукта

Продукт - конфигуратор тестов
Можно создать тест (один ответ / несколько ответов)
Можно выполнить тест - есть ссылка на продукт. Можно выполнить тест и получить результат (показывать / не показывать правильные ответы)
Нужна ли регитсрация??? (login / ip / session-id / cookies)
Создание теста - нужна регистрация
Выполнение теста - без регистрации



Создание теста: 

Каждый тест хранится в БД

У теста есть:

-id
-author
-name


Вопросы
-id 
-test_id
-text

Ответы
-id
-quest_id
-text
-isTrue

Выполнение теста
-quest_session
-user
-test_id

Выполненные вопросы
-id 
-quest_session
-test_id
-isTrue



BackEnd
node.js
router "/" (public => angular)
router "/api" => db

FrontEnd
Angular (index.html)

