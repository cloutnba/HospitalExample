For login: 
Email: toni.kiselevich@gmail.com
Pass: Test12345

Кабинет для создания визитов к врачу, создав визит на одном устройстве, вы можете залогиниться с другого устройства в этот аккаунт и вся информация сохранится.

ТЗ :
Вам нужно создать страницу, на которой Секретарша сможет создавать карточки, описывающие запланированные визиты к врачам.
На странице должны присутствовать:

1)Header (шапка) страницы:
    в левом верхнем углу - логотип. Можно взять любой
    в правом углу - Кнопка "Вход". После успешной авторизации она должна меняться на Кнопку "Создать визит".
2)Под Header - форма для фильтрации визитов. В этой форме должно быть 3 поля:
    поиск по заголовку/содержимому визита
    поиск по статусу (Open/Done) (визит прошел или еще нет)
    срочность визита (High, Normal, Low)
3)Под формой фильтров - список созданных визитов.

1)При первом посещении пользователем страницы, на доске должна быть надпись No items have been added. Эта же надпись должна быть, если у пользователя нету ни одной добавленной карточки (например, он их все удалил).
2)По клику на кнопку Вход появляется модальное окно, в котором пользователь вводит свой email и пароль. Если он верный - пользователю на странице выводится список ранее созданных визитов.
3)По клику на кнопку Создать визит появляется модальное окно, в котором можно создать новую карточку.
4)Для создания классов нужно использовать синтаксис class из ES6.
5)Для выполнения AJAX запросов можно использовать fetch или axios.
6)После выполнения любых AJAX запросов, страница не должна перезагружаться. При добавлении/удалении карточки и других подобных операциях, с сервера не должен заново загружаться весь список карточек. Необходимо использовать данные из ответа сервера и Javascript для обновления информации на странице.
7)При обновлении страницы или ее закрытии, ранее добавленные заметки не должны пропадать.
8)Желательно разделить проект на модули с помощью ES6 modules.

