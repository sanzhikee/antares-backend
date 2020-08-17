# `Задача: `
Создать приложение по работе с финансовыми транзакциями.

## Необходимо создать минимальный каркас приложения:
- **Одна точка входа;**
- **Контроллеры;**
- **Сущности;**
- **Сервис (работа с БД);**

## Приложение должно соответствовать конструкционному шаблону MVC.

## В приложении должны присутствовать такие элементы как:
- **Авторизация (пользователь может быть заранее добавлен в БД)**
- **RBAC (3 роли: администратор, модератор, клиент)**
- **Страница управления средствами клиента (содержит информацию о текущем балансе и Поле вывода средств с кнопкой "вывести" )**
- **Страница для модератора - дает возможность добавлять средства на счет**
- **Страница для Администратора - дает возможность добавлять средства на счет, выводить и отменять транзакции (то есть отмена ввода или вывода)**
- **Страница для Администратора - Просмотр всех транзакции**

##Необходимо представить, что начисление и раздача денег происходит с Вашей родной банковской карты, так что если где-то будут ошибки, то ошибки будут стоить денег.

###В случае списания деньги не зачисляются на другой счет, списываем "вникуда".
###Сессия должна быть неблокируемой, использовать session_write_close().

##Решение может использовать очереди, но достаточно использования PHP + Mysql и понимания работ транзакций и блокировок записи в БД.

## Использовать boostrap, jQuery и прочие инструменты для html-страницы – можно, но не обязательно, упор идёт именно на серверную часть. Клиент может быть сделан даже в виде файла index.php, где через echo выводится форма. Делать html5-красивости и валидации на js нет необходимости, валидация должна быть на уровне php и базы.

## Тестовое задание должно быть выложено на личный аккаунт на github.com (можно использовать другие подобные git-системы).  

## Все это дело обернуть в докер

## Идеальное задание по стэку:
- **Api - на GoLang**
- **Миграции - на php**
- **Джобы - без разницы**
- **Админка - php**