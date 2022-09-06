# Тестовое задание (Junior Backend-разработчик/стажер)

Требуется создать консольное приложение на C# (.NET Core), которое реализует следующую логику:
1.	При запуске без параметров:
    * Проверяет доступность сайтов из списка (например, ya.ru, но перечень сайтов может быть изменен).
    * Проверяет доступность сервера СУБД PostgreSQL (указывается строка подключения).
    * Результат последней проверки сохраняет в файл (в JSON или XML формате), а также отправляет по электронной почте.
2.	При запуске с любым параметром:
    * Выводит результат последней проверки из сохраненного файла в консоль.


## Требования

1. Ввод данных для работы приложения НЕ должен осуществляться пользователем. Все данные должны загружаться из конфигурации приложения (например, из файла appsettings.json).
2. Список сайтов для проверки должен быть расширяемым и храниться в файле конфигурации приложения.
3. Строка соединения и адрес электронной почты для отправки также должны храниться в файле конфигурации приложения.
4. Необходимо настроить логирование операций в файл. Логироваться должна информация об успехе или неуспехе выполняемых проверок, а также отправки данных на электронную почту и сохранения результата проверки в файл. Кроме того, возникающие исключительные ситуации при работе приложения тоже могут логироваться. Для реализации логрования можно использовать сторонние NuGet-пакеты.
5. Описание сервиса и информацию по его использованию необходимо выполнить в файле README.md.
6. Программный код должен отражать понимание автором «хорошего кода». Для проверки стиля кода возможно дополнительно настроить автоматический анализ кода на основе .editorconfig-файла. 
7. Всё, что не оговорено в задании явно, решается на усмотрение соискателя.
8. Результат выполнения задания требуется опубликовать в личном репозитории на GitHub с использованием нескольких коммитов, ссылку на репозиторий необходимо отправить на <job@neoplatform.ru>.
