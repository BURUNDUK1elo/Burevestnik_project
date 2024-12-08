# **Проект "РемонтЭксперт" для завода Буревестник**

Проект разделен на 3 части: серверная(server), приложение(client) - основное, телеграм-бот(telegram)

## **_Client:_**

Вы можете запустить приложение 2-умя способами:

* _py (client/main.py)_
* _.exe (client/setup/dist/main.exe)_

##### О приложении

Приложение разделяет пользователей на 2 группы:
* Работник(User) 
* Диспетчер(Admin)

Чтобы зайти в аккаунт Admin вам необходимо ввести логин и пароль - admin, admin, а для User зарегистрироваться

Функции приложения описываются в ТЗ там все(ну почти*). Думаю сами разберетесь...))


## **_Server:_**

Для запуска "сервера" вам необходимо запустить server/main.py(если создатель забил на хост) и поменять API_URL в файле client/settings.py на ваш URL(с вашим URL .exe не будет работать)
 
Бекенд просто базисный написанный на коленке с костылями

## **_Telegram:_**

**Telegaram-bot** - _@Remont_expert_bot_

Для запуска вам потребуется запустить telegram/main(тут тоже если забил на хост)*

В боте можно привязать аккаунт к пользователю и получать там уведомления от привязанных аккаунтов

## Недоделки *

* .exe файл не имеет картинок
* Чтобы запустить тг-бота и для его корректной работы вам потребуйте специальный файл, за которым обратитесь в тг @34_elo
* Упущенная выгода предприятия(просто доп.функция из ТЗ)

## **Разработчики**

* **Евсеев Никита(_34elo_)** - весь код написан этим парнем
* **Хоченков Кирилл(_Gumke1_)** - весь дизайн сделан этим парнем

## ТЗ и презентация
О нашем ТЗ можете подробнее ознакомится в директории "ТЗ" и презентацией соответственно также.