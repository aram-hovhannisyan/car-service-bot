1. Установка:
Установите необходимые зависимости, выполнив 
pip install -r requirements.txt
Создайте файл config.py с токеном API Telegram Bot и конфигурацией базы данных.
2. Настройка бота:
Получите токен Telegram Bot API от BotFather в Telegram.
Настройте конфигурацию базы данных в config.py, включая имя базы данных.
Укажите в config.py идентификаторы пользователей для администраторов бота.
3. Запуск бота:
Запустите main.py скрипт бота, чтобы запустить его.
Пользователи могут взаимодействовать с ботом, начав разговор и используя команды типа 
/start для начала.
4. Использование:
Обычные пользователи могут взаимодействовать с ботом для просмотра услуг, размещения заказов и выполнения других действий.
Администраторы имеют дополнительные привилегии для управления услугами, запчастями, пользователями и заказами с помощью административных команд типа /admin.
5. Административные команды:
Администраторы могут использовать команды типа /admin для доступа к административным функциям, таким как добавление или удаление услуг, запчастей и пользователей.
6. Управление базой данных:
Бот использует базу данных SQLite3, к которой можно получить доступ и управлять ею с помощью соответствующих инструментов или скриптов SQLite3.
7. /unanswered_messages Эта команда позволяет администраторам просматривать все оставшиеся без ответа сообщения, отправленные в службу технической поддержки.
8. Бот включает в себя функцию планирования, реализованную с помощью методов потоков, для отправки пользователям напоминаний за день до запланированных встреч в автосервисе, что позволяет им подтверждать, отменять или переносить заказы, при этом изменения отображаются администратору для мониторинга.