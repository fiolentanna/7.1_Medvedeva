# 7.1_Medvedeva

Проект SqlVerifierд развернут по ссылке https://sqlverifier-live-6e21ca0ed768.herokuapp.com/

В репозитории присутствует коллекция "Сhange task" с запросами:
1) Create task, в котором в Pre-req  так же реализован запрос на авторизауцию пользователя с правами админа
2) Get task list
3) Change task text, в котором в Pre-req реализовано изменение значения переменной  text 
4) Get task data, в котором в Tests так же реализован запрос на удаление созданной ранее таски и так же очистка переменных окружения

Переменные  коллекции:
* baseUrl:  https://sqlverifier-live-6e21ca0ed768.herokuapp.com/api
* adminLogin: busya2024_admin -  логин для учетной записи с правами администратора
* adminPassword:  busya2024_admin - пароль для учетной записи с правами администратора

В запросах реализованы тесты на 
- статус код ответа
- статус-сообщение ответа
- содержимое тела ответа
- хедеры ответа

В тестах подключены и использованы библиотеки moment и chai. Они используются совместно для проверки соответствия даты в заголовке ответа и текущей даты для кажого из запросов в коллекции. 
Библиотека chai используется для остальных тестов к запросам. 


