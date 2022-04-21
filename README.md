# wikitabia-telegram-bot
Telegram Bot проекта Wikitabia - @wikitabia_bot.

## Эпилог
Стажировочный проект компании Интабия. 
Приглашаются все желающие попробовать свои силы в OpenSource разработке, 
получить обратную свзяь от профессиональных разработчиков, составить себе
обьектитвное портфолио к резюме начинающего Java-разработчика. С чего начать смотри [тут](./CONTRIBUTING.md).

## О чём проект
Telegram Bot для сохранения полезных ссылок на технические материалы 
с возможностью маркировать ссылку некоторым тэгом и в дальнейшем получать по тэгам
полезные материалы.

## Что уже можем

Сервер telegram бота, который по некоторому расписанию отслеживает команды пользователя:
1) Добавить ссылку
2) Добавить тэги на ссылку
3) Просматривать добавленные ссылки

## Видение развития проекта

1) Стабилизировать первую рабочию версию проекта для разворачивания полноценного продакшен-реди сервера
2) Реализовать веб часть для администрирования добавляемых материалов
3) Настроить правила модерации материалов и участников с их уровнем доступа. Ограничить возможность добавления материалов только для ответсвенных участников и открыть доступ к материалам для всех.
4) Открыть развёрнутое продакшен решение для всех
5) Развивать продукт по обратной свзяи от пользователей

## Как собрать и запустить

Подготовь окружение:
1) Jdk 11
2) Maven 3

Собери проект
1) `maven clean install`

Запусти
1) Добавь в ресурсах токен тестового telegram бота. Параметр `application.token`.
2) `java -jar wikibot-1.0-SNAPSHOT.jar`

## Как проверить, что после моих изменений ничего не сломалось

1) Добавь тест на новые изменения
2) Собери проект с запуском тестов
