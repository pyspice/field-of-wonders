Клиент-серверная игра Поле Чудес

Для запуска сервера требуется node.js версии 14.16.0 или выше, npm версии 6.14.11 или выше. 
Необходимо в папке client выполнить команды:
* npm install
* npx webpack

Затем нужно в папке server выполнить команды:
* npm install
* node index.js

Параметры сервера опциональны, но можно дополнить запуск сервера портом, количеством попыток на угадывание и словарем слов (подробнее - node index.js --help).

Сервер запустится на localhost с указанным портом, 
для запуска игры достаточно открыть в браузере страницу
http://localhost:<ваш порт>. При запуске эту ссылку
сервер выводит в консоль.
