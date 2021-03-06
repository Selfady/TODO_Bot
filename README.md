# Homework_Theme_10

Задача
Цель домашнего задания
Научиться создавать интерфейсы оконных приложений с помощью технологии WPF.



Что нужно сделать
Создайте оконный интерфейс для бота из предыдущего задания с использованием WPF.

В приложении необходимо реализовать отображение списка сообщений, которые написал боту пользователь. В списке присутствуют как минимум имя пользователя и его сообщение. При нажатии на сообщение оно становится выделенным.

Помимо этого, приложение может отправлять выбранному пользователю ответ в виде текста. Для реализации этого потребуется использовать элементы управления Button и TextBox. При каждом новом полученном сообщении приложение сохраняет его в истории сообщений. Потом её можно импортировать в файл формата JSON. Также вы можете добавить в приложение меню, в котором можно совершить сохранение истории, выход из приложения, просмотр список присланных файлов в новом окне и так далее.

При этом приложение не должно выглядеть некрасиво при растягивании на весь экран.



Советы и рекомендации
Необязательно использовать стандартный дизайн элементов управления WPF. Вы можете установить, например, пакет Material Design.
Не ограничивайте себя поставленным заданием. Если ваш бот может присылать курс криптовалют, попробуйте сделать его график, а если бот позволяет узнать погоду, выведите таблицу с основными атмосферно-температурными показателями.


Что оценивается
В задании используется WPF.
В главном окне программы содержатся: список сообщений пользователя, поле для ввода ответа, кнопка для отправки ответа.
Все сообщения от всех пользователей сохраняются в формате JSON.