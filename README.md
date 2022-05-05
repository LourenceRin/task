## Диспетчер задач
Приложение для управления задачами для команды или небольшой компании
Прямой эфир: https://task-manager-r.herokuapp.com/

## Функции:
Для большинства функций требуется вход в систему
Неавторизованные пользователи имеют доступ к экрану приветствия и панели входа или регистрации.

## Администратор (менеджер) может:

Создать задачу и назначить задачу любому пользователю
Просмотр списка всех пользователей с возможностью удаления пользователя
Просмотр списка всех задач с редактированием или удалением задачи
Переключить задачу как выполненную/незавершенную
Обычный пользователь (сотрудник) может:

Создать задачу только для себя
Просмотр списка всех пользователей без разрешенных действий
Просмотрите список всех задач, но отредактируйте или удалите только задачи, за которые он отвечает
Переключение собственной задачи как завершенной/незавершенной
Каждый авторизованный пользователь может:

##Построен с
- Весенний ботинок
- Весенняя безопасность
- База данных H2
- Мавен
- Лист тимьяна
- Начальная загрузка
- jQuery

##Тестовые пользователи

    url: "jdbc:postgresql://localhost:1234/wh_db"
    username: "postgres"
    password: "733123"

пароль manager@mail.com: 112233
ann@mail.com пароль: 112233
mark@mail.com пароль: 112233
